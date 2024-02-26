<%*
let title = "Session " + tp.date.now("YYYYMMDD")
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
  - session
referenzen:
  - "[[Fabula-Ultima-Core-Rulebook.pdf]]"
---
# <% title %>

### Notizen

- 

### Recap

- 

### Spieler

- 

### NPCs

- 

---
> [!sessions]- Sessions
> ```dataview
> TABLE date as "Gespielt am", kampagne as "Kampagne" FROM "Welten" WHERE date != NULL AND econtains(type,"session") SORT date DESC LIMIT 3
> ```