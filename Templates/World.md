---
date: {{date}}{{time}}
tags:
  - PnP
  - FabulaUltima
type:
  - world
---
# {{title}}

> [!infobox]
> # {{title}}
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
TABLE date as "Erstellt am" FROM "Welten" WHERE contains(welt,[[Drachma]]) AND econtains(type,"kampagne") SORT date
```

### Sessions

```dataview
TABLE date as "Gespielt am" FROM "Welten" WHERE date != NULL AND econtains(welt,[[Drachma]]) AND econtains(type,"session") SORT date DESC LIMIT 10
```



