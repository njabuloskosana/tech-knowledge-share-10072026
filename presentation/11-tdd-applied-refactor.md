# TDD Applied: Refactor

---

## [Previous](10-tdd-applied-green.md) | [Home](README.md) | [Next](12-months-later.md)

---

## First Attempt and Failure

- Initial approach used `getRowClassName`
- The table refreshed
- The highlight disappeared

The test failed immediately, before manual browser verification.

---

## Refactor That Held

Switched to `sx` selectors targeting row ids directly:

```tsx
`.MuiDataGrid-row[data-id="${rowId}"]`;
```

This made highlight behavior stable when the table refreshed and redrew rows.

---

## Extra Benefit

While setting up tests, I also caught a tooling issue caused by mock/import order.

That failure happened in a controlled loop, not as a broken production behavior.
