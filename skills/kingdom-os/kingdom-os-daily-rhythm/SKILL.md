---
name: kingdom-os-daily-rhythm
description: Governs the three-part Kingdom OS daily execution cycle. Teaches Claude to run morning activation (identity + assignment + top 3 actions), midday alignment (energy + drift check), and evening debrief (win + obedience step + inbox-zero + scoring), logging each session to the Notion Daily Operating Rhythm database.
---

# Kingdom OS Daily Operating Rhythm

Run this cycle every day. The goal is not productivity — it is governed alignment with identity, assignment, and the Spirit.

## Overview

| Session | Time | Purpose |
|---|---|---|
| Morning Activation | Start of day | Establish identity and assignment before the noise begins |
| Midday Alignment | Midday | Correct drift; recalibrate energy and priorities |
| Evening Debrief | End of day | Distill learning, record fruit, clear the inbox |

---

## Morning Activation Protocol

**Goal**: Begin from alignment, not reaction.

Steps to run through with the user:

1. **Morning Scripture / Focus**
   - Ask: "What scripture or theme is your focus today?"
   - Capture the passage and a one-sentence observation

2. **Declaration Spoken?**
   - Ask: "Did you speak your declarations this morning?" (Yes / No)
   - If No: prompt the user to speak them before continuing

3. **Top 3 Kingdom Actions**
   - Ask: "What are your top 3 Kingdom actions for today?"
   - Each action should tie to an active project or domain
   - Limit to exactly 3; remove anything that is not mission-critical

4. **Family Presence Action**
   - Ask: "What is your specific family presence action today?"
   - Must be concrete (e.g., "dinner at the table together", "20 min reading with [child]")

Log to Notion: `Notion:notion-create-pages` or `Notion:notion-update-page` in the Daily Operating Rhythm database for today's date row.

---

## Midday Alignment Protocol

**Goal**: Correct drift before the afternoon compounds it.

Check-in questions:

1. **Energy**: High / Moderate / Low
2. **Distraction / Drift**: What pulled you off assignment today?
3. **Midday Alignment Check**: Are you still on your top 3 Kingdom actions? (Yes / No)

Provide a one-sentence recalibration prompt based on the answers.

Log midday fields to today's Notion row.

---

## Evening Debrief Protocol

**Goal**: Distill learning, capture fruit, close the loop.

Steps:

1. **Evening Win**
   - Ask: "What was your top win today?"
   - Frame wins as evidence of Kingdom order, not just task completion

2. **Obedience Step Completed?**
   - Ask: "Did you complete your obedience step today?" (Yes / No)

3. **Inbox Processed?**
   - Ask: "Is your inbox at zero?" (Yes / No)
   - If No: help the user do a quick capture sweep before closing

4. **Gratitude / Testimony**
   - Ask: "What are you grateful for or what testimony do you have today?"

5. **Formation Score (1–5)**
   - Ask: "How would you score your spiritual and character formation today? (1–5)"

6. **Execution Score (1–5)**
   - Ask: "How would you score your execution on Kingdom assignments today? (1–5)"

7. **Daily Alignment** = average of Formation and Execution scores (calculated automatically)

Log all evening fields to today's Notion row and confirm the row is marked complete.

---

## Notion Field Mapping

When writing to the Daily Operating Rhythm database, map inputs to these columns:

| Field | Type | Source |
|---|---|---|
| Date | Date | Today's date |
| Morning Scripture / Focus | Text | Step 1 |
| Declaration Spoken? | Select (Yes/No) | Step 2 |
| Top 3 Kingdom Actions | Text | Step 3 |
| Family Presence Action | Text | Step 4 |
| Midday Alignment Check | Select (Yes/No) | Midday |
| Energy | Select (High/Moderate/Low) | Midday |
| Distraction / Drift | Text | Midday |
| Evening Win | Text | Evening 1 |
| Obedience Step Completed? | Select (Yes/No) | Evening 2 |
| Inbox Processed? | Select (Yes/No) | Evening 3 |
| Gratitude / Testimony | Text | Evening 4 |
| Formation Score | Number (1–5) | Evening 5 |
| Execution Score | Number (1–5) | Evening 6 |
| Daily Alignment | Number (avg) | Calculated |

---

## Key Principles for Daily Execution

- The morning sets the posture; the evening closes the loop
- Declarations are not optional — they are identity rehearsal
- Family presence is a Kingdom action, not a personal preference
- Inbox-zero is a stewardship discipline, not a productivity hack
- Score honestly — a 3 is not failure; it is a correction signal
