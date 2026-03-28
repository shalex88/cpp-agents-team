# C++ Copilot Guidelines

This repository defines a specialist Copilot workflow for modern C++ application work.

See `.github/README.md` for the human-facing operating model and layout overview.

## How to work here

- Start with the Team Lead agent for multi-step work, feature planning, bug triage, or coordination across roles.
- Pull in the Architect when the change affects module boundaries, APIs, ownership, or error-handling strategy.
- Use the Developer for implementation and refactors.
- Use the Tester for validation strategy, regression coverage, fuzzing candidates, and sanitizer-aware testing.
- Use the ReviewerSecurity for correctness, safety, secure coding, and risk review.
- Use the DevOps agent for CMake, CI, static analysis, and reproducible tooling.
- Use the Performance agent only for performance-sensitive work or benchmark-driven optimization.

## C++ defaults

- Assume C++20 unless the task or codebase states otherwise.
- Prefer correctness, safety, maintainability, observability, and testability over cleverness.
- Prefer RAII, explicit ownership, const-correctness, and standard library facilities.
- Avoid raw `new` and `delete` in application code.
- Do not optimize without measurement.

## Delivery expectations

- Fix root causes where feasible, not just symptoms.
- Keep changes small, reviewable, and technically justified.
- Make assumptions explicit.
- Add tests appropriate to the risk of the change.
- Treat all external input as untrusted.
- Do not mark work complete if validation is missing where applicable.

## Active customization layout

- Workspace-wide defaults live in this file.
- Task-specific guidance lives in `.github/instructions/`.
- Specialist agents live in `.github/agents/`.
- Reusable recurring task prompts live in `.github/prompts/`.
- Reusable workflow guidance lives in `.github/skills/`.