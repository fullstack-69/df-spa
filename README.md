# Data Fetching

This repository demonstrates different data-fetching strategies for React applications. Each strategy is implemented on its own Git branch.

To explore a strategy, switch to the corresponding branch:

```bash
git switch <branch-name>
```

## Strategies

Follow the branches in this order:

1. `useeffect` - Fetch data with React's `useEffect` hook.
2. `custom-hook` - Encapsulate fetching logic in a reusable custom hook.
3. `prop-drilling` - Pass fetched data through component props.
4. `zustand` - Manage fetched data with Zustand.
5. `jotai` - Manage fetched data with Jotai atoms.
6. `tanstack-query` - Fetch and cache server state with TanStack Query.
7. `sse` - Receive server updates with Server-Sent Events.
8. `websocket` - Receive real-time updates through WebSockets.

The current branch can be checked with:

```bash
git branch --show-current
```
