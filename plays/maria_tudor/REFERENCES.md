---
updated: "2026-06-07"
---

# Maria Tudor: Reference

## Line of Work

Georg Büchner's 1835 translation of Victor Hugo's tragedy _Marie Tudor_ as **a study of absolute power, personal betrayal, and the scaffold**. The play stages the Tudor court where Queen Mary I of England is torn between her passionate love for the foreign adventurer Fabiano Fabiani and her sovereign duty to her people and the state. The domain models this as a closed system of royal favor, citizen honor, and execution machinery.

## Origin

The romantic prose drama _Marie Tudor_ written by Victor Hugo, first performed in Paris in November 1833. Georg Büchner translated the play in Strasbourg and Darmstadt in the spring of 1835, selling the translation to publisher Heinrich Remigius Sauerländer to secure funds for his flight to Strasbourg.

| Source            | Key Work / Event          | Scope                                                                                                                                |
| :---------------- | :------------------------ | :----------------------------------------------------------------------------------------------------------------------------------- |
| **Victor Hugo**   | _Marie Tudor_ (1833)      | The original French prose drama depicting the conflict of Queen Mary I and Fabiano Fabiani.                                          |
| **Georg Büchner** | German Translation (1835) | The translation of Hugo's work, rendered in expressive German prose, reflecting the fatalism and intensity of the romantic original. |

## Restrictions

What the production refuses to model, and to whom it delegates.

- **Historical English politics**: The production refuses to model the complex religious (Protestant vs. Catholic) and international politics of Mary Tudor's reign, focusing strictly on the courtly melodrama of favor and betrayal.
- **Dynastic marriage**: The production refuses to model the Queen's historical marriage negotiations with Philip II of Spain, keeping the focus on her obsession with Fabiani.
- **Redemptive justice**: The play refuses to offer a happy resolution. The machinery of the Tower and the executioner's axe are physical realities that cannot be bypassed.

## Encoding

Source to constraint, per file.

- **[play_maria_tudor.md](play_maria_tudor.md)**: The root playbook defining the company, triggers, and four-phase plot.
- **the queen ([Maria](persona_maria.md), [queen](position_queen.md))**: The sovereign whose emotional desires conflict with her absolute political authority.
- **the favorite ([Fabiani](persona_fabiani.md), [favored](position_favored.md))**: The Italian climber who seduces the Queen and the orphan, driving the betrayal.
- **the citizen ([Gilbert](persona_gilbert.md), [citizen](position_citizen.md))**: The honest Londoner who seeks justice and becomes a political target.
- **the orphan ([Jane](persona_jane.md), [orphan](position_orphan.md))**: The vulnerable victim whose secret lineage is used as a pawn.
- **the catalysts ([axe](piece_execution_axe.md), [seal](piece_royal_seal.md), [cannon](piece_drake_cannon.md))**: The physical objects that drive the execution process.
- **the trap ([dungeon](place_tower_dungeon.md), [scaffold](place_scaffold_square.md))**: The physical closure of the tragedy, resulting in Fabiani's death.
