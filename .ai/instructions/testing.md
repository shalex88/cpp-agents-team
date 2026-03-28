# Testing policy

- Every feature requires tests appropriate to its risk profile.
- Prefer fast unit tests first, then integration tests where boundaries matter.
- Include edge cases, failure paths, invalid input paths, and regression coverage.
- Use sanitizers in validation flows where supported.
- Add fuzzing for parsers, protocol handlers, and untrusted input paths.
- Tests must be deterministic and maintainable.
