---
type: NPC
location: "[[Thanze]]"
building: "[[Steel Lotus Forge]]"
description: Spirit armorsmith
name: Raijin
alive: true
---
> [!infobox | right]
> # `= this.name`
> ![[raijin_splash.png|profile+medium]]
> ###### Stats
> | Type | Stat |
> | ---- | ---- |
> | Test | Testing |

Raijin is an ancient Ionian Spirit residing within a suit of animated armor. The armor is adorned with intricate carvings resembling swirling winds and water. Though lacking a physical form, Raijin's presence is felt through the ethereal glow emanating from the armor's eye slits. A soft, echoing voice carries the wisdom of centuries.
## Interactions
```dataview
table L.text as Interaction
from "Session Notes"
flatten file.lists as L
where contains(L.text, this.name)
```