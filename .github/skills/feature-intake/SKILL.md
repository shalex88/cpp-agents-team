---
name: feature-intake
description: 'Use when scoping a new feature request, defining goals, non-goals, constraints, risks, required specialists, and done criteria before implementation.'
argument-hint: 'Describe the feature request and known constraints.'
user-invocable: true
---

# Feature Intake

Use this skill when a feature needs structured intake before architecture or implementation starts.

## Produce

- Request summary
- Goals and non-goals
- Constraints
- Risks
- Required specialists
- Done criteria

## Procedure

1. Summarize the request in concrete engineering terms.
2. Separate goals from non-goals.
3. Identify technical, testing, security, CI, and performance constraints.
4. Decide which specialists need to be involved.
5. Define done criteria that can be validated later.

## Checks

- Make assumptions explicit.
- Flag unclear scope early.
- Involve Architect if APIs, module boundaries, ownership, or error handling may change.