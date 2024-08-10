---
type: NPC
location: "[[Thanze]]"
building: "[[Yellow Coast]]"
description: Lively yordle with red fur
name: Taro
alive: true
---
> [!infobox | right]
> # `= this.name`
> ![[taro_splash.png|profile+medium]]
> ###### Species
> Marai

Taro, a Marai with scales reminiscent of ocean waves, has a sleek and aquatic appearance. His eyes, a deep shade of azure, reflect the mysteries of the sea. Taro wears a wide-brimmed hat adorned with seaweed and shells, and his hands, webbed and nimble, expertly handle the day's catch. The essence of the ocean clings to him, creating an air of maritime allure.
# Interactions
```dataview
table L.text as Interaction
from "Session Notes"
flatten file.lists as L
where contains(L.text, this.name)
```