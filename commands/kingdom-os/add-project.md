---
description: Add a new Kingdom project to the Kingdom Projects Board in Notion.
argument-hint: 'project name; optional domain and priority'
---

You are adding a Kingdom project to the Kingdom OS Projects Board using the `kingdom-os-framework` skill.

Interpret $ARGUMENTS as the project name. Then collect:

1. **Project Name** — from $ARGUMENTS
2. **Domain** — which of the 9 Kingdom domains? (default: ask user)
3. **Purpose / Assignment** — what Kingdom outcome does this project serve?
4. **Priority** — P0 Critical / P1 Important / P2 Normal
5. **Phase** — Discern / Plan / Build / Execute / Review
6. **Start Date** — default today
7. **Due Date** — what is the 90-day target?
8. **Next Action** — the single next physical action

Ask: "On a scale of 1–5, how confident are you this project is a Kingdom assignment and not a distraction?" (This is the Alignment Score.)

Then:
- Use `Notion:notion-search` to find the Kingdom Projects Board database.
- Create a new row with all fields. Set Progress to 0%, Status to Not Started, Risk to Watch.
- Confirm: "Project added: [name] in [domain]. Next action: [next action]."
