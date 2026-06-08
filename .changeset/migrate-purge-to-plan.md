---
"@chbrain/khai-plays-buechner": patch
---

Dantons Tod: recast the miscast `process_purification` as a `plan`
(`plan_purification`, "der Säuberungsplan"). The purge was a top-down directive,
not a mechanism: as a plan its Orders name the agents (the Ausschussbürger,
Saint-Just, the Volksvertreter), while the mock trial and the decapitation
remain processes the plan commands. The plan is `status: active`, and its Targets
mark where the scheme stands at the scene's moment: the decree is signed (`[x]`),
the arrest still pending (`[ ]`). The line between `[x]` and `[ ]` is where the
scene sits, between decision and execution. Requires `@chbrain/khai-tests@^0.1.11`,
which gates plan completion by status so an active plan may hold that mix.
