---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/lox
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Fel Ardra"
---
# [Fel Ardra](fel-ardra-lox.md)
*Source: Light of Xaryxis p. 23*  
![[fel-ardra-lox.webp]]

```statblock
"name": "Fel Ardra (LoX)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Neutral"
"ac": !!int "13"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor-xphb.md)"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "12"
  - !!int "10"
  - !!int "13"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+4"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+4"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+2"
"damage_resistances": "fire"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger-xphb.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 11"
"languages": "any one language (usually Common), Infernal"
"cr": "2"
"traits":
  - "desc": "Fel is a 4th-level spellcaster. Its spellcasting ability is Wisdom (spell\
      \ save DC 11, +3 to hit with spell attacks). Fel has the following cleric\
      \ spells prepared:\n\n**Cantrips (at will):** [light](3-Mechanics/CLI/spells/light-xphb.md),\
      \ [sacred flame](3-Mechanics/CLI/spells/sacred-flame-xphb.md), [thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy-xphb.md)\n\
      \n**1st level (4 slots):** [command](3-Mechanics/CLI/spells/command-xphb.md),\
      \ [inflict wounds](3-Mechanics/CLI/spells/inflict-wounds-xphb.md), [shield of\
      \ faith](3-Mechanics/CLI/spells/shield-of-faith-xphb.md)\n\n**2nd level (3 slots):**\
      \ [hold person](3-Mechanics/CLI/spells/hold-person-xphb.md), [spiritual weapon](3-Mechanics/CLI/spells/spiritual-weapon-xphb.md)"
    "name": "Spellcasting"
  - "desc": "Fel has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Dark Devotion"
"actions":
  - "desc": "Fel makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one creature. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "LoX"
"image": "3-Mechanics/CLI/bestiary/npc/token/fel-ardra-lox.webp"
```
^statblock

