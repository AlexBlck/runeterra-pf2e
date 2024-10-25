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
occupation: 
goal:
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
<!-- QueryToSerialize: TABLE L.text as Interaction FROM "Session Notes" FLATTEN file.lists as L WHERE contains(L.text, this.name) -->
<!-- SerializedQuery: TABLE L.text as Interaction FROM "Session Notes" FLATTEN file.lists as L WHERE contains(L.text, this.name) -->

| File | Interaction |
| ---- | ----------- |
<!-- SerializedQuery END -->
