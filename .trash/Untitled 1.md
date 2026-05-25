```statblock
name: Fire Elemental (XMM)
size: Large
type: elemental
alignment: Neutral
ac: 13
hp: 93
hit_dice: 11d10 + 33
modifier: 3
stats:
  - 10
  - 17
  - 16
  - 6
  - 10
  - 7
speed: 50 ft.
damage_resistances: bludgeoning, piercing, slashing
damage_immunities: fire, poison
condition_immunities: <STATBLOCK-MARKDOWN-LINK>3-Mechanics/CLI/rules/conditions.md#Exhaustion|exhaustion<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>3-Mechanics/CLI/rules/conditions.md#Grappled|grappled<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>3-Mechanics/CLI/rules/conditions.md#Paralyzed|paralyzed<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>3-Mechanics/CLI/rules/conditions.md#Petrified|petrified<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>3-Mechanics/CLI/rules/conditions.md#Poisoned|poisoned<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>3-Mechanics/CLI/rules/conditions.md#Prone|prone<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>3-Mechanics/CLI/rules/conditions.md#Restrained|restrained<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>3-Mechanics/CLI/rules/conditions.md#Unconscious|unconscious<STATBLOCK-MARKDOWN-LINK>
senses: <STATBLOCK-MARKDOWN-LINK>3-Mechanics/CLI/rules/senses.md#Darkvision|Darkvision<STATBLOCK-MARKDOWN-LINK> 60 ft., passive Perception 10
languages: Primordial (Ignan)
cr: "5"
traits:
  - desc: At the end of each of the elemental's turns, each creature in a 10-foot <STATBLOCK-MARKDOWN-LINK>3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md|Emanation<STATBLOCK-MARKDOWN-LINK> originating from the elemental takes 5 (1d10) Fire damage. Creatures and flammable objects in the <STATBLOCK-MARKDOWN-LINK>3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md|Emanation<STATBLOCK-MARKDOWN-LINK> start <STATBLOCK-MARKDOWN-LINK>3-Mechanics/CLI/traps-hazards/burning-xphb.md|burning<STATBLOCK-MARKDOWN-LINK>.
    name: Fire Aura
  - desc: The elemental can move through a space as narrow as 1 inch without expending extra movement to do so, and it can enter a creature's space and stop there. The first time it enters a creature's space on a turn, that creature takes 5 (1d10) Fire damage.
    name: Fire Form
  - desc: The elemental sheds <STATBLOCK-MARKDOWN-LINK>3-Mechanics/CLI/rules/variant-rules/bright-light-xphb.md|Bright Light<STATBLOCK-MARKDOWN-LINK> in a 30-foot radius and <STATBLOCK-MARKDOWN-LINK>3-Mechanics/CLI/rules/variant-rules/dim-light-xphb.md|Dim Light<STATBLOCK-MARKDOWN-LINK> for an additional 30 feet.
    name: Illumination
  - desc: The elemental takes 3 (1d6) Cold damage for every 5 feet the elemental moves in water or for every gallon of water splashed on it.
    name: Water Susceptibility
actions:
  - desc: The elemental makes two Burn attacks.
    name: Multiattack
  - desc: "*Melee Attack Roll:* +6, reach 5 ft. *Hit:* 10 (2d6 + 3) Fire damage. If the target is a creature or a flammable object, it starts <STATBLOCK-MARKDOWN-LINK>3-Mechanics/CLI/traps-hazards/burning-xphb.md|burning<STATBLOCK-MARKDOWN-LINK>."
    name: Burn
source:
  - XMM
image: 3-Mechanics/CLI/bestiary/elemental/token/fire-elemental-xmm.webp

```
