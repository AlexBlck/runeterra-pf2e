---
icon: RaPlayer
name: Miyamoto
---
> [!infobox | right]
> # Miyamoto Musashi
> ![[miyamoto_portrait.png|cover ws-med]]
> >[!recite|bg-c-blue] [Pathbuilder](https://pathbuilder2e.com/launch.html?build=833816)
> 
> ###### Stats
> | Type | Stat |
> | ---- | ---- |
> | Test | Testing |
> ## Heading 2
> # Relationthips
> >[!kith|friend] **[[Xhokar]]**
> 
> > [!kith] **[[Lee Sin]]** - Former Master
```pf2e-stats
# Miyamoto Musashi
## Fighter 2

---

==Medium== ==Human== ==Versitile Human== ==Humanoid==

**Perception** +5

**Skills** Acrobatics +6, Athletics +8, Crafting +5, Intimidation +4, Lore: Warfare +5, Medicine +4, Stealth +6
**Str** +4, **Dex** +2, **Con** +2, **Int** +1, **Wis** +0, **Cha** +0

---
**AC** 19; **Fort** +8, **Ref** +8, **Will** +4
**HP** 32
---
**Speed** 25 feet
**Melee** Katana +10 ==Deadly, d8== ==Two-Hand, d10== ==Versatile, P== **Damage** 1d6+4 S
**Melee** Dagger +10 ==Agile== ==Finesse== ==Thrown, 10 ft.== ==Versatile, S== **Damage** 1d4+4 P
**Double Slice** `[two-actions]` **Requirements** You are wielding two melee weapons, each in a different hand. You lash out at your foe with both weapons. Make two Strikes, one with each of your two melee weapons, each using your current multiple attack penalty. Both Strikes must have the same target. If the second Strike is made with a weapon that doesn't have the agile trait, it takes a –2 penalty. If both attacks hit, combine their damage, and then add any other applicable effects from both weapons. You add any precision damage only once, to the attack of your choice. Combine the damage from both Strikes and apply resistances and weaknesses only once. This counts as two attacks when calculating your multiple attack penalty.
**Sudden Charge** `[two-actions]` ==Flourish==  Stride twice. If you end your movement within melee reach of at least one enemy, you can make a melee Strike against that enemy.
```
# Biography
Former student of [[Lee Sin]] who left the [[Shojin Monastery]]
# Interactions
```dataview
table L.text as Interaction
from "Session Notes"
flatten file.lists as L
where contains(L.text, this.name)
```