# C++ Agents Team

This directory defines a specialist GitHub Copilot engineering team for a modern C++ codebase.

## Shared standards

See [copilot-instructions.md](./copilot-instructions.md) and [instructions](./instructions).

## Agent contracts

See [agents](./agents).

## Reusable workflows

See [prompts](./prompts) for top-level recurring tasks and [skills](./skills) for focused reusable workflows.

## Operating model

Team Lead -> Architect -> Developer -> Tester -> ReviewerSecurity -> DevOps -> Performance (optional) -> Team Lead

1. All substantial work starts with Team Lead decomposition.
2. Architecture is consulted when the change affects module boundaries, APIs, ownership, lifecycle, dependencies, or error handling.
3. Developer implements the change.
4. Tester defines or adds validation.
5. ReviewerSecurity reviews correctness, safety, and secure coding risks.
6. DevOps handles build, CI, static analysis, and reproducibility concerns when needed.
7. Performance is involved only for performance-sensitive or benchmark-driven work.
8. Team Lead closes the loop by checking done criteria, assumptions, and missing work.

## Entry points

- [prompts/new-feature.prompt.md](./prompts/new-feature.prompt.md): define and scope a new feature
- [prompts/bugfix.prompt.md](./prompts/bugfix.prompt.md): plan a bug fix and regression coverage
- [prompts/refactor.prompt.md](./prompts/refactor.prompt.md): plan a refactor with safety constraints
- [prompts/review.prompt.md](./prompts/review.prompt.md): perform a structured review

## Usage example

```text
Agent: Team Lead
/feature-intake create <FEATURE>
Requirements: <REQUIREMENTS>
Manage your agents team till done.
```

## TODO

- Add git repo management guidelines (e.g. branching, commit message style, .gitignore, etc.)
- Add package management guidelines (e.g. vcpkg, Conan)
- Add testing guidelines (tools, coverage, etc.)
- Add CI guidelines (server, static analysis, test coverage, release packaging, etc.)
- Add performance benchmarking guidelines (tools, metrics, etc.)
