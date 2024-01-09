---
name: "Tables"
tags:
  - PnP
  - FabulaUltima
type:
  - reference
references:
  - "[[Fabula-Ultima-Core-Rulebook.pdf]]"
---
```dataview
TABLE level as "Level", species as "Species" FROM "Beastiary" WHERE name != NULL SORT level
```

^beastiary

```dataview
TABLE date as "Played at ", campaign as "Campaign" FROM "Worlds" WHERE date != NULL AND econtains(type,"session") SORT date DESC
```

^sessions

```dataview
TABLE date as "Created at", campaign as "Campaign" FROM "Charakters" WHERE campaign != NULL AND econtains(type,"npc") SORT date
```

^NPCs

```dataview
TABLE date as "Created at", campaign as "Campaign" FROM "Charakters" WHERE campaign != NULL AND econtains(type,"pc") AND !contains(tags,"npc") SORT date
```

^PCs

```dataview
TABLE world as "World" FROM "Locations" WHERE world != NULL SORT date
```

^locations

```dataview
TABLE  world as "World" FROM "Situations" WHERE world != NULL SORT date
```

^situations

```dataview
TABLE FROM "References" WHERE date != NULL AND econtains(type,"reference") SORT date DESC
```

^references
