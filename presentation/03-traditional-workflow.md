# The Old Way on a Real Feature

---

## [Previous](02-the-problem-wa902806.md) | [Home](README.md) | [Next](04-the-bug-that-broke-the-pattern.md)

---

## What I Implemented First

- Added `invalidRowIds` state
- Wired state through the prop chain
- Context -> ConfigureStep -> ConfigureStepForm -> ConfigureStepGrid

---

## Why This Feels Fine the First Time

- In-browser checks looked good
- Visual validation passed
- I shipped it

---

## Why It Gets Expensive Over Time

- The first implementation is not the hard part.
- The hard part is doing this again and again for every change.
- Every new edge case means more clicking, more tracing, more re-checking.

I was relying on memory and repetition instead of a repeatable specification.
