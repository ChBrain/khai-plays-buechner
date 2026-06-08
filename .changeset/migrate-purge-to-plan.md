---
"@chbrain/khai-plays-buechner": patch
---

Dantons Tod: recast the miscast `process_purification` as a `plan`
(`plan_purification`, "der Säuberungsplan"). The purge was a top-down directive,
not a mechanism: as a plan its Orders name the agents (the Ausschussbürger,
Saint-Just, the Volksvertreter) and its Targets are the terror's aims, while the
mock trial and the decapitation remain processes the plan commands. The plan is
`status: active` with open `[ ]` targets: an in-world plan holds its targets as
forward intent, not as a finished report. Requires `@chbrain/khai-tests@^0.1.11`,
which gates plan completion by status.
