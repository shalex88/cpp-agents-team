---
description: "Use when designing modules, APIs, dependency direction, ownership models, lifecycle rules, or error-handling strategy for C++ changes."
---
# Architecture Guidance

- Design for clear module boundaries and acyclic dependencies.
- Keep interfaces narrow and stable.
- Separate public API from implementation details.
- Treat ownership, lifecycle, test seams, and build cost as design concerns.
- Prefer simple, explicit designs over framework-heavy or implicit structures.
- Flag performance-sensitive boundaries explicitly instead of assuming everything is hot.