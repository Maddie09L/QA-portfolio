# BUG-LOGIN-01: Password show/hide icon disappears after field loses and regains focus

| | |
|---|---|
| **Bug ID** | BUG-LOGIN-01 |
| **Module** | Authentication / Login |
| **Severity** | 🟡 Medium |
| **Priority** | Medium |
| **Status** | ✅ Closed / Fixed |
| **Reported By** | Maddie |
| **Date Reported** | [March 17, 2026 at 10:03 AM] |

---

## 📝 Summary

The show/hide (eye icon) toggle on the password field disappears or reappears inconsistently after the password field loses and regains focus. The behavior is different across Chrome, Edge, and Firefox — making the bug a cross-browser UI consistency issue as well as a usability problem.

## 🌐 Environment

- **OS:** Windows 11
- **Browsers tested:**
  - Chrome 145.0.7032.100
  - Microsoft Edge 145.0.3800.97
  - Firefox 147.0.1

## ✅ Pre-Conditions

- The user is on the **Login** page
- The password field is visible and editable

## 🔁 Steps to Reproduce

1. Open the application login page
2. Click inside the **Password** field
3. Enter any value into the password field
4. Click **outside** the password field (lose focus)
5. Click back **inside** the password field (regain focus)
6. Observe the behavior of the show/hide eye icon

## 🎯 Expected Result

The show/hide eye icon should **remain visible and functional** whenever the password field contains a value, regardless of focus state. Behavior should be consistent across all supported browsers.

## ❌ Actual Result

The behavior differs by browser:

- **Chrome:** The show/hide icon does **not** appear on the password field after focus is lost and regained.
- **Firefox:** The show/hide icon does **not** appear, even when the field is focused and contains a value.
- **Edge:** The behavior is different again — the password show/hide icon is no longer visible after the field loses focus and is refocused.

This inconsistency makes the feature unreliable across browsers and confuses users who expect to be able to verify what they typed.

## 💬 Notes

This bug was particularly valuable to file because cross-browser inconsistencies are easy to miss in development (developers often build and test in a single browser). Filing it with all three browsers documented allowed the developer to address the root cause rather than patch one browser at a time.

---

[← Back to bug reports](../README.md) • [← Back to main portfolio](../../README.md)
