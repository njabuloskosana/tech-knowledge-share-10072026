# TDD Applied: Red

---

## [Previous](08-red-green-refactor.md) | [Home](README.md) | [Next](10-tdd-applied-green.md)

---

## What I Wrote Before Feature Code

In `ConfigureStepContext.test.tsx`:

- should track invalid rows when 2 required fields are missing
- should clear invalid rows after the missing values are fixed and validation passes

In `ConfigureStepGrid.test.tsx`:

- passes invalid row styling selectors through sx when invalidRowIds change
- verifies selectors clear again when invalidRowIds becomes empty

---

## Short Excerpt Pattern

```tsx
it('should track invalid active rows when values are missing', async () => {
  // arrange scenario with 2 missing required fields
  // trigger validation
  // expect invalidRowIds to contain impacted row ids
})
```

```tsx
it('passes invalid row styling selectors through sx', async () => {
  // set invalidRowIds
  // expect sx to include row data-id selectors
})
```

---

## Why This Mattered

Before touching implementation, I had locked behavior in executable terms.

This is the level we want to get fast at: frontend unit tests that define behavior before the component wiring grows.
