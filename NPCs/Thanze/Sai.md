---
type: NPC
location: "[[Thanze]]"
faction: "[[Shadow Order]]"
description: Isa's shadowy friend
name: Sai
alive: true
---
> [!infobox | right]
> # `= this.name`
> ![[sai_splash.webp|profile+medium p+ccr]]
> ###### Species
> Human
> # Relationthips
> >[!kith|friend] **[[Isa]]** Friend

# Biography
[[Isa|Isa's]] friend, left [[Kinkou Order]] and joined the [[Shadow Order]].
# Interactions
```dataview
table L.text as Interaction
from "Session Notes"
flatten file.lists as L
where contains(L.text, this.name)
```