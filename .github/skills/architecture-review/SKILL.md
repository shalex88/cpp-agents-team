---
name: architecture-review
description: 'Use when designing or reviewing module boundaries, APIs, dependency direction, ownership models, lifecycle rules, or error-handling strategy for C++ changes.'
argument-hint: 'Describe the design problem, affected modules, and constraints.'
user-invocable: true
---

# Architecture Review

Use this skill when structural decisions need to be made or reviewed.

## Focus areas

- Module responsibilities
- Dependency direction and acyclic design
- Public API shape
- Ownership and lifetime
- Error-handling strategy
- Test seams and build impact

## Procedure

1. Identify affected modules and their current responsibilities.
2. Propose narrow interfaces and intentional dependency direction.
3. Make lifecycle, ownership, and error behavior explicit.
4. Evaluate testability and compile-time consequences.
5. Record tradeoffs, risks, and migration notes.