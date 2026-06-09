---
"@chbrain/khai-plays-buechner": patch
---

Ship the play registry and give it English loglines.

`registry.json` is now included in the published package (added to `files`), so
the website reads curated play titles and descriptions from it instead of
falling back to parsing the German `## Arc` section. Every logline is rewritten
in English to match the English play titles and the English-only house blurb;
the German play bodies are untouched. The mirrored `khai.plays` block in
`package.json` is updated to agree.
