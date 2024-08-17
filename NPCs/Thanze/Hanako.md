---
type: NPC
location: "[[Thanze]]"
building: "[[Scarlet Sip Tavern]]"
description: Lively yordle with red fur
name: Hanako
alive: true
species: "[[Yordle]]"
age: 30's
gender: Female
---

> [!infobox | right]
> # Hanako
> ![[hanako_splash.png|profile+medium]]
> # Bio
>  `$= if (!dv.current().alive) { "|Dead|\n |----|" }`
>  
> |  |  |
> | ---- | ---- |
> | **Species** |  `= this.species` |
> | **Age** |  `= this.age` | 
> | **Gender** | `= this.gender` |
> 
> # Location
> |  |  |
> | ---- | ---- |
> -  `= this.location`
> 	- `= this.building` 

Owner of the [[Scarlet Sip Tavern]] in [[Thanze]].
## Description
Hanako, a lively Yordle, has vibrant, flame-red fur covering her small stature. Her large, expressive eyes are a deep shade of green, and they sparkle with infectious energy. She wears a colorful apron adorned with tiny bottles and shakers, and her small, nimble hands expertly craft unique cocktails that match her enthusiastic personality.

## Interactions
<!-- QueryToSerialize: TABLE L.text as Interaction FROM "Session Notes" FLATTEN file.lists as L WHERE contains(L.text, this.name) -->
<!-- SerializedQuery: TABLE L.text as Interaction FROM "Session Notes" FLATTEN file.lists as L WHERE contains(L.text, this.name) -->

| File                                      | Interaction                                                                                                                                                                         |
| ----------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [[Session Notes/Session 2.md\|Session 2]] | The party got a few drinks at the [[Scarlet Sip Tavern]] and met its owner [[Hanako]].                                                                                              |
| [[Session Notes/Session 2.md\|Session 2]] | [[K]] mentioned to [[Hanako]] that some people seem to not like the [[Shadow Order]] guys in here, which led a cold response and a rant from [[Hanako]] addressed to all customers. |
<!-- SerializedQuery END -->


