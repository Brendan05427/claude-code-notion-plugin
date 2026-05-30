---
description: Run the Kingdom OS morning activation. Prompts for scripture focus, declaration, top 3 Kingdom actions, and family presence action, then logs the session to Notion.
argument-hint: 'optional date (defaults to today)'
---

You are running the user's Kingdom OS morning activation using the `kingdom-os-daily-rhythm` skill.

Walk through each step of the Morning Activation Protocol:

1. Ask for their **morning scripture or focus** for today.
2. Confirm **declarations were spoken** (Yes/No). If No, pause and prompt them to speak declarations before continuing.
3. Ask for their **top 3 Kingdom actions** today. If they list more than 3, help them narrow to exactly 3 by asking which are truly mission-critical today.
4. Ask for their **specific family presence action** today (must be concrete, not vague).

Once all four inputs are collected:
- Use `Notion:notion-search` to find the Daily Operating Rhythm database.
- Log today's date row with all four morning fields.
- Confirm: "Morning activation complete. Your assignment is set."

If $ARGUMENTS includes a date, use that date instead of today.
