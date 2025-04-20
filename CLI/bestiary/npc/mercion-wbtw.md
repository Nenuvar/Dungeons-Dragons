---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wbtw
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/cleric
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
aliases:
- Mercion
---
# [Mercion](CLI/bestiary/npc/mercion-wbtw.md)
*Source: The Wild Beyond the Witchlight p. 224*  

Mercion strikes the balance of a natural leader and a protective caregiver. She has a direct manner that reassures and inspires those around her.

Mercion does not worship a deity, but rather an ideal: that truth gives life to artistry and beauty, and that those who embrace deceit should be censured and punished. Light is her domain.

```statblock
"name": "Mercion (WBtW)"
"size": "Medium"
"type": "humanoid"
"subtype": "cleric, human"
"alignment": "Lawful Good"
"ac": !!int "19"
"ac_class": "[plate armor](/CLI/items/plate-armor.md)"
"hp": !!int "31"
"hit_dice": "9d8 - 9"
"stats":
- !!int "15"
- !!int "10"
- !!int "9"
- !!int "12"
- !!int "17"
- !!int "17"
"speed": "30 ft."
"saves":
  "Charisma": !!int "5"
  "Wisdom": !!int "5"
"skillsaves":
  "Medicine": !!int "5"
  "Insight": !!int "5"
"senses": "passive Perception 13"
"languages": "Common, Dwarvish"
"cr": "3"
"traits":
- "desc": "Mercion casts one of the following spells, using Wisdom as the spellcasting\
    \ ability (spell save DC 13):\n\nAt will: [light](/CLI/spells/light.md), [spare\
    \ the dying](/CLI/spells/spare-the-dying.md)\n\n1/day: [death ward](/CLI/spells/death-ward.md)\n\
    \n2/day each: [command](/CLI/spells/command.md), [create food and water](/CLI/spells/create-food-and-water.md),\
    \ [cure wounds](/CLI/spells/cure-wounds.md), [faerie fire](/CLI/spells/faerie-fire.md),\
    \ [hold person](/CLI/spells/hold-person.md), [revivify](/CLI/spells/revivify.md)"
  "name": "Spellcasting"
- "desc": "Mercion wields a [+1 quarterstaff](/CLI/items/1-weapon.md)."
  "name": "Special Equipment"
"actions":
- "desc": "Mercion makes one Divine Radiance attack and one +1 Quarterstaff attack.\
    \ She can replace one of these attacks with a use of Spellcasting."
  "name": "Multiattack"
- "desc": "Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 60 ft.,\
    \ one target. Hit: 13 (3d8) radiant damage."
  "name": "Divine Radiance"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) bludgeoning damage, or 7 (1d8 + 3) bludgeoning damage when used with\
    \ two hands."
  "name": "+1 Quarterstaff"
- "desc": "Mercion creates a magical explosion of fiery radiance centered on a point\
    \ she can see within 120 feet of her. Each creature in a 20-foot-radius sphere\
    \ centered on that point must make a DC 13 Dexterity saving throw, taking 28 (8d6)\
    \ radiant damage on a failed save, or half as much damage on a successful one."
  "name": "Radiant Fire (Recharge 5-6)"
"source":
- "WBtW"
"image": "/CLI/bestiary/npc/token/mercion-wbtw.webp"
```
^statblock