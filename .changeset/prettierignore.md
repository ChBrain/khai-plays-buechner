---
"@chbrain/khai-plays-buechner": patch
---

Add a `.prettierignore` for the machine-written audit artifacts. The audit
workflow commits `audit/*/log.md`, `ledger.json`, and `meta.json`; without an
ignore file, `prettier --check` (the `test` gate) fails the moment the audit bot
writes a non-trivial finding. Mirrors the khai monorepo and the house blueprint,
and registers `.prettierignore` as a shared path in `khai-guard.config.json`.
