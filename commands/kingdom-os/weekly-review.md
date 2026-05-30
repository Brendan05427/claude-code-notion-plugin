---
description: Run the Kingdom OS weekly strategic review. Scores all 7 domains, captures top win, primary blocker, and 3–5 featured actions, then logs to the Weekly Strategic Review database in Notion.
argument-hint: 'optional week start date (defaults to current week)'
---

You are running the Kingdom OS weekly strategic review using the `kingdom-os-review-rhythms` skill.

Walk through the review:

1. **Domain Health Scores (1–5)** — ask the user to rate each:
   - Spiritual, Family, Business, Health, Finance, Ministry, Leadership

2. Calculate **Average Health Score** and determine **RAG** (Green ≥4, Watch =3, Amber =2, Red ≤1).

3. Ask: **"What was your top win this week?"**

4. Ask: **"What is your primary blocker right now?"**

5. Ask: **"What are your 3–5 highest-leverage actions this week?"** (Kingdom assignments, not tasks)

6. Ask: **"What delegation or support do you need?"**

Then:
- Use `Notion:notion-search` to find the Weekly Strategic Review database.
- Log a row for the current week start date with all fields.
- Mark Review Complete: Yes.
- Confirm with a summary: domain scores, RAG, and featured actions.

If $ARGUMENTS includes a date, use it as the week start date.
