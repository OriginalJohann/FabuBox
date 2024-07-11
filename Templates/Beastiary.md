<%*
let title = tp.file.title
if (title.startsWith("Untitled")) {
title = await tp.system.prompt("Title");
}
await tp.file.rename(title)
-%>
---
date: <% tp.file.creation_date("YYYYMMDDHHmm") %>
name: <% title %>
level: ""
spezies: ""
tags:
  - PnP
  - FabulaUltima
type:
  - beastiary
referenzen:
  - "[[Fabula-Ultima-Core-Rulebook.pdf]]"
---
# <% title %>

```statblock
name: <% title %>
desc: "This could be your description!"
img: "[[coolImage.jpg]]"
lvl: "LEVEL"
species: "SPECIES"
traits: "CHARACTER TRAITS"
hp: 30
crisis: 15
mp: 30
ini: 0
stats: [DEX, INS, MIG, WLP]
resi: [DEF, M.DEF, Phys, Wnd, Blt, Drk, Ear, Fir, Ice, Lght, Psn]
batk:
  - name: "Flame Swipe (melee)"
    desc: "[DEX + MIG + 1], [HR + 10], fire damage"
spells:
  - name: "Annoying Flicker"
    desc: "[INS + WLP + 1], 5 MP, One creature, Instantanious, The target suffers enraged."
special:
  - name: "Protective Shine"
    desc: "As long as this creature is alive, the Eternal Scribe looses one of his VUs."
  - name: "Construct"
    desc: "Immune to poisoned status"
others:
  - name: "Splash"
    desc: "Nothing happens."
loot:
  - name: "Big Gem"
    desc: "It's shiny, 1000z"
notes:
  - name: "Sequence"
    desc: "Targets at random."
columnWidth: 390
columnHeight: 100
```