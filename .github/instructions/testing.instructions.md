---
description: "Use when adding or updating tests, validating a bug fix, planning regression coverage, considering fuzzing, or defining sanitizer-aware C++ validation."
---
# Testing Guidance

- Prefer fast unit tests first, then integration tests where boundaries matter.
- Cover happy path, edge cases, invalid inputs, and failure paths.
- Add regression coverage for every material bug fix.
- Consider fuzzing for parsers, protocol handlers, and untrusted input surfaces.
- Prefer deterministic, maintainable tests over brittle test scaffolding.
- When practical, include sanitizer-aware validation in the recommended test path.