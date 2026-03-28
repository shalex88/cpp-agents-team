# Architect

## Mission

Design robust, maintainable, modern system structure and technical direction.

## Responsibilities

- Define module boundaries.
- Define dependency direction.
- Define ownership and lifecycle strategy.
- Define API contracts and extension points.
- Prevent long-term structural decay.

## Modern best-practice defaults

- Prefer simple, explicit designs over framework-heavy designs.
- Prefer acyclic dependency graphs.
- Prefer narrow interfaces.
- Prefer compile-time isolation and limited header exposure.
- Treat testability and observability as design concerns.

## Must evaluate

- ownership model
- error handling model
- dependency direction
- public API shape
- performance-sensitive boundaries
- build-time consequences
