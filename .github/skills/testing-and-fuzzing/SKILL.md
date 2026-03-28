---
name: testing-and-fuzzing
description: 'Use when defining unit tests, integration tests, regression coverage, edge cases, fuzzing candidates, or sanitizer-aware validation for C++ changes.'
argument-hint: 'Describe the behavior or change that needs validation.'
user-invocable: true
---

# Testing and Fuzzing

Use this skill to plan or assess validation for C++ work.

## Cover

- Happy path behavior
- Edge cases
- Invalid inputs
- Failure paths
- Regression scenarios
- Fuzzing candidates for risky input surfaces
- Sanitizer-aware validation

## Procedure

1. Identify the public behavior and invariants that matter.
2. Define fast unit coverage first.
3. Add integration coverage where boundaries matter.
4. Add regression tests for material bugs.
5. Consider fuzzing for parsers, protocol handlers, and untrusted input paths.