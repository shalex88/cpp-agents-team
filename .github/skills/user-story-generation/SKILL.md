---
name: user-story-generation
description: 'Use when converting PRD requirements into backlog-ready user stories with acceptance criteria, priority, dependencies, and validation notes.'
argument-hint: 'Provide the PRD requirements, target users, release scope, and known dependencies.'
user-invocable: true
---

# User Story Generation

Use this skill after product discovery or PRD generation when requirements need to become backlog-ready work.

## Produce

- Epics when needed
- User stories
- Acceptance criteria
- Priority
- Dependencies
- Assumptions
- Validation notes
- Traceability IDs

## Procedure

1. Group related requirements into epics when the scope is large.
2. Write each story from the user or stakeholder perspective.
3. Use this story shape: As a named role, I want a capability, so that I can achieve an outcome.
4. Add acceptance criteria using Given, When, and Then statements or equivalent observable checks.
5. Assign priority using Must, Should, Could, or Not in current release.
6. Identify dependencies, risks, and validation requirements.
7. Assign stable IDs such as US-001, US-002, and REQ-001 links when traceability is needed.

## Checks

- Stories describe outcomes, not implementation tasks.
- Acceptance criteria are testable by Tester.
- Dependencies and blocked decisions are explicit.
- Stories can be estimated and decomposed by Team Lead.
- Security, performance, DevOps, and architecture implications are called out when relevant.
