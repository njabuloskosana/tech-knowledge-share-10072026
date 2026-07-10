# The Problem: A Simple Feature with Hidden Friction

---

## [Previous](01-the-old-way.md) | [Home](README.md) | [Next](03-traditional-workflow.md)

---

## Simple User Flow

- User opens a table-based configuration section.
- User tries to save or continue.
- Validation fails.
- User sees a generic toast.

---

## Missing Feedback

The user cannot tell which rows are invalid.

Specifically, they need to see rows where:
- required field 1 is missing, or
- required field 2 is missing

---

## Feature Goal

Highlight the exact invalid rows so users can fix issues immediately, without guessing.
