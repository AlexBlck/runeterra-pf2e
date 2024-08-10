---
type: NPC
location: "[[Thanze]]"
building: "[[Nature's Nook]]"
name: May Li
alive: true
species: "[[Vastaya#Llhotlan]]"
gender: Female
age: "30's"
---
> [!infobox | right]
> # `= this.name`
> ![[mayli_splash.png|profile+medium]]
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

Owner of [[Nature's Nook]].
# Description
May Li is a graceful Vastaya with vibrant, feathered wings extending from her back. Her plumage is a mesmerizing blend of colors, and her eyes, a brilliant shade of turquoise, exude both wisdom and kindness. May Li's attire is practical yet adorned with intricate patterns reminiscent of her Vastaya heritage.
# Interactions
```dataview
table L.text as Interaction
from "Session Notes"
flatten file.lists as L
where contains(L.text, this.name)
```