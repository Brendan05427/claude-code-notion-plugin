---
name: kingdom-os-mfr
description: Governs the Monthly Financial Review (MFR) for Estica Learner Centre. Teaches Claude the full 4-phase operational close process — data reconciliation, accounts receivable aging, expense oversight, and management reporting — so it can walk Finance Admin and Management through each task and log progress to Notion by the 7th of every following month.
---

# Kingdom OS — Monthly Financial Review (MFR)

**Entity**: Estica Learner Centre  
**Document**: MFR-2026-V1  
**Review Cycle**: Monthly Operational Close  
**Target Completion**: 7th of every following month  

**Objective**: Ensure accurate financial reporting, robust oversight of fee collections, tracking of outstanding aging accounts, and alignment with South African regional operational standards for independent educational entities.

---

## MFR Structure

The MFR runs 4 sequential phases covering 11 tasks. Tasks are owned by either Finance Admin or Management.

| Phase | Focus | Task Count | Owner(s) |
|---|---|---|---|
| Phase 1 | Data Gathering & Reconciliations | 3 | Finance Admin |
| Phase 2 | Accounts Receivable & Aging Reports | 3 | Finance Admin + Management |
| Phase 3 | Operational Expense Oversight | 3 | Finance Admin + Management |
| Phase 4 | Management Reporting & Strategy | 3 | Management |

---

## Phase 1: Data Gathering & Reconciliations

*Verification of primary entry data and bank balances to establish a single source of truth.*

### Task 1.1 — Bank Statement Reconciliation
- **Owner**: Finance Admin
- **Procedure**: Download and reconcile all operational bank accounts. Ensure all matching transactions are cleared. Flag unrecognized items for inspection.
- **Evidence of Completion**: All accounts reconciled, flagged items documented.

### Task 1.2 — Fee Processing Verification
- **Owner**: Finance Admin
- **Procedure**: Cross-match learner monthly tuition fees received against the active registration accounts database. Confirm allocations match specific learner profiles.
- **Evidence of Completion**: All received fees matched to learner profiles with no unallocated amounts.

### Task 1.3 — Expense & Receipt Matching
- **Owner**: Finance Admin
- **Procedure**: Upload and attach all physical and digital receipts to correspond with business expenses — curriculum materials, logistics, and operational utility payouts.
- **Evidence of Completion**: All expenses have attached receipts; no unmatched transactions.

---

## Phase 2: Accounts Receivable & Aging Reports

*Critical oversight of outstanding fees to safeguard cash flow stability and learner tenure continuity.*

### Task 2.1 — Extract Aging Accounts Report
- **Owner**: Finance Admin
- **Procedure**: Generate the detailed aging accounts report categorizing outstanding balances into 30, 60, and 90+ day cohorts.
- **Evidence of Completion**: Report generated with all three aging bands populated.

### Task 2.2 — Identify Critical Defaulters
- **Owner**: Management
- **Procedure**: Isolate accounts exceeding 60 days. Cross-reference previous payment agreements or special arrangements made with parents or guardians.
- **Evidence of Completion**: Critical defaulter list compiled with payment history notes.

### Task 2.3 — Issue Reminders & Notices
- **Owner**: Finance Admin
- **Procedure**: Dispatch personalized fee reminders and formal administrative notifications according to the formal escalation procedure.
- **Evidence of Completion**: All reminders dispatched and logged; escalation procedure followed.

---

## Phase 3: Operational Expense Oversight

*Evaluating resource distribution, staff expenditures, and institutional infrastructure overheads.*

### Task 3.1 — Payroll & Staff Allowances
- **Owner**: Management
- **Procedure**: Review payroll records for instructional and administrative staff. Verify any training allocations or special reimbursements incurred during the period.
- **Evidence of Completion**: Payroll confirmed, reimbursements verified and coded.

### Task 3.2 — Curriculum & Supply Costs
- **Owner**: Management
- **Procedure**: Analyze monthly expenditures on educational paths (CAPS/GED materials) to check alignment with projected term intake and per-learner operational budgets.
- **Evidence of Completion**: Curriculum spend reconciled against per-learner budget; variances noted.

### Task 3.3 — Fixed Infrastructure & Rent
- **Owner**: Finance Admin
- **Procedure**: Confirm processing of recurring space allocations, lease obligations, or local utility assessments specific to regional facility branches.
- **Evidence of Completion**: All lease and utility payments confirmed processed.

---

## Phase 4: Management Reporting & Strategy

*Translating monthly financial figures into actionable insights for educational advancement.*

### Task 4.1 — Income Statement Review
- **Owner**: Management
- **Procedure**: Evaluate the final monthly Profit & Loss statement against the annual master budget. Note substantial variances for strategic correction.
- **Evidence of Completion**: P&L reviewed; variances documented with corrective notes.

### Task 4.2 — Strategic Forecast Update
- **Owner**: Management
- **Procedure**: Adjust quarterly cash flow projections based on exact collection rates, upcoming seasonal design/branding needs, or upcoming academic registration cycles.
- **Evidence of Completion**: Cash flow forecast updated and saved.

### Task 4.3 — Sign-Off & Archival
- **Owner**: Management
- **Procedure**: Formally execute and lock the monthly financial period. Securely archive electronic records within the Master Operational System.
- **Evidence of Completion**: Period locked; all records archived.

---

## Notion Database Mapping

When logging MFR progress to Notion, look for databases by these names:

| MFR Section | Notion Database (approximate match) |
|---|---|
| MFR Checklist / Task Log | "MFR Checklist", "Monthly Financial Review", or "Operational Close" |
| Aging Accounts | "Aging Report", "Accounts Receivable", or "Fee Defaulters" |
| Expense Log | "Expense Tracker" or "Monthly Expenses" |
| Management Reports | "Financial Reports" or "P&L Review" |

Use `Notion:notion-search` to locate the correct database before creating or updating entries.

---

## Behavioral Defaults

- Run phases in sequence (1 → 2 → 3 → 4); do not skip ahead
- Log each completed task immediately — do not batch at the end
- When a task is Finance Admin–owned, confirm the admin has completed it before marking done
- When a task is Management–owned, route confirmation to the appropriate decision-maker
- Flag any unrecognized bank items, unmatched receipts, or 90+ day defaulters as high-priority items requiring immediate attention
- The MFR is due by the **7th of every following month** — track this deadline and surface it proactively
