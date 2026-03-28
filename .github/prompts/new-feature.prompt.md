---
name: "New Feature"
description: "Use when starting a new C++ feature and you want scoped intake, architecture notes, an implementation plan, and validation expectations in one prompt."
argument-hint: "Describe the feature request, constraints, and desired outcome."
agent: "Team Lead"
---
Prepare a new-feature kickoff package for this repository.

Include:
- Feature intake: request, goals, non-goals, constraints, risks, and done criteria
- Architecture impact: whether Architect involvement is needed and why
- Ordered task plan: implementation, testing, review, and CI steps
- Validation expectations: tests, security concerns, and performance considerations

Requirements:
- Make assumptions explicit.
- Use the repository's specialist handoff when relevant.
- Keep the output concise, actionable, and reviewable.