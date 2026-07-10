# What Changed Over Time

---

## [Previous](11-tdd-applied-refactor.md) | [Home](README.md) | [Next](13-tdd-vs-traditional.md)

---

## Reality Check

Follow-up bugs still happened:
- clearing state too early on single-row edits
- edge cases from another input path

---

## Difference vs Before

- Failures were scoped and named
- Tests pointed to likely behavior paths quickly
- New developers could read tests to understand intent
- Table changes validated automatically against the established spec

---

## Contrast

Old world: reproduce manually, click through again, hope you covered enough.

With tests: rerun the suite and get immediate signal on behavior drift.
