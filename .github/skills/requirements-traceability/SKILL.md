---
name: requirements-traceability
description: 'Use when requirements must be linked to stories, architecture decisions, implementation tasks, tests, risks, and release evidence.'
argument-hint: 'Provide PRD requirements, stories, design notes, test plan, and release evidence when available.'
user-invocable: true
---

# Requirements Traceability

Use this skill for product-facing, safety-sensitive, compliance-sensitive, or complex work where requirements must remain connected through delivery.

## Produce

- Stable requirement IDs
- Requirement-to-story mapping
- Requirement-to-design mapping
- Requirement-to-test mapping
- Requirement-to-risk mapping
- Release evidence mapping
- Coverage gaps

## Procedure

1. Assign stable IDs to product requirements, such as REQ-001, REQ-002, and NFR-001.
2. Link each requirement to user stories or engineering tasks.
3. Link each requirement to architecture notes, ADRs, API contracts, or data models when applicable.
4. Link each requirement to test cases, validation strategy, or acceptance criteria.
5. Link each requirement to risks and mitigations when relevant.
6. Identify requirements that lack implementation, validation, design, or release evidence.
7. Keep open questions separate from approved requirements.

## Traceability table

| Requirement | Story or task | Design artifact | Test artifact | Risk or release evidence | Status |
| --- | --- | --- | --- | --- | --- |
| REQ-001 | US-001 | ADR-001 | TC-001 | RISK-001 | Draft |

## Checks

- Every approved requirement has an owner or downstream artifact.
- Every Must-have requirement has validation coverage.
- Non-functional requirements are traced, not treated as notes.
- Gaps are explicit and actionable.
- Traceability does not create fake evidence; unknown links remain marked as missing.
