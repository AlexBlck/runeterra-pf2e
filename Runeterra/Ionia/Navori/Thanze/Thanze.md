![[thanze_banner.webp|banner]]
Village in southern [[Navori]], [[Ionia]].
# Notable Inhabitants
```dataview
table building as Building, faction as Faction, description as Description
from "NPCs"
WHERE contains(type, "NPC") and contains(location, [[Thanze]])
sort rating desc
```
# Map
```leaflet
id: thanze-map
image: [[map_thanze.jpg]]
height: 500px
lat: 65
long: 35
minZoom: 7
maxZoom: 10
defaultZoom: 8
unit: km
scale: 2
```