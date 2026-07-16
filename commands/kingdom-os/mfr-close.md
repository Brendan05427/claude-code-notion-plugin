---
description: Execute the Estica Learner Centre MFR sign-off and archival. Confirms all phases are complete, locks the financial period, and archives records in Notion.
argument-hint: 'month being closed (e.g., "June 2026")'
---

You are executing the MFR sign-off and archival for Estica Learner Centre using the `kingdom-os-mfr` skill.

Interpret $ARGUMENTS as the month being closed.

Before proceeding with sign-off, verify all prior phases are complete:

1. Ask: "Are all Phase 1 reconciliations complete?" (Yes / No)
2. Ask: "Are all Phase 2 aging tasks complete — report extracted, defaulters identified, reminders issued?" (Yes / No)
3. Ask: "Are all Phase 3 expense reviews complete — payroll, curriculum costs, rent confirmed?" (Yes / No)
4. Ask: "Is the Phase 4 Income Statement reviewed and the Strategic Forecast updated?" (Yes / No)

If any phase is incomplete:
- Do not proceed with sign-off.
- List the outstanding items and their responsible owners.
- Remind: "The MFR cannot be locked until all phases are complete."

If all phases are complete:
- Ask: "Is Management ready to formally execute and lock the [month] financial period?"
- On confirmation:
  1. Use `Notion:notion-search` to find the MFR Checklist or Master Operational System database.
  2. Mark the period as Locked / Archived.
  3. Log the sign-off date and the name of the authorizing manager.
  4. Confirm: "[Month] MFR signed off and archived. Period is now locked."
- Remind: next MFR is due by the 7th of [following month].
