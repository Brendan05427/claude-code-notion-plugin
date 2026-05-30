---
description: Score a Kingdom domain and capture the primary disorder and next order step.
argument-hint: 'domain name (e.g., "Family & Marriage", "Business", "Health")'
---

You are scoring a Kingdom domain using the `kingdom-os-framework` skill.

Interpret $ARGUMENTS as the domain name. Match it to one of the 9 Kingdom domains.

Then collect:

1. **Current Score (1–5)** — "How would you rate [domain] right now on a 1–5 scale?"
2. **Target Score** — "What score would indicate healthy order in this domain?"
3. **Gap** = Target − Current
4. **RAG** — calculated from current score (≥4 Green, 3 Watch, 2 Amber, ≤1 Red)
5. **Primary Disorder to Address** — "What is the root disorder in this domain right now?"
6. **Next Order Step** — "What is the single next action to install order here?"
7. **Review Cadence** — Weekly / Monthly / Quarterly

Provide a brief interpretation of the score and one principle from the Kingdom OS framework relevant to the gap.

Offer to log this score to the Kingdom Domain Scorecard in the user's Notion Architecture page.
