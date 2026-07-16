---
description: Run the Estica Learner Centre Monthly Financial Review (MFR). Walks through all 4 phases and 11 tasks, confirms completion with the responsible party, and logs progress to Notion.
argument-hint: 'month being closed (e.g., "June 2026"); defaults to previous month'
---

You are running the Monthly Financial Review (MFR) for Estica Learner Centre using the `kingdom-os-mfr` skill.

Interpret $ARGUMENTS as the month being closed. If not provided, default to the previous calendar month.

Work through all 4 phases sequentially. For each task:
1. State the task name, owner, and what it requires.
2. Ask: "Is this complete?" (Yes / No / In Progress)
3. If No or In Progress, capture a blocker note and move on — do not halt the review.
4. Log the completion status to Notion.

---

**Phase 1: Data Gathering & Reconciliations** (Finance Admin)
- Task 1.1 — Bank Statement Reconciliation
- Task 1.2 — Fee Processing Verification
- Task 1.3 — Expense & Receipt Matching

**Phase 2: Accounts Receivable & Aging Reports** (Finance Admin + Management)
- Task 2.1 — Extract Aging Accounts Report
- Task 2.2 — Identify Critical Defaulters
- Task 2.3 — Issue Reminders & Notices

**Phase 3: Operational Expense Oversight** (Finance Admin + Management)
- Task 3.1 — Payroll & Staff Allowances
- Task 3.2 — Curriculum & Supply Costs
- Task 3.3 — Fixed Infrastructure & Rent

**Phase 4: Management Reporting & Strategy** (Management)
- Task 4.1 — Income Statement Review
- Task 4.2 — Strategic Forecast Update
- Task 4.3 — Sign-Off & Archival

---

After completing all phases:
- Use `Notion:notion-search` to find the MFR Checklist database.
- Log each task's status (Complete / Incomplete / Blocked) and any blocker notes.
- Summarize: total tasks complete, incomplete tasks with owners, and whether the MFR is cleared for sign-off.
- Remind: MFR must be completed by the **7th of the following month**.
