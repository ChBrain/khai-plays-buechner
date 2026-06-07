---
updated: "2026-06-07"
---

# Lucretia Borgia: Reference

## Line of Work

Georg Büchner's 1835 translation of Victor Hugo's tragedy _Lucrèce Borgia_ as **a study of power, poison, and fated family tragedy**. The play stages the toxic, corrupt atmosphere of the Ferrara court where the infamous Lucretia Borgia tries to find moral redemption in the love of her secret son Gennaro, only to be crushed by the tragic inevitability of her own crimes. The domain models this as a closed system of political paranoia, poison cups, and revenge.

## Origin

The romantic drama _Lucrèce Borgia_ written by Victor Hugo, first performed in Paris in February 1833. Georg Büchner translated the play in Strasbourg and Darmstadt in the spring of 1835 under intense time and financial pressure, selling the translation to publisher Heinrich Remigius Sauerländer to secure funds for his flight to Strasbourg.

| Source            | Key Work / Event          | Scope                                                                                                                                |
| :---------------- | :------------------------ | :----------------------------------------------------------------------------------------------------------------------------------- |
| **Victor Hugo**   | _Lucrèce Borgia_ (1833)   | The original French prose drama depicting the crimes and motherhood of Lucretia Borgia.                                              |
| **Georg Büchner** | German Translation (1835) | The translation of Hugo's work, rendered in expressive German prose, reflecting the fatalism and intensity of the romantic original. |

## Restrictions

What the production refuses to model, and to whom it delegates.

- **Historical Ferrara politics**: The production refuses to model the wider historical conflicts between Venice, Ferrara, and the Papal States, focusing strictly on the interpersonal tragedy and poison intrigues of the main cast.
- **Moral rehabilitation**: The play refuses to offer a clean moral resolution or redemption for Lucretia. Her crimes are physical facts represented by poison vials and coffins, which cannot be undone.
- **Metaphysical curses**: The tragedy is modeled as a series of physical actions and logical triggers (defacement, poisoning, vengeance) rather than a supernatural curse.

## Encoding

Source to constraint, per file.

- **[play_lucretia_borgia.md](play_lucretia_borgia.md)**: The root playbook defining the company, triggers, and four-phase plot.
- **the mother ([Lucretia](persona_lucretia.md), [poisoner](position_poisoner.md))**: The central character, caught between her toxic political past and her maternal desire for redemption.
- **the son ([Gennaro](persona_gennaro.md), [soldier](position_soldier.md))**: The brave, unguided soldier who seeks his identity but hates the Borgias.
- **the husband ([Alphonso](persona_alphonso.md), [husband](position_husband.md))**: The suspicious Duke who sees Gennaro as Lucretia's lover and plots his death.
- **the friend ([Orsini](persona_orsini.md), [friend](position_friend.md))**: The loyal companion who shares Gennaro's fate and warns him of the Borgia poisons.
- **the catalysts ([poison](piece_poison_flask.md), [antidote](piece_antidote.md), [crested shield](piece_crested_shield.md))**: The material items that trigger the execution and vengeance loop.
- **the closure ([shrouds](piece_shrouds.md), [banquet hall](place_banquet_hall.md))**: The physical layout of Negroni's hall where the final deaths occur.
