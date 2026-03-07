```statblock
name: "Sirr al-Nar, The End of All Tales"
size: Large
type: Outsider
subtype: "Fire, Extraplanar, Lawful"
alignment: Lawful Evil
ac: "36 (touch 15, flat-footed 32; -1 size, +4 Dex, +8 natural, +5 deflection, +5 armor)"
hp: 247
hit_dice: "20 HD + Paragon bonuses + Toughness"
speed: "40 ft., fly 60 ft. (perfect)"
stats:
  - 24
  - 18
  - 22
  - 22
  - 26
  - 30
saves:
  - Fort: "+19"
  - Ref: "+17"
  - Will: "+22"
skillsaves:
  - Concentration: "+32"
  - Spellcraft: "+33"
  - Knowledge (arcana): "+31"
  - Knowledge (the planes): "+31"
  - Sense Motive: "+29"
  - Diplomacy: "+30"
  - Use Magic Device: "+30"
damage_resistances: "cold 20"
damage_immunities: "fire"
senses: "darkvision 60 ft., detect magic (at will), true seeing (at will)"
languages: "Common, Ignan, Auran, Celestial, Infernal, Draconic"
cr: "18"
traits:
  - name: "Combat Statistics"
    desc: "**Base Attack Bonus** +20; **Grapple** +29; **Initiative** +8; **Space/Reach** 10 ft./10 ft. **Melee:** Ashfire Blade +27 touch (4d6 fire + 4d6 untyped + dispel effect)."
  - name: "Damage Reduction"
    desc: "DR 10/magic and good."
  - name: "Spell Resistance"
    desc: "SR 30."
  - name: "Feats"
    desc: "Toughness, Quicken Spell-like Ability (fireball), Empower Spell-like Ability (fireball), Improved Initiative, Spell Penetration, Combat Casting, Iron Will."
  - name: "Ashfire (Su)"
    desc: "His blade burns not flesh but reason, time, and space. Whenever Sirr al-Nar hits with a touch attack, he deals 4d6 fire + 4d6 untyped damage. 1/round this triggers an automatic greater dispel magic effect against one ongoing magical or divine effect on the target."
  - name: "Recursive Form (Ex)"
    desc: "As a standard action, Sirr al-Nar summons an array of mirror forms that copy his every movement with minor variation. This causes a 40% miss chance from partial phasing across timelines. True seeing reveals the real Sirr al-Nar. Mirror forms dissipate after 3 rounds. Every destroyed mirror form grants fast healing 10 for 1 round and recovery of one expended spell-like ability (up to 6th level)."
actions:
  - name: "Spell-like Abilities (CL 20th, DC 20 + spell level)"
    desc: "**At will:** greater dispel magic, wall of force, plane shift, empowered fireball, true seeing. **3/day:** greater teleport, quickened searing light, mass suggestion. **1/day:** time stop, prismatic wall."
  - name: "Unwritten Prophecy (Su, 1/day)"
    desc: "As a standard action, Sirr al-Nar declares a target's false destiny. Will save DC 26 or be compelled to follow a false behavioral directive for 5 rounds (e.g., forced charge, denial of healing). Sirr al-Nar gains +2 to hit against the affected target. Disobedience causes 4d6 nonlethal damage and 1 round of confusion."
  - name: "Recalibrate Reality (Ex, 3/day)"
    desc: "Immediate action. May force a reroll of any d20 roll from the previous round. He chooses which result stands. Affects attacks, saves, checks, and spell penetration."
reactions:
  - name: "Phase Transition (Ex, 1/day)"
    desc: "When reduced to 0 HP, Sirr al-Nar explodes in Ashfire and reforms at 40% HP. Upon reforming: gains fast healing 5 (3 rounds); Ashfire Blade damage increases to 6d6 fire + 6d6 untyped; gains Reality Feedback aura (all spellcasting within 15 ft. requires Concentration DC 20 + spell level). After 3 rounds fast healing ends. After 5 rounds his body destabilizes, reducing AC and SR by 2."
```

## Tactics

- **Opening**: Begins in negotiation or monologue. Casts _wall of force_ to divide the party, then _mass suggestion_ or _empowered fireball_.
- **Mid-Fight**: Uses _Unwritten Prophecy_ to disable a key PC, then exploits _Recalibrate Reality_ to control outcomes.
- **Phase 2**: After Phase Transition, moves into melee with Ashfire Blade and spams touch attacks. Pushes casters to waste actions failing checks due to Reality Feedback aura.
