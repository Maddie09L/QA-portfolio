# BUG-LOGIN-02: Keyboard shortcuts (Ctrl+C, Ctrl+V) do not work in password field

| | |
|---|---|
| **Bug ID** | BUG-LOGIN-02 |
| **Module** | Authentication / Login |
| **Severity** | 🟢 Low |
| **Priority** | Low |
| **Status** | ✅ Closed (documented as intentional behavior) |
| **Reported By** | Maddie |
| **Date Reported** | [Date] |

---

## 📝 Summary

In the password field on the Login page, standard keyboard shortcuts behave inconsistently:

- **Ctrl+C** works and selects/copies the text
- **Ctrl+V** does **not** paste the selected text
- **Ctrl+A** and **Ctrl+Z** also do not function as expected

This inconsistency reduces usability and accessibility — especially for users relying on password managers or assistive tools.

## 🌐 Environment

- **OS:** Windows 11
- **Browser:** Chrome 145.0.7032.100
- **Also tested on:** Microsoft Edge 145.0.3800.97, Firefox 147.0.1

## ✅ Pre-Conditions

- The user is on the Login page
- The password field is editable

## 🔁 Steps to Reproduce

1. Open the application login page
2. Click inside the password field
3. Type or paste any text into the password field
4. Press **Ctrl+A** to attempt to select all text
5. Press **Ctrl+C** to copy the selected text
6. Press **Ctrl+V** to attempt to paste the copied text back into the field
7. Press **Ctrl+Z** to attempt to undo the last action

## 🎯 Expected Result

Standard keyboard shortcuts should behave consistently according to application requirements:

- If clipboard operations are allowed: Ctrl+C and Ctrl+V should both function normally
- If clipboard operations are intentionally restricted for security reasons, all related shortcuts should be handled consistently or documented in the requirements

## ❌ Actual Result

Behavior is inconsistent:
- Ctrl+C works and selects/copies the text
- Ctrl+V does not paste the copied text into the password field
- Ctrl+A and Ctrl+Z do not function


## 💬 Notes & Developer Discussion

After triage, the developer confirmed this is **intentional behavior** — password field paste restrictions are a common (if debated) security pattern to prevent clipboard-based credential leakage. However, the inconsistency (Ctrl+C works, Ctrl+V doesn't) was noted as worth documenting.

**Status:** Closed — Not a bug (intentional behavior). Filed for traceability and noted for inclusion in future requirements documentation.

> 💡 **Why I'm featuring this bug:** Not every "bug" turns out to be a defect. This one is a good example of how QA work also surfaces ambiguous behavior that should be documented in requirements — not just to fix, but to clarify.

---

[← Back to bug reports](../README.md) • [← Back to main portfolio](../../README.md)
