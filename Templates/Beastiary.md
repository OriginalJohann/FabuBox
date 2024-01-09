---
date: {{date}}{{time}}
name: "{{title}}"
level: ""
species: ""
tags:
  - PnP
  - FabulaUltima
type:
  - beastiary
references:
  - "[[Fabula-Ultima-Core-Rulebook.pdf]]"
---
# {{title}}

```statblock
name: "{{title}}"
desc: "A huge rock formation awakened by earth spirits. It may lay motionless for centuries, then suddenly rise and sow destruction."
img: "[[sickleWeasel.jpg]]"
lvl: "LEVEL"
species: "CLASS"
traits: "CHARACTER TRAITS"
hp: 30
crisis: 15
mp: 30
ini: 0
stats: [DEX, INS, MIG, WLP]
resi: [DEF, M.DEF, Phys, Wnd, Blt, Drk, Ear, Fir, Ice, Lght, Psn]
batk:
  - name: "BASIC ATTACK (ranged)"
    desc: "[INS + WLP], [HR + 1], fire damage, target suffers weak"
  - name: "BASIC ATTACK (melee)"
    desc: "[DEX + MIG], [HR + 1], physical damage, target suffers shaken"
spells:
  - name: "SPELLS"
    desc: "[MIG + WLP], 10 MP, One creature, Scene, Until this spell ends, the target suffers 5 extra damage from all sources that deal poison damage."
others:
  - name: "OTHER ACTIONS"
    desc: "The arcane lantern may use an action and spend up to 10 Mind Points to choose another creature it can see. That creature recovers an equal amount of Mind Points."
special:
  - name: "SPECIAL RULES"
    desc: "Can't be hit with melee, hit by weakness and opportunity ends effect, does not work during crisis"
equip:
  - name: "EQUIPMENT"
    desc: "Martial Sword, Two-handed, melee, [DEX + MIG] + 1, [HR + 10] physical damage, 200 zenit"
columnWidth: 390
columnHeight: 100
```