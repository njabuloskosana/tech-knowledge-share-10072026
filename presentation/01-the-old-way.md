# The Old Way (How I Used To Work)

---

## [Previous](00-title.md) | [Home](README.md) | [Next](02-the-problem-wa902806.md)

---

## My Default Workflow

1. Get the ticket and understand the requirement.
2. Gather context from the existing code.
3. Implement the feature.
4. Open the browser.
5. Click through manually.
6. Check that the main flow works.
7. Re-test a few regression paths by hand.
8. Ship.

---

## Why It Felt Fine

- Fast at the start
- Low setup cost
- Gives instant visual feedback

---

## Where It Breaks

- Behaviors drift between edge cases: a feature works for the happy path, but breaks when a user edits, refreshes, or retries
- Debugging scope gets wide fast: one bug sends you across multiple files, components, and state layers before you even know where it started
- Regressions hide in manual paths you did not retest: the main flow still looks fine, but a less common path quietly breaks after a later change

No shame in this workflow. It works until complexity compounds.
