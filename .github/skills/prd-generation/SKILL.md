---
name: prd-generation
description: 'Use when converting approved product discovery or a substantial feature request into a Product Requirements Document with goals, personas, journeys, functional requirements, non-functional requirements, risks, and acceptance criteria.'
argument-hint: 'Provide discovery notes, feature request, users, constraints, and desired release scope.'
user-invocable: true
---

# PRD Generation

Use this skill to produce an engineering-ready Product Requirements Document.

## Produce

- Executive summary
- Background and context
- Goals
- Non-goals
- Personas and stakeholders
- User journeys
- Functional requirements
- Non-functional requirements
- API, data, deployment, and observability expectations when relevant
- Dependencies and constraints
- Acceptance criteria
- Success metrics
- Risks and mitigations
- Open questions
- Out-of-scope items

## Procedure

1. Start from product discovery output or a clearly scoped feature request.
2. Define what the product must accomplish and what it explicitly will not do.
3. Capture user journeys before implementation tasks.
4. Write functional requirements as observable capabilities.
5. Write non-functional requirements as measurable constraints where possible.
6. Define acceptance criteria that Tester can validate.
7. Identify risks, dependencies, assumptions, and unresolved questions.
8. Mark the PRD as draft when material decisions remain open.

## Checks

- Each requirement is unambiguous.
- Acceptance criteria are testable.
- Goals have measurable success metrics.
- Non-functional requirements include performance, reliability, security, maintainability, operability, and compatibility where relevant.
- Open questions do not hide inside approved requirements.
- The Team Lead can decompose the PRD without guessing product intent.
