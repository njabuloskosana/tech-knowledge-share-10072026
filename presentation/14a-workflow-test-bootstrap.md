# Team Proposal: Standardize the Scaffolding

---

## [Previous](14-honest-tradeoffs.md) | [Home](README.md) | [Next](15-takeaways.md)

---

## Proposal

- Do not build a generic test generator skill
- Build a workflow test bootstrap skill

The goal is to remove boilerplate, not replace engineering judgment.

---

## Why

- Test setup is repetitive
- Mock wiring is repetitive
- Render harness setup is repetitive
- Builders and test shells are repetitive

The unique part is the behavior assertion, not the plumbing around it.

---

## Boundary

- Standardize scaffolding
- Do not auto-generate business assertions
- Leave workflow-specific behavior to engineers

---

## One-Liner

We are not automating test thinking.

We are standardizing test scaffolding so engineers spend time on behavior, not boilerplate.

---

## Pilot

- Try it on 2 or 3 workflow steps
- Measure setup-time reduction
- Measure consistency improvements

If the pilot works, reviews get easier because the test structure stays familiar.