---
date: {{date}}{{time}}
welt: "[[Drachma]]"
tags:
  - PnP
  - FabulaUltima
type:
  - kampagne
referenzen:
  - "[[Fabula-Ultima-Core-Rulebook.pdf]]"
---
# {{title}}

> [!infobox]
> # {{title}}
> ###### Ziele
> - [[Maestro]] besiegen
> - Zerstörung der Welt verhindern
> ###### Wichtige Orte
> ###### Wichtige NPCs

## Opening 

> 

 >[!persons]- Spieler
> ```dataview
> TABLE FROM "Charaktere" WHERE contains(kampagne,[[Symphonie der Erde]]) AND econtains(type,"pc")
> ```

>[!sessions]- Sessions
> ```dataview
> TABLE date as "Gespielt am" FROM "Welten" WHERE date != NULL AND contains(kampagne,[[Symphonie der Erde]]) SORT date DESC LIMIT 5
> ```