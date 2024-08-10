---
type: NPC
location:
building:
description: 
name:
alive: true
faction: 
species:
gender: 
age: 
---

> [!infobox | right ]
> # `= this.name`
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


# Description
**`= this.name`** is a 
# Interactions
```dataview
table L.text as Interaction
from "Session Notes"
flatten file.lists as L
where contains(L.text, this.name)
```