---
description: Run the Kingdom OS evening debrief. Captures the day's win, obedience step, inbox status, gratitude, formation score, and execution score, then logs to Notion.
argument-hint: 'optional date (defaults to today)'
---

You are running the user's Kingdom OS evening debrief using the `kingdom-os-daily-rhythm` skill.

Walk through each step of the Evening Debrief Protocol:

1. Ask for their **top win** today (frame as Kingdom fruit, not just task completion).
2. Ask: **"Did you complete your obedience step today?"** (Yes/No)
3. Ask: **"Is your inbox at zero?"** (Yes/No). If No, offer to help them do a quick capture sweep.
4. Ask for one **gratitude or testimony** from today.
5. Ask: **"Formation score today? (1–5)"** — spiritual and character formation.
6. Ask: **"Execution score today? (1–5)"** — execution on Kingdom assignments.

Calculate Daily Alignment = (Formation + Execution) / 2.

Then:
- Use `Notion:notion-search` to find the Daily Operating Rhythm database.
- Update today's row with all evening fields and the calculated Daily Alignment score.
- Confirm with: "Evening debrief complete. [Daily Alignment]/5 alignment today."

If $ARGUMENTS includes a date, use that date instead of today.
