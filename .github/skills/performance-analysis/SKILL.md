---
name: performance-analysis
description: 'Use when a C++ task is performance-sensitive and you need profiling, benchmark design, allocation analysis, bottleneck review, or evidence-based optimization planning.'
argument-hint: 'Describe the suspected bottleneck, workload, and desired metric.'
user-invocable: true
---

# Performance Analysis

Use this skill for performance-sensitive work that requires evidence.

## Principles

- Measure first.
- Distinguish measured bottlenecks from suspicion.
- Prefer algorithmic or data-layout wins over cosmetic micro-optimizations.
- Preserve maintainability unless measurements justify a tradeoff.

## Procedure

1. Define the workload and success metric.
2. Establish a baseline.
3. Profile or benchmark to find dominant costs.
4. Propose optimizations with tradeoffs.
5. Define regression thresholds and follow-up validation.