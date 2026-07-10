# Inside Out vs Outside In

---

## [Previous](06a-frontend-unit-tests.md) | [Home](README.md) | [Next](08-red-green-refactor.md)

---

## Two Simple Ways to Start

| Approach | Start Here | Simple Description | Best When |
|---|---|---|---|
| Inside Out | Small rules first | Test the logic underneath, then wire the UI around it | The business rule is the risky part |
| Outside In | User flow first | Start from what the user does, then fake dependencies as needed | The end-to-end behavior is the risky part |

---

## Plain Example

Inside Out:
- A row with 2 missing required fields should be marked invalid.
- Fix the missing fields, and the row should clear.

Outside In:
- A user clicks Save.
- The screen should show which rows need attention.

---

## What I Used Here

Inside Out.

I started with the rule for when a row is invalid, then let the component wiring follow.

---

## Team-Friendly Framing

Do not treat this as ideology.
Treat both as tools.
Choose based on uncertainty, seams, and feedback needs.
