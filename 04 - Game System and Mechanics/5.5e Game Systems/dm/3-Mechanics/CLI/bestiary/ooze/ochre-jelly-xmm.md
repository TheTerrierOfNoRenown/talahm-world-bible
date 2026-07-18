---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/xmm
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/ooze
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ochre Jelly"
---
# [Ochre Jelly](ochre-jelly-xmm.md)
*Source: Monster Manual (2024) p. 230. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  
![[ochre-jelly-xmm.webp]]


## Ochre Jelly

*Multiplying Amoeboid Hunter*

- **Habitat.** Underdark  
- **Treasure.** None  

Ochre jellies are giant, yellow-brown amoebas that digest organic creatures. They tirelessly hunt any prey smaller than themselves, oozing over, under, and around obstacles in their path. Once they overwhelm their quarry, these acidic slimes dissolve the flesh, hair, and scales of their prey, leaving behind clothing, equipment, treated leather, and bone.

If damaged by lightning or a slashing weapon, an ochre jelly splits in two. These smaller jellies work together to consume foes, but afterward they move on to hunt independently. Both eventually grow into full-size jellies.

What ochre jellies can't dissolve they leave behind. Roll on or choose a result from the Ochre Jelly Leftovers table to inspire such remains.

**Ochre Jelly Leftovers**

| dice: 1d6 | After a Meal, the Ochre Jelly Leaves Behind... |
|-----------|------------------------------------------------|
| 1 | A bone etched with a word or an eerie symbol. |
| 2 | Broken dragonborn or tiefling horns. |
| 3 | An ornate prosthetic limb. |
| 4 | The skeleton of an explorer's pet (perhaps a small dog, monkey, or parrot). |
| 5 | A skull with gold teeth worth `1d4` GP. |
| 6 | A spotless suit of metal armor. |
^ochre-jelly-leftovers

```statblock
"name": "Ochre Jelly (XMM)"
"size": "Large"
"type": "ooze"
"alignment": "Unaligned"
"ac": !!int "8"
"hp": !!int "52"
"hit_dice": "7d10 + 14"
"modifier": !!int "-2"
"stats":
  - !!int "15"
  - !!int "6"
  - !!int "14"
  - !!int "2"
  - !!int "6"
  - !!int "1"
"speed": "20 ft., climb 20 ft."
"damage_resistances": "acid"
"damage_immunities": "lightning, slashing"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened),\
  \ [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled), [prone](3-Mechanics/CLI/rules/conditions.md#Prone),\
  \ [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)"
"senses": "[Blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft., passive\
  \ Perception 8"
"languages": ""
"cr": "2"
"traits":
  - "desc": "The jelly can move through a space as narrow as 1 inch without expending\
      \ extra movement to do so."
    "name": "Amorphous"
  - "desc": "The jelly can climb difficult surfaces, including along ceilings, without\
      \ needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 12 (3d6 + 2) Acid damage."
    "name": "Pseudopod"
"reactions":
  - "desc": "Trigger: While the jelly is Large or Medium and has 10+ [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md),\
      \ it becomes [Bloodied](3-Mechanics/CLI/rules/conditions.md#Bloodied) or is\
      \ subjected to Lightning or Slashing damage. _Response:_ The jelly splits into\
      \ two new Ochre Jellies. Each new jelly is one size smaller than the original\
      \ jelly and acts on its [Initiative](3-Mechanics/CLI/rules/variant-rules/initiative-xphb.md).\
      \ The original jelly's [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ are divided evenly between the new jellies (round down)."
    "name": "Split"
"source":
  - "XMM"
"image": "3-Mechanics/CLI/bestiary/ooze/token/ochre-jelly-xmm.webp"
```
^statblock


## Environment

underdark

## The Monsters Know What They're Doing

After all the time I spent trying to figure out tactics for [mummy lords](http://themonst.wwwmi3-ts2.a2hosted.com//undead-tactics-mummy-lord/) and [liches](http://themonst.wwwmi3-ts2.a2hosted.com//undead-tactics-liches/), I’m taking it easy on myself today and talking about oozes—those barely intelligent, probably nonsentient, subterranean amoeboids.

The fifth-edition _Monster Manual_ claims that oozes “have no sense of tactics or self-preservation,” but I can’t buy the second half of that. They may be “drawn to movement and warmth,” but even an amoeba will move away from an electric current. Despite the lore that oozes originated as fragments of the demon lord Juiblex, I’m going to treat them as evolved beings, akin to [slime molds](https://en.wikipedia.org/wiki/Slime_mold)—scavengers that exist as part of the subterranean ecosystem.

The _MM_ lists four types of oozes: the gray ooze, the ochre jelly, the black pudding and the gelatinous cube. All of them have several things in common: negligible Intelligence and Charisma (the ochre jelly, with Intelligence 2, is the genius of the bunch), low Dexterity and Wisdom, high Constitution, an acidic pseudopod attack and 60 feet of blindsight. Also, all but the gelatinous cube are Amorphous and can climb walls.

The **gray ooze** is the weakest and simplest of the four. Its False Appearance allows it to blend in with wet rock, so it’s self-evident that this is where a gray ooze lies in wait for its next meal. (Unlike the other oozes, the gray ooze has a +2 Stealth “skill,” reflecting its camouflage ability.) When a living being comes within 60 feet of it, it senses the being’s presence. If the being is coming toward the ooze, it holds still; if the being moves away from the ooze again, it begins to follow, continuing its slow-motion pursuit for as long as it can do so without having to expose itself (that is, move onto a surface that isn’t wet rock). When it finally comes in reach of a living being, it extends a pseudopod and grabs on.

The idea of a gray ooze forming itself into a big fist and whomping somebody is ridiculous to me, so I prefer to interpret its “bludgeoning” attack as _squeezing_: when the ooze gets its pseudopod around a PC’s leg, say, it begins to constrict and suck that leg into itself, doing physical and acid damage all the while. It will keep attacking—corroding any metal the target is wearing—until either it takes enough damage to drive it off or destroy it or the PC is completely digested.

By “completely digested,” I don’t just mean the PC is reduced to 0 hp: I mean that it’s _dead_. An unconscious victim may be presumed to be completely engulfed by the gray ooze, but it isn’t dead yet, only well on its way. Once the gray ooze has engulfed its victim, it moves away from other living beings at its full movement speed, continuing to “attack” the target inside it. Only when the target has either taken overflow damage equal to its maximum hit points or failed three death saving throws is he or she finally dead.

The gray ooze begins with 22 hp, and its predatory behavior is interrupted when it’s reduced to 8 hp or fewer. At this point, it lets go of whatever target it’s attacking and Dashes away (potentially exposing itself to opportunity attacks). Of course, “Dashing,” for an ooze, means traveling a whopping 20 feet, and catching up to it will be no problem at all for a vindictive party. So if there’s a crack it can slither into, it will do so.

The **ochre jelly** functions in the same manner as the gray ooze, with only two differences. First, since it has Spider Climb, it prefers to hang on ceilings and drop down on its prey. Second, it can be cut or blasted into multiple smaller ochre jellies.

A full-size, undamaged ochre jelly has 45 hp. Suppose it were approached by a chirurgeon with a scalpel, who inflicted the least damage necessary to cut it in two. The ~~Medium~~ **Large**-size jelly has now been cut into two ~~Small~~ **Medium** jellies, each with 22 hp, **and each of those in turn can be cut into two Small jellies with 10 hp each**. (Small jellies can’t be Split.) To force a ~~Medium-size~~ Large jelly to retreat, it has to be reduced to 18 hp or fewer by non-slashing, non-lightning damage; a ~~Small~~ **Medium** jelly must be reduced to 8 hp or fewer, **and a Small jelly, 4 hp or fewer**. Like the gray ooze, these Dash away at 20 feet per round; unlike the gray ooze, they go straight up the nearest wall to the ceiling, their instinctive place of safety, if there’s no crevice to flow into.

A **black pudding** is like a cross between the gray ooze and the ochre jelly—able to corrode weapons and armor like the former and to hang from ceilings and Split like the latter. It will spread itself across the ceiling of a cavern and, rather than drop on its prey, reach down and glom onto it with a sludgy pseudopod. A Large black pudding retreats when it’s reduced to 34 hp or fewer by non-slashing, non-lightning damage; a Medium pudding must be reduced to 16 hp or fewer; and a Small pudding must be reduced to 8 hp or fewer. Cutting a hanging black pudding in half results in one half that falls to the ground and one that remains stuck to the ceiling. The one on the ground will behave like a gray ooze or ochre jelly, remaining in place until it’s absorbed its prey (reduced him or her to 0 hp), then oozing back up the wall with it to finish digesting it in peace. If a black pudding that’s hanging from the ceiling reduces a victim to 0 hp or fewer, it will slurp it right up off the ground.

The **gelatinous cube** is always on the move, and it makes no attempt at stealth or surprise. It’s a juggernaut, like a dungeon Roomba, systematically scouring its area for anything it can digest. I’d go so far as to suggest that it should _never take the shape of a cube_. The cube shape never made sense, and it only _seemed_ to make sense back in the days when every dungeon was drawn on graph paper, at a scale of 10 feet per quarter inch. I’d like to think we DMs all have enough sense nowadays to draw cavern passages as naturally irregular in width, shape and direction. Instead, the “cube” should be an enormous blob, and suicidally curious PCs who walk right up to one should see it constantly extending and withdrawing creepy little pseudopods to sweep out every irregularity in a cavern wall.

Normally, it moves at less than its full movement rate—say, only 5 feet per round—so that it doesn’t miss a morsel. When it senses living creatures, however, it approaches at full movement speed to a distance of 25 feet, then waits motionless for one round, counting on its Transparency to let it go unnoticed until they come within reach. If they do, it attacks with surprise. If they maintain their distance, and at least one PC is still 25 feet away or closer at the end of that round, it uses its full 15 feet of movement, then its Engulf action—which includes _another_ 15 feet of movement—to absorb its prey. If the creatures move away from it instead, it follows, Dashing if necessary, until either it’s 25 feet from them again or it can no longer catch up.

Unlike the other oozes, the gelatinous cube doesn’t leave once it’s absorbed a victim. It keeps moving forward, Engulfing anyone and everyone in its path. The only thing that will make it reverse direction is reducing it to 33 hp or fewer, whereupon it Dashes away from the PCs. (Woe, then, to any PC who avoided being Engulfed by popping out the _back_ of the cube.)


