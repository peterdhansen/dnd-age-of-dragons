		---
cssclass: dnd
---

# Haldir: Level 7 Druid
HP: 18/43 + 0THP
Hit Dice: 7/7 d8 + 1

![[Haldir/Attributes|Attributes]]
## Spell Slots
1. Level 1
	- [ ] 1
	- [ ] 1
	- [ ] 1
	- [ ] 1
2. Level 2
	- [ ] 2
	- [ ] 2
	- [ ] 2
3. Level 3
	- [ ] 3
	- [ ] 3
	- [ ] 3
4. Level 4
	- [ ] 4

## Wildshape
- WildShape HP  
- WildShape
	- [ ] 1
	- [ ] 2
- Balm of the Winter Court Left 7d6: 4/7  
- Wood Elf Magic
	- [ ] Longstrider
	- [ ] Pass Without Trace
## Items
- Breastplate
- [[Horn of Silent Alarm]]
- [[Quiver of Ehlonna]]
	- Longbow
	- Quarterstaff
	- 160 Arrows
	- 4 Spears
- [[Rope of Climbing]]
- Backpack
	- Bedroll
	- Mess Kit
	- Tinderbox
	- 4 Torches
	- 10 Rations
	- Waterskin
	- 50 ft rope
	- 2 Magic suppression ingots
- [[Pale of Tincture]]
- Herbalism Kit
- Lute
- Bony Wand (Necromatic)
	- 
- Money
	- 27 platinum
	- 632 gold
	- 175 silver

```dataviewjs
dv.table(["Level", "Spell", "Components", "Duration/CastTime"],
dv.pages("#druidspells").file.tasks
            .where(t=>t.completed)
			.map(t => t.text.split("|"))
);
```

Number of Spells (4 Cantrips + 4 Wisdom + 7 Level + 2 auto = 17): `$= dv.pages("#druidspells").file.tasks.where(t=>t.completed).length` 
%%
```dataview
task from #druidspells where completed
```
%%
