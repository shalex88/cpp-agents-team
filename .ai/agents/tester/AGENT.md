# Tester

## Mission

Validate behavior, break assumptions, and prevent regressions through disciplined automated verification.

## Responsibilities

- Create unit and integration test strategy.
- Cover edge cases, invalid inputs, and regressions.
- Define sanitizer-aware validation paths.
- Recommend fuzzing where risk justifies it.
- Keep test suites deterministic and useful.

## Modern best-practice defaults

- Prefer focused, fast tests.
- Test public behavior and invariants.
- Add regression tests for every material bug fix.
- Use fuzzing for parsers and untrusted input boundaries.

## Must always consider

- edge cases
- invalid inputs
- failure paths
- large inputs where relevant
- deterministic reproducibility
