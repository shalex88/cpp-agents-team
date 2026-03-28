---
name: ci-and-cmake
description: 'Use when updating CMake structure, compiler warning policy, CI pipelines, static analysis, sanitizer jobs, dependencies, or reproducible developer workflows.'
argument-hint: 'Describe the build, CI, or tooling problem to solve.'
user-invocable: true
---

# CI and CMake

Use this skill for build-system and pipeline work.

## Focus

- Target-based modern CMake
- Explicit dependencies
- Strict warnings
- Static analysis and tests
- Sanitizer jobs
- Reproducible local and CI workflows

## Procedure

1. Identify the target or pipeline stage that needs change.
2. Keep dependency flow explicit and reproducible.
3. Add quality gates that are justified and maintainable.
4. Align local reproduction steps with CI behavior.
5. Record rollout risks and validation expectations.