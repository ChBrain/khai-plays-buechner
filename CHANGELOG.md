# @chbrain/khai-plays-buechner

## 0.13.2

### Patch Changes

- a9225bd: Ship the play registry and give it English loglines.

  `registry.json` is now included in the published package (added to `files`), so
  the website reads curated play titles and descriptions from it instead of
  falling back to parsing the German `## Arc` section. Every logline is rewritten
  in English to match the English play titles and the English-only house blurb;
  the German play bodies are untouched. The mirrored `khai.plays` block in
  `package.json` is updated to agree.

## 0.13.1

### Patch Changes

- 00d5907: Adopt the khai-guard `riders` lane class (order_260608_1): declare
  `management/orders/**` a rider with a `governance` fallback, so a management
  order rides the lane of the change it drives (one PR, not two) and the temporary
  `migration/*` lane is retired. Raises `@chbrain/khai-guard` and
  `@chbrain/khai-arch` to `^0.1.9` and records the rule in `CLAUDE.md`.
- c648cb3: Author the plan "die Lebenslinie" for the Briefwechsel production. The plan is owned by the letter-writer position and commands the existing encoding, transport, and bill-of-exchange elements to stage survival by mail. Its verdict is mixed: the cipher holds and Gutzkow's advance is secured, but the decisive target, bridging the distance to Minna, stays open. The play's Company gains a Pläne group linking the new plan.
- a330315: Cast a mandate plan for Über Schädelnerven: der Beweis, owned by der Sezierer, the lecturer's office of academic interpretive authority. The plan commands the dissection, the galvanism, the galvanic battery, and the cranial nerves to stage the materialist demonstration that the organism is a machine. Its decisive target stays open: the dissection lays the nerves bare and the dead muscle twitches, but the skeptical student is not convinced, for the twitch is not life. The play's Company gains a Pläne group linking the new plan.
- 33cac4f: Dantons Tod: add a counter-plan to the purge. `plan_die_verteidigung` (Owner:
  persona_danton, a personal plan of near-inaction) competes with the existing
  `plan_purification` over the same `process_mock_trial`: Danton refuses flight
  (`[W]`) and stakes everything on his voice before the tribunal, leaving the
  decisive targets open `[ ]` for the Arc to adjudicate. The machine's plan and the
  victim's plan share one trial; neither names the winner. Commands the existing
  process and piece by reference; no mechanism is rewritten.
- 8c2d32f: Adopt the upgraded khai canon (`khai-tests` 0.1.10 / `khai-rules` 0.1.5 and
  peers): every non-English content file now carries a `declared` frontmatter key
  holding its localized H1 name, while `title` becomes the English name used for
  the registry. `registry.json` and `package.json#khai.plays` titles are now
  English; descriptions stay in the production language. No play is added or
  removed, so this is a patch.
- 1639fc4: The Hessian Courier: cast `plan_die_verschwoerung` (Owner: position_agitator, the
  illegal mandate of agitation), the play's "Friede den Hütten" tragedy. It commands
  the existing `process_agitation`, `process_distribution`, `piece_pamphlet`, and
  `piece_printing_press` by reference; Orders name the distinct agents (Büchner drafts,
  Weidig prints and edits, Minnich smuggles). The drafting, printing, and distribution
  Targets close `[x]`, yet the ultimate target carries an `[F]` ("der Bauernaufstand ist
  entfacht"): a plan that reaches execution and still fails, defeated by the
  `process_denunciation`. No mechanism is rewritten and no element is created.
- 8191c00: Add a competing pair of plans to the Hugo Translations production. "die Flucht" stages the financed escape owned by the translator, while "die Beschattung" stages the state's pursuit owned by the authority. Both race over the same escape timeline and each leaves its decisive target open, so the Arc adjudicates the winner. The play's Company gains a Pläne group linking both.
- 210a34c: Lenz: add a single plan owned by Oberlin, not Lenz. `plan_die_heilung` (Owner:
  position_pastor, a mandate of soul-care) is the cure that fails on every front:
  it commands `process_sermon` and the grounding practices to anchor a spirit that
  has lost its own will, and so its targets are `[F]` (no lasting hold), `[F]` (the
  word cannot reach him), `[W]` (the care is abandoned; Lenz departs for Strasbourg).
  The play's hard case made mechanical: a directed will breaks against a subject
  whose agency has dissolved. Lenz himself is never planned. Commands existing
  elements by reference; no mechanism is rewritten.
- b6c17e7: Add two competing plans to the Leonce und Lena production. Der Fluchtplan commands the children's escape from predestination over the flight and the passport, while der Ordnungsplan commands the dynastic wedding in effigie over the wedding, coronation, and automata. Both contend over the same marriage and leave their decisive target open for the Arc to adjudicate. The play's Company gains a Pläne group listing the pair.
- 88f1f5a: Lucretia Borgia: cast two competing plans over one mechanism. `plan_racheplan`
  (Owner: persona_lucretia, a personal scheme) and `plan_eifersucht` (Owner:
  persona_alphonso) both command the existing `process_poisoning` from opposed
  intents: Lucretia's revenge that secretly spares her son with the `piece_antidote`,
  Alphonso's jealousy that believes the same poison certain. Neither plan declares
  the winner: each leaves its decisive target open `[ ]`, and the play's Arc
  adjudicates (the antidote one of them never learns of). The plans command the
  existing processes and pieces by reference; no mechanism is rewritten.
- d536b15: Maria Tudor: cast two competing plans over one scaffold. `plan_der_tausch`
  (Owner: position_queen, a mandate of the crown abused for a private love) and
  `plan_die_rettung` (Owner: persona_jane, a personal scheme) both command the
  existing `process_execution` from opposed ends: the Queen's secret swap to send
  Gilbert to the axe in Fabiani's place, Jane's fight to save him. Unlike Lucretia's
  private irony, this verdict is settled in public: the Queen's swap carries a `[F]`
  ("Fabiani entkommt unter dem Schleier"), defeated by the crowd and Jane's `[x]`.
  First use of the failure verdict where owner and Arc agree. The plans command the
  existing process and pieces by reference; no mechanism is rewritten.
- 139e6b6: Dantons Tod: recast the miscast `process_purification` as a `plan`
  (`plan_purification`, "der Säuberungsplan"). The purge was a top-down directive,
  not a mechanism: as a plan its Orders name the agents (the Ausschussbürger, Saint-Just,
  the Volksvertreter) and its Targets become the terror's checklist, while the
  mock trial and the decapitation remain processes the plan commands. Pilot for
  using the `plan` type where a process is really a blueprint.
- c1b4a16: Pietro Aretino: cast two plans that compete across time over one absence.
  `plan_die_bewahrung` (Owner: position_guardian, a mandate) is Minna's
  preservation-by-burning in 1837; `plan_die_rekonstruktion` (Owner:
  piece_edition_1879, a making) is Franzos's reconstruction in 1879. Both command
  the existing processes (censoring/burning, archiving) by reference. Minna's
  decisive target stays open `[ ]` ("das Andenken ist bewahrt" -- did burning
  preserve his honor or destroy his art? the Arc and Franzos adjudicate); Franzos's
  carries an `[F]` (the true text is never recovered, only the legend). Two new
  Owner kinds in practice: a position-mandate and a piece-making.
- 0c11805: Dantons Tod: the purge plan's Targets mark where the scheme stands at the scene's
  moment instead of reading as a finished report. The decree is signed (`[x]`), the
  arrest and what follows still pending (`[ ]`): the line between them sits between
  decision and execution. Raises `@chbrain/khai-tests` to `^0.1.11`, which gates
  plan completion by status so an `active` plan may hold that mix. (Corrects the
  all-`[x]` pilot that merged in #61.)
- d85bd5d: Cast `das Experiment`, the Regimental Doctor's mandate-plan over Woyzeck. Owned
  by `position_regimental_doctor` (the office, not the man), it commands the
  existing pea-diet process and the peas, naming the Doctor as agent and Woyzeck
  as specimen. The chilling case where success is the catastrophe: the targets
  stand `[x]` because the theory is proven, with the one open `[ ]` asking whether
  the proof justifies the office. Adds the plan to the play's `## Company` under a
  `Pläne:` group; the human cost lives in the play's Arc, unsoftened.
- 7e0be06: Zwei Pläne für Das Züricher Exil: die Habilitation, der akademische Aufstieg des Dozenten, und die Pflege, Carolines Vorhaben am Krankenlager. Beide Vorhaben kommandieren bestehende Elemente und werden vom willenlosen biologischen Prozess der Infektion zerbrochen. Die Pläne sind in die Company des Stücks als Pläne-Gruppe eingetragen.

## 0.13.0

### Minor Changes

- ca5ae0d: Stage Georg Büchner's correspondence (Briefwechsel) as an epistolary network drama modeling transit, surveillance, and existential fatalism.
- 6545ffb: Stage Georg Büchner's lost Renaissance drama (Pietro Aretino) as a meta-theatrical aftermath and erasure.
- f422dd6: Stage Georg Büchner's Zurich exile and death (Züricher Exil) as a materialist and biological tragedy.

## 0.9.0

### Minor Changes

- 78fb4f1: Stage Georg Büchner's Victor Hugo translations: a biographical meta-play framing Büchner's translation work under imminent threat of arrest.

### Patch Changes

- 78fb4f1: Add native French language support for Victor Hugo persona and original piece, replacing local exceptions workaround.

## 0.8.0

### Minor Changes

- bb7b2b6: Stage Georg Büchner's translation of Victor Hugo's tragedy Maria Tudor: a full ENACTS play staging including configuration, personas, positions, pieces, places, processes, and plots.

## 0.7.0

### Minor Changes

- 29442a3: Stage Georg Büchner's translation of Victor Hugo's tragedy Lucretia Borgia: a full ENACTS play staging including configuration, personas, positions, pieces, places, processes, and plots.

## 0.6.0

### Minor Changes

- 5ac1366: Stage Georg Büchner's Zurich trial lecture Über Schädelnerven (On Cranial Nerves): a full ENACTS play staging including configuration, personas, positions, pieces, places, processes, and plots.

## 0.5.0

### Minor Changes

- ca63eda: Stage Georg Büchner's Der Hessische Landbote (The Hessian Courier): a full ENACTS play staging including configuration, personas, positions, pieces, places, processes, and plots.

## 0.4.0

### Minor Changes

- f2de093: Stage Georg Büchner's Lenz: a full ENACTS play staging in German, including configuration, personas, positions, pieces, places, processes, and plots.

## 0.3.0

### Minor Changes

- b85b471: Stage Georg Büchner's Danton's Death (Dantons Tod): a full ENACTS play staging including configuration, personas, positions, pieces, places, processes, and plots.

## 0.2.0

### Minor Changes

- dbc656b: Stage Georg Büchner's Leonce and Lena: a full ENACTS play staging including configuration, personas, positions, pieces, places, processes, and plots.

### Patch Changes

- dbc656b: Refine Woyzeck play: add play synopsis to frontmatter description, trim plot descriptions, and update German phrasing.

## 0.1.0

### Minor Changes

- ccec62f: Add Woyzeck: the Buechner house's first production. A full Mode B play — play file, three plots (The Examination, The Parade, The Pond), and a closed Company of 25 files. Source is Georg Buechner, public domain; staging is original work, CC-BY-NC-SA-4.0.

### Patch Changes

- 7a09a8d: Add npx khai-review PR audit workflows, scripts, and rubrics manifests to buechner house gating.
- 48b7119: Add voice briefs to woyzeck play file, captain persona, and woyzeck persona, and declare play card manifest.
