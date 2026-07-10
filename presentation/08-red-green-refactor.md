# Red-Green-Refactor as a Design Loop

---

## [Previous](07-inside-out-vs-outside-in.md) | [Home](README.md) | [Next](09-tdd-applied-red.md)

---

## Red

- Define expected behavior first
- Force precision: what exactly should happen?
- Expose unclear requirements early

---

## Green

- Implement the smallest change that passes
- Resist architecture speculation
- Avoid solving future problems prematurely

---

## Refactor

- Improve structure and readability
- Keep behavior fixed behind tests
- Move faster safely because the spec is executable

Key insight: TDD produces tests, but its real output is better design decisions under constraints.

---

## Simple Example

- Red: a row with 2 missing fields should be highlighted
- Green: add only the logic needed to highlight that row
- Refactor: simplify the code without changing the result
