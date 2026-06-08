---
"@chbrain/khai-plays-buechner": patch
---

Adopt the upgraded khai canon (`khai-tests` 0.1.10 / `khai-rules` 0.1.5 and
peers): every non-English content file now carries a `declared` frontmatter key
holding its localized H1 name, while `title` becomes the English name used for
the registry. `registry.json` and `package.json#khai.plays` titles are now
English; descriptions stay in the production language. No play is added or
removed, so this is a patch.
