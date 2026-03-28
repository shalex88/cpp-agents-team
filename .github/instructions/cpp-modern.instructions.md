---
description: "Use when writing, refactoring, or reviewing C++ source, headers, interfaces, ownership, lifetime, or error handling. Covers modern C++ defaults for production application code."
applyTo: "**/*.c, **/*.cc, **/*.cpp, **/*.cxx, **/*.h, **/*.hh, **/*.hpp, **/*.hxx, **/*.ipp, **/*.tpp"
---
# Modern C++ Guidance

- Default to C++20 unless constrained otherwise.
- Prefer RAII and value semantics where they keep ownership clear.
- Prefer `std::unique_ptr` for ownership; use `std::shared_ptr` only with explicit shared lifetime justification.
- Avoid raw `new` and `delete` in application code.
- Prefer `std::span`, `std::string_view`, and narrow type-safe interfaces where appropriate.
- Keep headers minimal and reduce compile-time coupling.
- Make invariants, ownership, and error-handling strategy explicit.
- Avoid undefined behavior, hidden ownership, and implicit lifetime coupling.
- Avoid micro-optimizations without measurement.