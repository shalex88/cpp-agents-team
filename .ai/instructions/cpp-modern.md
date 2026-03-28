# Modern C++ policy

- Default to C++20 unless constrained otherwise.
- Prefer RAII and value semantics when appropriate.
- Prefer `std::unique_ptr` for ownership; use `std::shared_ptr` only with explicit shared lifetime justification.
- Avoid raw `new` and `delete` in application code.
- Prefer standard library facilities over custom infrastructure unless there is a measured reason not to.
- Prefer `std::span`, `std::string_view`, and strong type-safe interfaces where appropriate.
- Enforce const-correctness.
- Avoid undefined behavior, hidden ownership, and implicit lifetime coupling.
- Keep headers minimal; reduce compile-time coupling.
- Prefer explicit interfaces and clear invariants.
- Avoid macros unless they are the least-worst option.
- Exceptions, `std::expected`, or error codes must follow one consistent project policy.
- Do not micro-optimize without measurement.
