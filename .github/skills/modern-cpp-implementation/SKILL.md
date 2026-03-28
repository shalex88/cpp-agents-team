---
name: modern-cpp-implementation
description: 'Use when implementing or refactoring C++ code with modern ownership, RAII, const-correctness, focused functions, and clear invariants.'
argument-hint: 'Describe the feature, bug fix, or refactor to implement.'
user-invocable: true
---

# Modern C++ Implementation

Use this skill for code-level implementation work in the repository.

## Defaults

- Assume C++20 unless constrained otherwise.
- Prefer RAII and explicit ownership.
- Avoid raw `new` and `delete` in application code.
- Keep functions focused and interfaces clear.
- Avoid hidden lifetime coupling and undefined behavior.

## Procedure

1. Confirm the architectural intent and invariants.
2. Identify error paths, boundary conditions, and ownership transitions.
3. Implement the smallest coherent change.
4. Note obvious test impact and review concerns.
5. Avoid speculative performance changes unless there is evidence.