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
> ###### Allgemein
> | Type |  Stat |
> |---|---|
> | Genre | Fantasy |
> | Thema | Epische Locations |

## Geschichte
> [!campaign]- Kampagnen
> ```dataview
> TABLE date as "Erstellt am" FROM "Welten" WHERE contains(welt,[[Drachma]]) AND econtains(type,"kampagne") SORT date
> ```

>[!sessions]- Sessions
> ```dataview
> TABLE date as "Gespielt am" FROM "Welten" WHERE date != NULL AND econtains(welt,[[Drachma]]) AND econtains(type,"session") SORT date DESC LIMIT 10
> ```


