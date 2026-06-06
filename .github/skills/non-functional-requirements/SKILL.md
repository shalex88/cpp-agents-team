---
name: non-functional-requirements
description: 'Use when defining measurable product constraints for performance, reliability, security, maintainability, compatibility, operability, deployment, and support before architecture or implementation.'
argument-hint: 'Provide product scope, target environment, users, deployment context, and known constraints.'
user-invocable: true
---

# Non-Functional Requirements

Use this skill when a product or feature needs explicit quality attributes before engineering design starts.

## Produce

- Performance requirements
- Reliability and availability requirements
- Security and privacy requirements
- Maintainability requirements
- Compatibility and portability requirements
- Operability and observability requirements
- Deployment and rollback requirements
- Supportability requirements
- Constraints and assumptions

## Procedure

1. Identify quality attributes that matter for the product and release.
2. Express requirements as measurable targets where possible.
3. Record environment constraints such as CPU, memory, storage, network, OS, compiler, or target hardware.
4. Capture security, privacy, abuse, and data handling expectations.
5. Define observability expectations such as logs, metrics, traces, health checks, diagnostics, and alerting.
6. Define deployment expectations such as packaging, configuration, rollback, and upgrade behavior.
7. Mark any missing target as an explicit open question instead of leaving it implicit.

## Checks

- Performance targets are measurable.
- Reliability and recovery expectations are stated.
- Security and privacy expectations are visible to ReviewerSecurity.
- Operability expectations are visible to DevOps.
- Hardware, OS, compiler, and resource constraints are documented when relevant.
- Non-functional requirements can influence architecture before implementation begins.
