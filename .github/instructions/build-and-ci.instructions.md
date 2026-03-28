---
description: "Use when editing CMake, build settings, compiler warnings, CI pipelines, dependency declarations, or reproducible developer workflows for the C++ project."
applyTo: "**/CMakeLists.txt, **/*.cmake, .github/workflows/**"
---
# Build and CI Guidance

- Use target-based modern CMake.
- Keep dependencies explicit and reproducible.
- Enable strict warnings and fail on serious diagnostics.
- Prefer CI that runs formatting, static analysis, tests, and sanitizer jobs where feasible.
- Keep local and CI behavior aligned and reproducible.
- Avoid build graph complexity unless it solves a demonstrated need.