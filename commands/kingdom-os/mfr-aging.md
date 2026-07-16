---
description: Run the Estica Learner Centre MFR Phase 2 — Accounts Receivable & Aging Reports. Extracts aging cohorts, identifies critical defaulters, and prepares reminders.
argument-hint: 'month being reviewed (e.g., "June 2026")'
---

You are running Phase 2 of the Monthly Financial Review — Accounts Receivable & Aging Reports — using the `kingdom-os-mfr` skill.

Interpret $ARGUMENTS as the month under review.

**Task 2.1 — Extract Aging Accounts Report**
Ask: "Has the aging accounts report been generated with 30, 60, and 90+ day cohorts?"
- If yes: ask for a summary of totals per band (30-day: R___, 60-day: R___, 90+: R___).
- If no: prompt Finance Admin to generate it before proceeding.

**Task 2.2 — Identify Critical Defaulters**
For all accounts exceeding 60 days:
- Ask: "How many learner accounts are in the 60-day or 90+ day cohorts?"
- For each critical defaulter: ask if there is an existing payment agreement or special arrangement on record.
- Flag accounts with no arrangement as escalation-required.

**Task 2.3 — Issue Reminders & Notices**
Ask: "Have personalized fee reminders been dispatched to all outstanding accounts?"
- If yes: confirm the escalation procedure was followed for 60+ day accounts.
- If no: prompt Finance Admin to dispatch reminders before closing Phase 2.

After all three tasks:
- Use `Notion:notion-search` to find the Aging Accounts or Accounts Receivable database.
- Log aging totals by band, the count of critical defaulters, and the reminder dispatch status.
- Surface any 90+ day accounts as high-priority items requiring immediate Management review.
- Confirm Phase 2 complete or note outstanding items.
