# 02 — Test Cases

This folder contains the master test case repository for the Vector platform — **200+ manually authored test cases** organized by module.

## 📄 Files

| File | Description |
|---|---|
| [Test cases Repository.xlsx](https://github.com/user-attachments/files/28768588/Test.cases.Repository.xlsx) | Full test case repository |
| [Test Cases Repository.pdf](https://github.com/user-attachments/files/28768617/Test.Cases.Repository.pdf) | PDF preview  |
| `Screenshots` | Visual previews of the spreadsheet structure <img width="1828" height="353" alt="Screenshot preview" src="https://github.com/user-attachments/assets/ea0507d8-1b66-4371-948d-2d54d5fb28b5" /> |

## 📋 Test Case Structure

Each test case in the master spreadsheet follows a consistent format:

| Column | Description |
|---|---|
| **Module** | Functional area (e.g., Authentication, Registration, User Portal) |
| **Test Case ID** | Unique identifier (e.g., `TS-AUTH-052`, `TS-ADMIN-001`) |
| **Test Case Title** | Short, descriptive title of what is being verified |
| **Pre-Conditions** | What must be true before the test starts |
| **Test Steps** | Numbered, executable steps |
| **Test Data** | Specific inputs used (where applicable) |
| **Expected Results** | What should happen if the system works correctly |
| **Status (Pass/Fail)** | Execution result |

## 🗂️ Modules Covered

The test repository is split across multiple worksheets, one per module:

- **Auth - Login** — login flows, session handling, remember-me, browser navigation
- **Auth - Reset Password / Links** — password recovery, link expiration, password rules
- **Registration** — account creation, field validation, email format, social sign-up
- **User Portal - Coach Application** — profile, image upload, file validation
- **Administrative** — admin settings, profile picture management
- *(and more)*

## 🎯 Test Case Design Approach

I used a mix of:

- **Positive testing** — verifying the happy path works as expected
- **Negative testing** — invalid inputs, error handling, security-adjacent cases
- **Boundary testing** — character limits, file size limits, edge values
- **Cross-browser testing** — confirming behavior on Chrome, Edge, and Firefox
- **Exploratory testing** — finding bugs outside the scripted cases

---

[← Back to main portfolio](../README.md)
