# Honest Tradeoffs

---

## [Previous](13-tdd-vs-traditional.md) | [Home](README.md) | [Next](14a-workflow-test-bootstrap.md)

---

## What TDD Costs

- More code to write and maintain
- Test setup overhead is real
- Tooling gotchas can slow momentum
- Superficial tests create false confidence
- Ambiguous UX requirements still need discovery work

---

## Simple Example from This Story

Vitest + `vi.mock()` + import order produced a hoisting/transform issue.

That friction is part of the practice and must be budgeted in delivery planning.

---

## Balanced View

TDD is not a silver bullet.
It is a discipline that trades upfront effort for lower uncertainty during change.

It works best when the team treats tests as part of delivery, not as optional cleanup.
