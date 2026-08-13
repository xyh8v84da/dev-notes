# React Hooks Tips

- Use `useCallback` for functions passed to memoized children.
- `useEffect` cleanup functions prevent memory leaks.
- Prefer `useReducer` for complex state logic.
- Custom hooks: extract reusable logic starting with `use`.
- `useMemo` only when computation is expensive.
- Keep dependency arrays exhaustive to avoid stale closures.
- Use `useRef` for mutable values that don't trigger re-renders.