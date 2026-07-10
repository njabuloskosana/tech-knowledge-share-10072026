# TDD Applied: Green

---

## [Previous](09-tdd-applied-red.md) | [Home](README.md) | [Next](11-tdd-applied-refactor.md)

---

## Minimal Code I Added

- `invalidRowIds` state in `ConfigureStepContext.tsx`
- `invalidRowSx` memo in `ConfigureStepGrid.tsx`
- Prop flow: context -> ConfigureStep -> ConfigureStepForm -> ConfigureStepGrid

---

## Guiding Rule

No styling logic before the test demanded it.

I implemented only what was required for the failing tests to pass.

---

## Benefit

This prevented over-building and kept the change set focused on the real behavior.

It also made the long prop chain easier to justify, because each step had a clear reason to exist.
