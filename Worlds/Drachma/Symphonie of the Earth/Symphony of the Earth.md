---
date: 202207171955
world: "[[Drachma]]"
tags:
  - PnP
  - FabulaUltima
type:
  - campaign
references:
  - "[[Fabula-Ultima-Core-Rulebook.pdf]]"
---
# Symphonie der Erde

> [!infobox]
> # {{title}}
> ###### Ziele
> - find [[Symphonic Crystal]]
> - stop [[Maestro]]
> - prevent destruction of the world
> ###### Important Locations
> - [[Ifa]]
> ###### Important NPCs
> - [[Maestro]]

## Opening 

> Once there were 2 normal people...

### Player

```dataview
TABLE FROM "Characters" WHERE contains(campaign,[[Symphony of the Earth]]) AND econtains(type,"pc")
```

### Sessions

```dataview
TABLE date as "Played at" FROM "Worlds" WHERE date != NULL AND contains(campaign,[[Symphony of the Earth]]) SORT date DESC LIMIT 5
```






