---
name: "Review"
description: "Use when reviewing a C++ change for correctness, security, memory safety, maintainability, test gaps, and performance sanity."
argument-hint: "Describe the change, PR, or files to review."
agent: "ReviewerSecurity"
---
Review the requested change with a code-review mindset.

Output requirements:
- Present findings first, ordered by severity.
- Focus on bugs, regressions, lifetime issues, secure coding, test gaps, and maintainability risks.
- Include concrete remediation guidance.
- If no findings exist, say so explicitly and mention residual risks or validation gaps.

Keep summaries brief and secondary to the findings.