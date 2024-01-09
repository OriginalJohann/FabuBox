---
date: 202207111123
tags:
  - PnP
  - FabulaUltima
type:
  - world
---
# Drachma

> [!infobox]
> # Drachma
> ![[Image.png|cover hsmall]]
> ###### General Info
> | Type |  Stat |
> |---|---|
> | Genre | Fantasy |
> | Theme | Epic Locations |

## History
> At the beginning there was a dragon...

### Campagnes

```dataview
TABLE date as "Created at" FROM "Worlds" WHERE contains(world,[[Drachma]]) AND econtains(type,"campaign") SORT date
```

### Sessions

```dataview
TABLE date as "Played at" FROM "Worlds" WHERE date != NULL AND econtains(world,[[Drachma]]) AND econtains(type,"session") SORT date DESC LIMIT 10
```










