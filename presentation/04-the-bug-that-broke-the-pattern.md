# The Bug That Broke My Pattern

---

## [Previous](03-traditional-workflow.md) | [Home](README.md) | [Next](05-lightbulb-moment.md)

---

## What Broke

After the table refreshed, the highlighted rows were no longer highlighted.

Environment:
- MUI DataGrid Pro v8
- Virtualized rows
- The data was still there, but the visual warning was gone

---

## Why It Was Hard to Debug

- Was the state resetting?
- Was a prop not updating?
- Was the grid re-rendering differently?
- Was my styling hook attached to the wrong part of the grid lifecycle?

---

## Real Cost

- I retraced the whole flow manually
- I re-ran browser clicks repeatedly
- I had no reproducible test to prove stability

The only way I could confirm the fix was to click through it again.
