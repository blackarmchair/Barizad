```statblock
name: "The Warden of Errors"
size: Medium
type: Construct
subtype: Living Construct
alignment: Lawful Neutral
ac: "21 (10 + 8 armor + 1 Dex + 2 natural)"
hp: 92
hit_dice: "Brazen Warblade 6 / Fighter 3"
speed: 30 ft.
stats:
  - 20
  - 12
  - 16
  - 12
  - 10
  - 6
saves:
  - Fort: "+10"
  - Ref: "+6"
  - Will: "+5"
skillsaves:
  - Intimidate: "+8"
  - Concentration: "+14"
  - Balance: "+5"
  - Jump: "+12"
  - Knowledge (tactics): "+8"
senses: "darkvision 60 ft."
languages: "Common, Ignan"
cr: "9"
traits:
  - name: "Combat Statistics"
    desc: "**Base Attack Bonus** +9; **Grapple** +14; **Initiative** +1. **Melee:** +1 True Brass Maul +15/+10 (2d6+7; bypasses DR of celestials and constructs). **Full Attack:** +1 True Brass Maul +15/+10 (2d6+7)."
  - name: "Feats"
    desc: "Power Attack, Improved Bull Rush, Iron Will, Weapon Focus (Maul), Combat Reflexes, Mage Slayer (Complete Arcane)."
  - name: "Echo Memory"
    desc: "Will save (DC 13) or dazed 1 round when first seeing a Celestine relic."
  - name: "Celestine Echo (Su, 1/day)"
    desc: "Reroll a failed Will save vs. compulsion or charm."
  - name: "Unmake Pattern (Su, 1/day)"
    desc: "As a free action, cancel one targeted spell or SLA directed at him (as if by greater dispel magic, CL 9, counterspells only)."
  - name: "Recursive Strike (Ex, 1/round)"
    desc: "If he misses a melee attack and the same PC hits him that round, he can reroll the missed attack once."
actions:
  - name: "Warblade Maneuvers Readied (4)"
    desc: "**Steel Wind** (strike 2 enemies). **Iron Heart Surge** (remove one ongoing effect). **Wall of Blades** (use attack roll as AC). **White Raven Tactics** (ally takes extra turn)."
  - name: "Warblade Stances"
    desc: "**Punishing Stance:** +1d6 melee damage, -2 AC. **Bolstering Voice:** allies within 10 ft. get +2 Will saves."
  - name: "Warblade Class Features"
    desc: "Battle Clarity (+1 to Reflex saves when unarmored). Weapon Aptitude (can swap weapon-specific feats each day)."
reactions:
  - name: "Equipment"
    desc: "**True Brass Maul +1:** 2d6+7 base, bypasses DR of constructs and celestials. **Adamantine Full Plate +1.** **Amulet of Health +2.** **Belt of Giant Strength +2.** **Ring of Deflection +1.** **Boots of Stability:** +4 to resist bull rush, trip, and similar effects."
```

## Tactics

- Begins in **Punishing Stance**, charging forward to bull rush a caster or control target
- Combines **Mage Slayer** with **White Raven Tactics** to harass support characters
- Uses **Wall of Blades** defensively if targeted by touch spells
- **Iron Heart Surge** removes Slow, Blindness, or Hold Person
- Retreats only if Seraphine commands it — otherwise fights until deactivated
