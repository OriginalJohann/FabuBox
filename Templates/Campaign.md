---
date: {{date}}{{time}}
world: "[[Drachma]]"
tags:
  - PnP
  - FabulaUltima
type:
  - campaign
references:
  - "[[Fabula-Ultima-Core-Rulebook.pdf]]"
---
# {{title}}

> [!infobox]
> # {{title}}
> ###### Goals
> - stop [[BBEG]]
> - prevent destruction of the whole world
> ###### Important Locations
> ###### Important NPCs

## Opening 

> 

### Player

```dataview
TABLE FROM "Characters" WHERE contains(campaign,[[Symphony of the Earth]]) AND econtains(type,"pc")
```

### Sessions

```dataview
TABLE date as "Played at" FROM "Worlds" WHERE date != NULL AND contains(campaign,[[Symphony of the Earth]]) SORT date DESC LIMIT 5
```