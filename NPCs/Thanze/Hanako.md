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
# Description
Hanako, a lively Yordle, has vibrant, flame-red fur covering her small stature. Her large, expressive eyes are a deep shade of green, and they sparkle with infectious energy. She wears a colorful apron adorned with tiny bottles and shakers, and her small, nimble hands expertly craft unique cocktails that match her enthusiastic personality.
# Interactions
```dataview
table L.text as Interaction
from "Session Notes"
flatten file.lists as L
where contains(L.text, this.name)
```