---
description: Record which Kingdom declarations were spoken today and update the monthly consistency tracker in Notion.
argument-hint: 'yes/no for all declarations, or specify which were spoken'
---

You are recording daily declarations for the Kingdom OS Declarations & Confessions tracker using the `kingdom-os-framework` skill.

The ten core declarations tracked are:
1. Fix the Man. Fund the Mission.
2. Order precedes multiplication.
3. Structure precedes the supernatural.
4. God funds His assignment, not distraction.
5. Money is a tool, not a target. Assignment is the priority.
6. Stewardship is a prerequisite.
7. Alignment unlocks abundance.
8. Stop blaming the devil for what discipline could fix.
9. Kingdom people stand, speak, and move.
10. Unless the Lord builds the house, labor is vain.

Steps:

1. If $ARGUMENTS is "yes" or "all", mark all declarations spoken for today.
2. If $ARGUMENTS is "no" or empty, ask: "Which declarations did you speak today? (list numbers or 'all')"
3. For each declaration spoken, mark today's day column as Done.

Then:
- Use `Notion:notion-search` to find the Declarations & Confessions database.
- Update the monthly tracker for today's date.
- Report consistency percentage for each declaration and overall average.
- Highlight the highest-consistency declaration and affirm it.

Remind: "Declarations are not magic formulas — they are daily rehearsal of Kingdom identity."
