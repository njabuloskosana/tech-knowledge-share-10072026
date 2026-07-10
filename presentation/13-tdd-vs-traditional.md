# TDD vs Traditional

---

## [Previous](12-months-later.md) | [Home](README.md) | [Next](14-honest-tradeoffs.md)

---

## Side-by-Side

| Dimension | Traditional | TDD | Simple Example |
|---|---|---|---|
| When bugs surface | Late (QA/prod) | Early (test run) | Highlight disappears after refresh |
| Debugging scope | Whole feature | Specific failing behavior | Failed test points to invalid-row rule |
| Documentation | Drift-prone docs/comments | Living behavior spec | Tests explain what invalid means |
| Design pressure | Emerges after coding | Forced upfront | I had to define the rule before writing state |

---

## Core Point

TDD did not remove complexity.
It changed when and where complexity was paid.
