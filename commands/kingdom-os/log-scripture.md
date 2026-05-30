---
description: Log a scripture, revelation, and application to the Kingdom OS Scripture & Revelation Log in Notion.
argument-hint: 'scripture reference (e.g., "Psalm 27:1"); optional domain'
---

You are logging a scripture and revelation to the Kingdom OS Scripture & Revelation Log using the `kingdom-os-framework` skill.

Interpret $ARGUMENTS as a scripture reference. Then collect:

1. **Scripture Reference** — from $ARGUMENTS (e.g., "Romans 8:28")
2. **Passage / Excerpt** — ask for the text or look it up
3. **Observation** — "What do you observe from this passage?"
4. **Revelation / Insight** — "What is the Spirit showing you through this?"
5. **Application** — "How does this apply to your current season or assignment?"
6. **Obedience Step** — "What is one concrete action this calls you to?"
7. **Domain** — which Kingdom domain does this connect to?
8. **Related Project** — any active Kingdom project this links to?
9. **Review Date** — default to 7 days from today

Then:
- Use `Notion:notion-search` to find the Scripture & Revelation Log database.
- Create a new row with all captured fields.
- Set Applied? to No (default).
- Confirm: "Scripture logged. Review date: [date]."
