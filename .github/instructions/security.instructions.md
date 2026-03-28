---
description: "Use when handling untrusted input, parsing, integer conversions, bounds checks, memory ownership, file or network input, or secure coding review for C++ changes."
---
# Security Guidance

- Treat all external input as untrusted.
- Validate ranges, formats, allocation sizes, and invariants at boundaries.
- Review integer conversions, overflow risk, and bounds handling carefully.
- Prefer safe-by-default interfaces and explicit ownership.
- Minimize attack surface and avoid fragile parsing assumptions.
- Never expose secrets in code, logs, tests, or examples.