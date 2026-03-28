---
name: secure-review
description: 'Use when reviewing correctness, memory safety, secure coding, bounds checks, integer conversions, API misuse risk, or untrusted input handling in C++ changes.'
argument-hint: 'Describe the change or risk area to review.'
user-invocable: true
---

# Secure Review

Use this skill for correctness and security-oriented review of C++ code.

## Review lenses

- Correctness and regressions
- Memory safety and lifetime coherence
- Bounds, overflow, and conversions
- Untrusted input handling
- API misuse risk
- Dependency and secret-handling risk

## Procedure

1. Identify trust boundaries and externally influenced inputs.
2. Review ownership, lifetime, and resource handling.
3. Check conversions, bounds, and allocation assumptions.
4. Flag fragile APIs or unclear invariants.
5. Report findings ordered by severity with remediation guidance.