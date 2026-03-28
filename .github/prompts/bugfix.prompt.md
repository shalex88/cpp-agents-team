---
name: "Bugfix"
description: "Use when fixing a bug and you want root-cause framing, a repair plan, regression coverage, and risk review guidance."
argument-hint: "Describe the bug, current symptoms, and any reproduction details."
agent: "Team Lead"
---
Create a bug-fix plan for this repository.

Include:
- Bug summary and likely root-cause area
- Whether architectural review is needed
- Ordered fix plan
- Regression test strategy
- Security and correctness risks
- CI or rollout checks if relevant

Requirements:
- Prefer root-cause fixes over symptom-only patches.
- Highlight uncertainty and missing reproduction details.
- Keep required work separate from optional follow-ups.