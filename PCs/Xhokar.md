---
icon: RaPlayer
name: Xhokar
---
> [!infobox | right]
> # Xhokar
> ![[xhokar_portrait.webp|cover portrait ws-med]]
> >[!recite|bg-c-blue] [Pathbuilder](https://pathbuilder2e.com/launch.html?build=833813)
> 
> ###### Stats
> | Type | Stat |
> | ---- | ---- |
> | Test | Testing |
> ## Heading 2
> # Relationthips
> >[!kith|friend] **[[Miyamoto]]**
> 
> >[!kith|friend] **[[Lee Sin]]**

# Biography
Xhokar is a monk from the [[Shojin Monastery]], where he's been taught by [[Lee Sin]].
# Interactions
```dataview
table L.text as Interaction
from "Session Notes"
flatten file.lists as L
where contains(L.text, this.name)
```