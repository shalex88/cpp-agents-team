# Build and CI policy

- Use target-based modern CMake.
- Keep dependencies explicit and reproducible.
- Enable strict warnings and fail on serious diagnostics.
- Run formatting, static analysis, tests, and sanitizer jobs in CI where feasible.
- Keep CI fast enough for regular use but strict enough to block bad changes.
- Prefer reproducible local and CI behavior.
