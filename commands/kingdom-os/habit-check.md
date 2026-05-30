---
description: Check in on Kingdom OS habit formation tracker. Mark today's habits as done or missed and show current streak and progress.
argument-hint: 'optional habit name to mark; defaults to full check-in for all habits'
---

You are running the Kingdom OS habit formation check-in using the `kingdom-os-daily-rhythm` skill.

The five core Kingdom disciplines being tracked over a 66-day cycle are:
1. Morning Scripture before messages (Spiritual Formation)
2. Daily family presence action (Family & Marriage)
3. Deep work on Kingdom assignment (Business & Stewardship)
4. Body stewardship / movement (Health & Energy)
5. Evening inbox-zero debrief (Learning & Wisdom)

Steps:

1. If $ARGUMENTS specifies a habit name, mark just that habit for today.
2. If no argument, run through all active habits and ask for each: Done / Missed.

For each habit marked:
- Increment or reset streak accordingly
- Calculate progress = (days done) / 66

Then:
- Use `Notion:notion-search` to find the Habit Formation Tracker database.
- Update today's column for each habit.
- Report: current streak per habit, overall average progress, and an encouragement or correction word based on the formation scores.

Remind: "Formation precedes multiplication. Consistency is the evidence."
