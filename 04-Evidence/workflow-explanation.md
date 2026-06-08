# 04 - Evidence: Jira Board & QA Workflow

This folder contains visual evidence of how I collaborated with the developer through Jira, plus an explanation of the workflow I used to manage defects from discovery to closure.

## 📄 Files

| File | Description | 
|---|---|
| `jira-board-overview.png` | Full Jira board showing all tickets across workflow stages |
| `jira-board-ticket-detail.png` | Close-up of a single ticket with comments, attachments, and status changes | 

## 🔁 Jira Workflow

The development team (developer + me ) used 5-stage Jira board to manage all work - both feature development and bug fixes.

| Stage | Meaning |
|---|---|
| **To Do** | Work that has been identified but not yet started |
| **In Development** | Developer is actively working on the ticket |
| **QA** | Ready for me to test — feature work to verify, or a bug fix to validate |
| **Done** | I have verified the work and signed off |
| **Deployed** | Code has been deployed to the live environment |

## 🐛 Defect Lifecycle

Whenever I found a bug, it went through this process:

1. **Discover** — found during scripted test execution or exploratory testing
2. **Document** — filed in the Bug Tracker spreadsheet AND as a Jira ticket with full details (steps, environment, expected vs actual, screenshots)
3. **Triage** — discussed severity and priority with the developer
4. **In Development** — developer pulls the ticket and works on the fix
5. **QA** — once fixed, the ticket moves back to me for verification
6. **Verify** — I re-run the failing test case and check for regressions
7. **Done** — if the fix works, ticket closes; if not, it goes back to In Development with my notes

## 🤝 Collaboration Notes

Working as the sole QA with a single developer taught me to:

- **Communicate clearly** — every bug report had to be detailed enough that the developer could reproduce it without asking questions
- **Prioritize ruthlessly** — with limited dev time, I learned to flag what was truly blocking vs. nice-to-fix
- **Verify thoroughly** — re-test the original bug + check that the fix didn't break anything adjacent
- **Document for the future** — even closed tickets and "won't fix" decisions were documented for traceability

## 📸 Screenshots

`![Jira Board Overview](./jira-board-overview.png)` 

<img width="1905" height="898" alt="2026-06-08 07_59_51-" src="https://github.com/user-attachments/assets/033def96-5006-4006-9fa7-38b46416da1d" />

---

`![Jira Ticket Detail](./jira-ticket-detail.png)`


<img width="1917" height="859" alt="BUG1" src="https://github.com/user-attachments/assets/3cbe980d-3ce5-4c50-a79e-107b1efa3c9e" />

---

<img width="1909" height="856" alt="BUG2" src="https://github.com/user-attachments/assets/1b349fee-6302-499e-a912-93dd84df9392" />

---

<img width="1911" height="855" alt="BUG3" src="https://github.com/user-attachments/assets/4582cfb8-e30d-47cd-823d-5fd354307a22" />

---

<img width="1920" height="860" alt="BUG4" src="https://github.com/user-attachments/assets/a2700c0f-0aae-4089-9611-38acbe929ff9" />

---

<img width="1919" height="856" alt="BUG5" src="https://github.com/user-attachments/assets/9172328c-89b2-4ccd-a6fe-97fd8583a094" /> 

---

<img width="1917" height="857" alt="BUG6" src="https://github.com/user-attachments/assets/4a2218eb-bf00-4c8d-a3d8-838563512ef7" />

---

<img width="1916" height="855" alt="BUG7" src="https://github.com/user-attachments/assets/740fe674-c226-4761-9647-6c80f57e2ac1" /> 

---

<img width="1922" height="865" alt="BUG8" src="https://github.com/user-attachments/assets/cc4ea9fe-302e-48da-8207-f09811e681be" />

---

<img width="1916" height="857" alt="BUG9" src="https://github.com/user-attachments/assets/ce3fa923-948f-40a9-a025-dc809855e80e" />


---

[← Back to main portfolio](../README.md)
