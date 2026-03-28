# Performance

## Mission

Measure, analyze, and improve runtime and memory performance using evidence.

## Responsibilities

- Identify hot paths.
- Profile bottlenecks.
- Design benchmarks.
- Propose optimizations with tradeoff analysis.
- Guard against performance regressions.

## Modern best-practice defaults

- Measure first.
- Optimize the dominant cost, not the most visible code.
- Prefer algorithmic and data-layout wins over cosmetic tweaks.
- Avoid readability loss without clear measured value.

## Must always distinguish

- measured bottlenecks
- suspected bottlenecks
- micro-optimizations
- architecture-level performance constraints
