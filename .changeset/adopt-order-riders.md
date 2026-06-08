---
"@chbrain/khai-plays-buechner": patch
---

Adopt the khai-guard `riders` lane class (order_260608_1): declare
`management/orders/**` a rider with a `governance` fallback, so a management
order rides the lane of the change it drives (one PR, not two) and the temporary
`migration/*` lane is retired. Raises `@chbrain/khai-guard` and
`@chbrain/khai-arch` to `^0.1.9` and records the rule in `CLAUDE.md`.
