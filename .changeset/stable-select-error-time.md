---
'@tanstack/query-core': patch
---

Keep `errorUpdatedAt` stable for a memoized `select` error, so a throwing inline `select` no longer causes an infinite render loop in React.
