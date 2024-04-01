---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- ttrpg-cli/monster/cr/20
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/devil
aliases: ["Pit Fiend"]
---
# Pit Fiend
*Source: Monster Manual p. 77, Baldur's Gate: Descent Into Avernus, Tasha's Cauldron of Everything. Available in the SRD.*  

```ad-statblock
title: Pit Fiend
![](https://raw.githubusercontent.com/5etools-mirror-2/5etools-img/main/bestiary/tokens/MM/Pit%20Fiend.webp#token)
*Large fiend (devil), Lawful Evil*

- **Armor Class** 19  (natural armor)
- **Hit Points** 300 (`24d10 + 168`)
- **Speed** 30 ft., fly 60 ft.

|STR|DEX|CON|INT|WIS|CHA|
|:---:|:---:|:---:|:---:|:---:|:---:|
|26 (+8)|14 (+2)|24 (+7)|22 (+6)|18 (+4)|24 (+7)|

- **Proficiency Bonus** +6
- **Saving Throws** Dexterity +8, Constitution +13, Wisdom +10
- **Skills** ⏤
- **Senses** truesight 120 ft., passive Perception 14
- **Languages** Infernal, telepathy 120 ft.
- **Challenge** 20

## Traits

***Fear Aura.*** Any creature hostile to the pit fiend that starts its turn within 20 feet of the pit fiend must make a DC 21 Wisdom saving throw, unless the pit fiend is [incapacitated](/compendium/rules/conditions.md#incapacitated). On a failed save, the creature is [frightened](/compendium/rules/conditions.md#frightened) until the start of its next turn. If a creature's saving throw is successful, the creature is immune to the pit fiend's Fear Aura for the next 24 hours.

***Magic Resistance.*** The pit fiend has advantage on saving throws against spells and other magical effects.

***Magic Weapons.*** The pit fiend's weapon attacks are magical.

***Innate Spellcasting.*** The pit fiend's spellcasting ability is Charisma (spell save DC 21). The pit fiend can innately cast the following spells, requiring no material components:

**At will**: [detect magic](compendium/spells/detect-magic.md), [fireball](compendium/spells/fireball.md)

**3/day each**: [hold monster](compendium/spells/hold-monster.md), [wall of fire](compendium/spells/wall-of-fire.md)

## Actions

***Multiattack.*** The pit fiend makes four attacks: one with its bite, one with its claw, one with its mace, and one with its tail.

***Bite.*** *Melee Weapon Attack:* `dice: d20+14` (+14 to hit), reach 5 ft., one target. *Hit:* `dice: 4d6 + 8|avg` (`4d6 + 8`) piercing damage. The target must succeed on a DC 21 Constitution saving throw or become [poisoned](/compendium/rules/conditions.md#poisoned). While [poisoned](/compendium/rules/conditions.md#poisoned) in this way, the target can't regain hit points, and it takes `dice: 6d6|avg` (`6d6`) poison damage at the start of each of its turns. The [poisoned](/compendium/rules/conditions.md#poisoned) target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

***Claw.*** *Melee Weapon Attack:* `dice: d20+14` (+14 to hit), reach 10 ft., one target. *Hit:* `dice: 2d8 + 8|avg` (`2d8 + 8`) slashing damage.

***Mace.*** *Melee Weapon Attack:* `dice: d20+14` (+14 to hit), reach 10 ft., one target. *Hit:* `dice: 2d6 + 8|avg` (`2d6 + 8`) bludgeoning damage plus `dice: 6d6|avg` (`6d6`) fire damage.

***Tail.*** *Melee Weapon Attack:* `dice: d20+14` (+14 to hit), reach 10 ft., one target. *Hit:* `dice: 3d10 + 8|avg` (`3d10 + 8`) bludgeoning damage.
```
^statblock