---
name: "Refactor"
description: "Use when planning or reviewing a refactor and you want structural goals, safety constraints, incremental steps, and regression protection."
argument-hint: "Describe the code to refactor and the target improvement."
agent: "Team Lead"
---
Produce a refactor plan for this repository.

Include:
- Objective and motivation
- Architecture or dependency impact
- Safety constraints and invariants
- Incremental execution steps
- Regression protection and validation gates
- Review and rollout considerations

Requirements:
- Prefer small, reviewable refactor steps.
- Preserve behavior unless an intentional change is stated.
- Call out ownership, lifetime, or API boundary risks where relevant.