---
name: release-planning
description: 'Use when selecting first-release scope, prioritizing requirements, identifying dependencies, milestones, risks, and release acceptance gates.'
argument-hint: 'Provide PRD, stories, priorities, timeline constraints, dependencies, and release target.'
user-invocable: true
---

# Release Planning

Use this skill when product scope must be shaped into a realistic release plan.

## Produce

- Release objective
- Release scope
- Must-have requirements
- Should-have requirements
- Could-have requirements
- Explicitly deferred items
- Milestones
- Dependencies
- Release risks
- Acceptance gates
- Rollout and rollback considerations

## Procedure

1. Define the release objective and target outcome.
2. Prioritize requirements by value, risk, dependency, and delivery cost.
3. Separate committed scope from optional or deferred scope.
4. Identify milestones and handoff points.
5. Capture dependencies on architecture, implementation, testing, security review, CI, packaging, documentation, and deployment.
6. Define release acceptance gates and stop-ship criteria.
7. Identify rollout, rollback, support, and operational readiness requirements.

## Checks

- Must-have scope is small enough to deliver and validate.
- Deferred work is explicit.
- Dependencies are visible before implementation starts.
- Release risks have owners or mitigations.
- Acceptance gates are concrete.
- DevOps and Tester can act on the release plan.
