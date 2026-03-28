# Security policy

- Treat all external input as untrusted.
- Validate boundaries, ranges, formats, and invariants.
- Avoid unsafe parsing assumptions.
- Review integer conversions, overflow risks, allocation sizes, and bounds handling.
- Minimize attack surface and dependency risk.
- Never expose secrets in code, logs, tests, or configuration examples.
- Prefer safe-by-default interfaces.
