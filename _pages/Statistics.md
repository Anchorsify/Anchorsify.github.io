---
layout: distill
title: Statistics
permalink: /Statistics/
nav: false

toc:
 - name: Strength (STR)
 - name: Resilience (RES)
 - name: Chakra (CHA)
 - name: Dexterity (DEX)
 - name: Agility (AGI)
 - name: Vitality (Vit)
 - name: Hit Points (HP)
 - name: Damage Bonus, Physical (PDB)
 - name: Damage Bonus, Ninjutsu (NDB)
 - name: Willpower (WP)
---
Attributes (also commonly referred to as statistics, or 'stats' for short) are numerical representations of your character's overall physical condition: how strong they are, how fast they are, and so forth. They are the baseline for determining performance.

The five primary attributes make up, in game terms, the core of a character's capabilities. Baseline 'normal human' stats are around 20. Ninja characters will quickly exceed these numbers. This is a result of them learning to harness the chakra in their body, and benefiting from the symbiotic relationship that chakra has with their body.

##### Strength (STR)
Strength is a measurement of your ability to exert physical force on the world around you. Exceptionally strong people may be correspondingly muscular, though ninja have developed many training methods which leave them deceptively lean.

- Your physical damage bonus is STR/15.
- Your Vitality is (RES * 8 + STR * 4)

##### Resilience (RES)
This is your body's ability to endure hardship without suffering from debilitating injuries. Many ninja believe that it's best to avoid being hit entirely... but nobody will say that not being able to take a blow is a good thing. RES/10 is your bonus to Stamina rolls.

- Your Vitality is (RES * 8 + STR * 4)
- Your HP is (RES * 3 + CHA)
- You add RES/10 to your Stamina rolls.

##### Chakra (CHA)
Every ninja is fueled by chakra, a mystical force that suffuses the world and fills the bodies of all living things, much like 'ki' in certain belief systems. This stat measures both your reserves of raw chakra and your ability to harness them.

- Your ninjutsu damage bonus is CHA/15.
- You add CHA/10 to your Chakra Exhaustion rolls.

##### Dexterity (DEX)
Representing your deftness, precision, and ability to quickly respond to changes in your environment, dexterity is very important in combat, as it is what enables you to actually hit things that are moving (such as other ninja).

- Your base Accuracy bonus is DEX/10.
- Seal Speed of jutsu you perform is reduced by DEX/10.

##### Agility (AGI)
The sister attribute to dexterity, agility is how quickly you can react to danger, how fast you can move, and, as the name suggests, how agile you are overall.

- You add AGI/10 to your Dodge rolls.
- You add AGI/10 to your Initiative rolls.

#### Secondary Stats

##### Vitality (Vit)
Vitality measures your character's ability to shrug off damage, to turn a dangerous blow into a glancing one, and to take a beating without being seriously injured. You have a current and maximum vitality; whenever you take damage, you reduce your current vitality by that amount, though your maximum Vitality is unaffected.

- Your Vitality equals your (RES * 8 + STR * 4).

##### Hit Points (HP)
Hit points are like your 'life force', representing injuries that have significantly harmed you and caused serious damage to your body. After your Vitality reaches 0, you take damage to your Hit Points; an attack which depletes your Vitality has the rest of its damage carry over into your HP. When you reach 0 HP, you become incapacitated, leaving you unable to perform any actions and vulnerable to being knocked out or killed; you die automatically if you reach -100% of your Maximum HP.

- You have (RES * 3 + CHA) Hit Points.

##### Damage Bonus, Physical (PDB)
As the name would suggest, this increases the damage you do with physical attacks. Full details on how can be found in the Combat chapter.

- Your damage bonus is STR/15.

Damage bonus is unique in that it is calculated to a single decimal place, rounded down. For example, with STR of 25, you'd have a damage bonus of 25/15.0 = 1.666 = 1.6

##### Damage Bonus, Ninjutsu (NDB)
This functions practically identically to physical damage bonus, except that it applies to attacks based on their potency of your chakra rather than your physical strength, which generally means ninjutsu..

- Your damage bonus is CHA/15.

##### Willpower (WP)
Your overall strength of will. This is both your raw determination, and your confidence in your body's ability to keep going, and perform at a higher level, even when it, well, can't.

- Your Willpower is calculated as (STR + RES + CHA + DEX + AGI)/100, with a minimum of 1.
