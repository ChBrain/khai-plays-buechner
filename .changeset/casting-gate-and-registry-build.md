---
"@chbrain/khai-plays-buechner": patch
---

Adopt the casting gate: bump `@chbrain/khai-tests` to `^0.1.19` (whose canon
check reds any plot that casts no Company element) and wire `khai-tests registry
build` into the `version` script so each release heals `registry.json` from
source. Rebuild the registry, syncing its version to the play count and its
descriptions to the play arcs.
