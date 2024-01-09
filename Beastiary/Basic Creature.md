---
date: 202305201828
name: "Basic Creature"
level: "10"
species: "Any"
tags:
  - PnP
  - FabulaUltima
type:
  - beastiary
references:
  - "[[Fabula-Ultima-Core-Rulebook.pdf]]"
---
# Basic Goon

```statblock
name: "Basic Creature"
desc: "A weaker version of a non-humanoid creature."
lvl: "10"
species: "Any"
traits: "normal, weak, swarms"
hp: 70
crisis: 35
mp: 50
ini: 8
stats: [8, 8, 8, 8]
resi: [DEF, M.DEF, -, -, -, RS, -, -, -, -, RS]
batk:
  - name: "Claws and Teeth (melee)"
    desc: "[DEX + MIG], [HR + 5], physical damage,"
  - name: "Stingers and Spit (ranged)"
    desc: "[DEX + DEX], [HR + 5], physical damage"
  - name: "Hex (ranged)"
    desc: "[INS + WLP], [HR + 5], physical damage, Before attacking roll a d8 to determine the damage type: left to right starting with Wind"
others:
  - name: "Coward"
    desc: "Will try to flee once their boss/advantage is gone."
  - name: "Scaleable"
    desc: "Bonusskill gained every 10 levels will be put into Damage Resistence while increasing HP by twice it's Level and MP by Level."
special:
  - name: "Strength in Numbers"
    desc: "Gain +1 to accuracy and damage per allied goon present"
columnWidth: 390
columnHeight: 100
```