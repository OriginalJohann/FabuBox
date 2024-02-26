<%*
let title = tp.file.title
if (title.startsWith("Untitled")) {
title = await tp.system.prompt("Title");
}
await tp.file.rename(title)
-%>
---
date: <% tp.file.creation_date("YYYYMMDDHHmm") %>
welt: "[[Drachma]]"
tags:
  - PnP
  - FabulaUltima
type:
  - location
referenzen:
  - "[[Fabula-Ultima-Core-Rulebook.pdf]]"
  - "[[Fabula-Ultima-Atlas-High-Fantasy.pdf]]"
---
# <% title %>

> [!infobox]
> # <% title %>
> %%## ![[IMAGE|cover hsmall]]%%
> ###### Keywords
> adventure, home, longing, nest.
> ###### Themen
> the journey's start, the call to adventure, the end of childhood.
> ###### Terrain
> fields, hills, marble.
> ###### Travel roll
> d6, d8
> ######  Affinitäten
> ||Elemente|
> |---|---|
> |Häufig|Ear, Ice, Lght|
> |Selten| Drk, Fir|
> ###### Gefahren
> a [[Behemoth]] passes the barrier; people with no apparent
connection to one another disappear throughout the realm.
> ###### Entdeckungen
> a messenger bears odd news from the outer world; [[Nefti Ruins]]; [[Templates/Lokationen#Founder's Plaza|Founder's Plaza]].
> ###### Wichtige NPCs
> | Typ |  Name |
> |---|---|
> |Clever Merchant|[[Emmet]]|

### Beschreibung

A serene and prosperous realm stretches along a wide navigable river, surrounded
by ivory walls that project a mighty magical barrier. An elegant castle towers above
shimmering azure waterfalls that dive into the lake at the center of this never-
conquered capital. Some say there is no safer place in the world. Why would anyone
ever leave?

### Typische Vorkommnisse

- An enigmatic leader who cares for the people’s needs.
- An ancient order of knights that defend the realm with magic.
- Secret access to a place long forgotten, perhaps discovered by one of the PCs
during childhood.
- A viewpoint from which one can admire one of its marvels.

### Besonderheiten

#### Founder's Plaza

A grand marble plaza dedicated to the Founding Queen lies at the center of Oniria’s
lake, connected to the city by airy vaulted bridges. There, the Queen’s statue stands
before a great waterfall. What does it hold in its hands?

#### Nefti Ruins
siehe [[Nefti Ruins]]


