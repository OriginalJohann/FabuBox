<%*
let title = tp.file.title
if (title.startsWith("Untitled")) {
title = await tp.system.prompt("Title");
}
await tp.file.rename(title)
-%>
---
date: <% tp.file.creation_date("YYYYMMDDHHmm") %>
kampagne: "[[Symphonie der Erde]]"
welt: "[[Drachma]]"
tags:
  - PnP
  - FabulaUltima
type:
  - situation
referenzen:
  - "[[Fabula-Ultima-Core-Rulebook.pdf]]"
---
# <% title %>

## Location(s)
- **Dungeon (low): 1d8**

## History (max. 5)
1. 

## Plot (max. 5)
1. 

## Conflicts
### Conflict 1
- 

### Conflict 2
- 