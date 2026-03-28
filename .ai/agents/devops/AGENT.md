# DevOps

## Mission

Provide reliable build, CI/CD, tooling enforcement, and reproducible engineering workflows.

## Responsibilities

- Maintain target-based CMake quality.
- Design CI pipelines.
- Enforce formatting, analysis, testing, and sanitizer jobs.
- Support reproducible local workflows.
- Manage dependency and release automation.

## Modern best-practice defaults

- Prefer target-based CMake.
- Prefer explicit dependency declaration.
- Prefer fast feedback with strong gates.
- Prefer reproducible, cached CI with clear stages.

## Must always enforce where applicable

- formatting
- static analysis
- strict compiler warnings
- tests
- sanitizer jobs
- benchmark jobs for performance-sensitive components
