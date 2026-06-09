# 03 — Bug Reports

This folder contains my full defect log for the Vector platform, plus 3 featured bug reports written up in detail.

## 📄 Files

| File / Folder | Description |
|---|---|
| [Bug Tracker.xlsx](https://github.com/user-attachments/files/28718173/Bug.Tracker.xlsx) | Full bug tracker with all defects, severity, priority, and status  |
| [Bug Tracker.pdf](https://github.com/user-attachments/files/28718180/Bug.Tracker.pdf) | PDF preview of the bug tracker  |
| featured-bugs | 3 detailed bug reports in markdown format (recommended starting point) |
| screenshots | Visual previews of the tracker <img width="1334" height="703" alt="Bug Tracker" src="https://github.com/user-attachments/assets/42e8d5da-020a-42f7-8019-8c9bc043970d" />
 |

## 🐛 Bug Report Format

Every bug I filed includes the following fields:

| Field | Why It Matters |
|---|---|
| **Bug ID** | Unique identifier (e.g., `BUG-LOGIN-01`, `BUG-RESET-01`) |
| **Title** | Clear, one-line description of the issue |
| **Module** | Functional area affected |
| **Severity** | Critical / High / Medium / Low — impact on the user |
| **Priority** | High / Medium / Low — urgency of fix |
| **Environment** | OS + browser + version (full details for reproducibility) |
| **Pre-Conditions** | What must be set up before reproducing |
| **Steps to Reproduce** | Numbered, exact steps anyone can follow |
| **Expected Result** | What should happen |
| **Actual Result** | What actually happened |
| **Screenshots / Video** | Visual evidence |
| **Status** | Open / In Progress / Fixed / Closed |

## ⭐ Featured Bugs (Read These First)

These three are good examples of the depth and range of my defect reporting:

1. [**BUG-RESET-01:** Password reset accepts current password as new password](./featured-bugs/BUG-RESET-01-password-reset.md)
   *Medium severity • Security-adjacent • Pre-release catch*

2. [**BUG-LOGIN-01:** Password show/hide icon disappears after field loses focus](./featured-bugs/BUG-LOGIN-01-show-hide-icon.md)
   *Medium severity • Cross-browser UI bug • Inconsistent across Chrome/Edge/Firefox*
   
3. [**BUG-LOGIN-02:** Keyboard shortcuts (Ctrl+C, Ctrl+V) fail in password field](./featured-bugs/BUG-LOGIN-02-keyboard-shortcuts.md)
   *Low severity • UX accessibility issue • Documents intentional behavior*

   ## 📊 Bug Summary

> _Tip: Add a table here once you have your final bug counts. Example:_

| Severity | Count |
|---|---|
| Critical | [2] |
| High | [6] |
| Medium | [25] |
| Low | [2] |
| **Total** | **[35]** |

---

[← Back to main portfolio](../README.md)
