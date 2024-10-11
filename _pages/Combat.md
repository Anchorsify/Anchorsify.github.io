---
layout: distill
title: Combat
permalink: /Combat/
nav: true
nav_order: 5

toc:
 - name: Initiative
 - name: How to Fight
 - name: Basic Actions
 - name: Stealth
 - name: Conditions and Status Effects
 - name: Fatigue
 - name: Wounds
 - name: Recovery
---

## Initiative
Combat begins with all participants making an Initiative roll: 1d20+(AGI)/10. From there, everyone is assigned a number depending upon how well they did compared to one another.

Everyone subtracts their roll from the person who rolled the highest; this is the initiative count they will act on.

>For example, Choji, Shikamaru, and Ino are all preparing to fight, and so they roll initiative. Choji scores a 6, Shikamaru a 16, and Ino a 12. They will act on the following initiative counts:
>
>Choji: 16 - 6 = 10 
>
>Shikamaru: 16 - 16 = 0 
>
>Ino: 16 - 12 = 4

People who join an Initiative after it has begun simply join on the IC the combat has advanced to upon their arrival, unless multiple people join at once, in which case they all roll initiative as normal; the highest then joins at the current IC, and others join a number of IC later as determined above.

### Flow of Time
Combat begins on Initiative Count 0, or "Init 0", or simply "IC 0". Players act whenever their initiative count is reached.

Every action a player can take has a given Speed associated with it. When they take an action, its effects are resolved immediately, and its Speed is added to their current initiative count; that is when they will be able to act again.

For example, if you use a Speed 6 action on IC 5, your action will be resolved then and there. After it finishes, combat will progress to IC 6, other people will take their turns, and so on, until IC (5+6 =) 11 is reached, when you will be able to act again.

Some effects may lower an action's Speed. No matter how many such effects are applied, no action's Speed may ever go below half its original value, rounded up, and no action's Speed (base or Final) can be reduced below 3, which means that an action with a base Speed of 3 or lower may not have its Speed decreased at all.

### Simultaneous Actions
If two people act on the same initiative count, both of their actions are declared and resolved simultaneously. Thus, you and your opponent will both fully declare and resolve your attacks (you can take turns doing so, for the sake of convenience), but not apply their effects until after you've both done so, at the very end of the IC. The exception to this is any Fatigue rolls which you must make during that IC: You roll and resolve them immediately in the midst of that IC, though you can choose to do so in any order. Penalties or changes from advancing a Fatigue level, however, do not apply to any other rolls for that IC (such as rolling a Dodge after you advanced a Fatigue level from your attack).

Variable Speed Actions (such as Block, Observe, or Guard) are partial exceptions: If you were utilizing such an action when your turn came up, and you choose to use it again as your simultaneous action, it takes priority; that is to say, you may use Block (or Total Defense, or Guard, etc.) as a defense against an attack delivered on the same IC, under those circumstances.

### Action Points
One of the things that makes battles dramatic is one or both sides pulling out sudden, unpredicted surprises, and among shinobi that's par for the course. Mechanically, this is represented by "Action Points"; thematically this can be a burst of adrenaline, or the result of you carefully luring your opponent into just the right position for you to counter-attack.

You gain 5 AP every time the Initiative Count reaches a multiple of 20. You start the battle with zero, and can have up to a maximum of AGI/2.

You can spend AP whenever you take an action. Each AP spent reduces the action's Speed by 1.

### Combat Example
It may help if you read the Actions section of this chapter before reading this example.

Using the example above, we had Shikamaru acting on IC 0, Ino on 4, and Choji on 10. Shikamaru spends his first action attacking Choji with a Speed 8 punch, meaning he'll act next on IC 8.

>To defend himself, Choji tries to dodge, though fails to do so. He's hit, and takes damage, but dodging pushed his next action back by 2, putting his next action on 12.
>
>Ino goes next, and begins forming handseals for a potent ninjutsu technique. It has a Seal Speed of 14, meaning she'll be ready to act on IC (4 + 14 =) 18.
>
>Shikamaru goes again, and uses a simple taijutsu technique with a speed of 12. Choji tries to dodge again, this time evading successfully. Shikamaru's next action will be on IC 20 (8+12), and Choji's on IC 14 (12+2, because he dodged).
>
>Choji's taking a bit of a beating, but Shikamaru's not hitting hard. He's worried about what Ino might be planning, though (she only had to declare that she was using a Perform Handseals action, not what jutsu it was for), so he disengages and rushes his other teammate, unleashing a powerful taijutsu technique with a speed of 20. Not wanting to take that kind of hit, Ino tries to dodge, and fails.
>
>Ino has to make a Chakra Control skill check against the damage of Choji's attack divided by 10, plus an additional 10. She rolls very well, and manages to succeed; had she failed, she would've automatically aborted her handseals action, meaning her next action would be on IC 15 (the attack happened on IC 14, +1 = 15), and if she wanted to use that technique she'd need to start over.
>
>Choji's next action won't come until IC 34 (14+20), whereas Ino's jutsu has been delayed until IC 20 (18+2).
>
>IC 20 comes up, and Shikamaru and Ino are both ready to go. It's too late for Shikamaru to do anything about Ino's jutsu; she's already completed the handseals, and this turn she'll be able to use it. Worse yet, he doesn't know if she'll be targeting him or Choji.
>
>If he'd had a little more time--for example, if he'd used a quicker move in place of the taijutsu technique he utilized last--he could declare a Block of a speed that would expire some time after Ino's action, allowing him to reliably defend himself if she chose to target him.
>
>That's not an option, so he goes for a quick punch at her (not wanting to make the same mistake as last time, that'll give him plenty of opportunity to prepare before Choji's next action). Ino uses her technique, a Speed 6 ninjutsu. Both try to dodge the other's technique.
>
>This means that Shikamaru will act on IC (20+8+2) 30, Ino on (20+6+2) 28, and Choji on 34.

## How to Fight
### Attacking
The simplest and most effective way to resolve a conflict is often violence. In some cases, it's the only way. Thus, it behooves any shinobi to be able to, when necessary, incapacitate or kill an opponent. The first step of attacking is to declare what your attack will be, its speed, its cost(s) (Stamina or Chakra Exhaustion) and its accuracy, so that the other player knows what you're doing, and can decide how to appropriately respond to it.  Typically, you should do so as follows:

>Choji rushes toward Shikamaru and swings a heavy fist toward his face to knock some sense into his teammate! (Basic Unarmed, Speed 8, Stamina 5, Accuracy 20)

### Accuracy
Accuracy is a measurement of how precise your attacks are, represented by a target number (TN) your opponent has to match or beat on their defense roll. Your attack's Accuracy is 10+(DEX)/10, plus any bonuses you may get from abilities, uniques, or the technique you're using. After you've declared your attack, your opponent will declare and, if applicable, roll their defense. If you hit them successfully (by beating their defense by one or more, or by them utilizing a defense such as Block, which ensures you hit), you'll then roll damage.

### Accuracy Rolls
Sometimes you'll have to make an "Accuracy Roll". This is essentially the same as your accuracy, but you replace the base 10 with a 1d20 roll. In other words, it's 1d20+(DEX/10) plus any other Accuracy modifiers. When something penalizes both Accuracy and d20 rolls, apply only the penalties to Accuracy; if it penalizes only d20 rolls, however, then those penalties also apply.

### Damage
Every attack has a "base damage", a number of dice of a certain size you roll. For example, a basic unarmed attack does 2d4 of base damage. The actual damage formula is, (Base Damage) + (Damage Bonus) * (Speed) + (any other bonuses).

Your damage bonus is the value determined by your STR (for most attacks) or CHA (for ninjutsu). The damage bonus is multiplied by Speed to represent that slower, more solid attacks are able to better benefit from your raw power. Unless otherwise noted, any alterations to an action's Speed also affect the Speed the action's damage bonus is multiplied by; faster isn't always better. Some abilities may add bonus damage, but unless they explicitly say so, this does not affect your stat-based "Damage Bonus."

Damage is done to an opponent's Vitality unless stated otherwise, until that reaches 0. Any overflow, and all future damage, goes straight to their Hit Points.

### Handseals
The majority of Ninjutsu and Genjutsu techniques have an entry for Seal Speed in their description. Those that don't, and those with a Seal Speed of 0, can be used at will, like regular actions. For the rest, however, they may not be used unless preceded by a Perform Handseals action (see Basic Actions). The jutsu you're using must be used on your next action, at which point its effects are resolved and you, as normal, will determine your next action based on the jutsu's speed.

### Genjutsu
Genjutsu are the mind-affecting, often-illusionary techniques used by ninja. While they can be potent in some situations, they're difficult to use against experienced ninja. Attempting to influence someone with Genjutsu (whether directly, such as a mental attack, or indirectly, casting an illusion over an area and determining if it fools them) is resolved through a set of opposed Genjutsu rolls.

The 'attacker' rolls 1d20+XP/400, and the 'defender' rolls 1d20+XP/200, both adding any bonuses or penalties they have to Genjutsu and d20 rolls. Some bonuses may apply only to offensive or defensive genjutsu rolls: In these cases, the person using the genjutsu is the 'attacker' and making the 'offensive' roll, and the person trying to avoid being affected is the 'defender' and accordingly making the defensive genjutsu roll. If the defender rolls lower than their opponent, they suffer the effects of the technique being used.

Bonuses and effects to "defensive rolls", such as from the Sixth Sense ability, or a Uchiha's Observe, do not apply to "defensive genjutsu rolls".  Bonuses to Accuracy do not apply to "offensive genjutsu rolls". Things that apply to genjutsu rolls are bonuses/penalties/effects...

 - Which explicitly mention genjutsu rolls.
 - Which apply to all d20 rolls.
 - From Fatigue.

Genjutsu relies upon confusing the senses, which is a powerful tool in the arsenal of someone who relies on subterfuge... or even just a shinobi needing an extra edge in combat. It's quite possible to realize one's under a genjutsu, but that doesn't give any special ability to overcome its effects ("disbelieving the illusion", so to speak, doesn't actually work). On the other hand, it's hard to fool someone again and again with the same trick. Each time a Genjutsu is successfully used against you in combat, you have a (cumulative) +5 bonus to defensive rolls against that specific jutsu for the rest of the battle.

There are three ways to break free from most Genjutsu:
 
 - Genjutsu Kai, the D-rank Ninjutsu Technique.
 - If you suffer a Wound of any severity, all Genjutsu effects applied to you end as your mind gets its act back together.
 - Many Genjutsu will have upkeeps, durations, or the like.  Details will exist in the specific jutsu entries.

By their nature, it's hard to realize that one is suffering from the effects of a Genjutsu technique. It's possible to be afflicted by a genjutsu that you know and use frequently, with obvious 'tells', and still mistake it for reality--such is the nature of delusions. Mechanically, this means that if you fail a genjutsu roll by 5 points or fewer, you realize that you've been afflicted by an illusionary technique; any higher, and you have no reason to suspect that what you're experiencing is anything but reality.

### Defending
Inevitably, you will at some point be attacked. Accordingly, ninja are trained to defend themselves in a variety of ways. Normally, you may only use a single defense against any given attack.  Like with Attacks, they follow a similar format:

>Shikamaru needs all his teeth to eat Choji's snacks when he isn't looking, and tries to slip under the shadow of the Akimichi's meaty arm for safety! (Dodge, Speed 2)

The most common defenses are Dodge and Parry, but others, such as Block, also exist.  See Basic Actions for the most common defenses.  Abilities and Jutsu can also grant you other defensive options.

A "Defensive Roll" is any roll made in opposition to the Accuracy of an opponent's attack.  A parry, or a jutsu-based defense such as Teiryuu Dageki, makes a defensive roll.

On the other hand, an opposed skill roll (such as Athletics against Trip, or a status roll) would not qualify as a "defensive roll".  Ties would still go to the defender, but it would not receive bonuses from Sixth Sense, penalties from Visibility, etc.

### Partial Success
Just because you failed to evade a shuriken or deflect a sword slash doesn't mean they struck a vital area (you are a ninja, after all). When you make a defensive roll to avoid an attack, for each point you fail by you take 20% damage. Any status effects that are part of the technique, however, will apply normally.

That can be confusing, so, it's example time! So you roll a 14 on your dodge, against an Accuracy 15 attack. You failed by 1 point, so you take 20% of the attack's normal damage. Had you rolled a 12, you would take 60% damage. And, if you had rolled a 7 (failing by 8 points), you would take the full 100% damage.

With regards to defensive jutsu: Partial success typically applies to any jutsu which works similar to a dodge or parry. That is, you make a d20 roll, and if successful the attack you are defending against does not hit you. However, if the technique has another effect (such as make a d20 roll, and if you succeed you reduce the attack's damage by a set amount), partial success does not apply. Exceptions to this will be noted otherwise in the individual technique's description.

### Damage Reduction
Some effects, such as uniques and clan abilities, provide Damage Reduction (DR). This reduces incoming damage directly: if you have 10 DR, and an attack does 100 damage, you would only take 90 damage from it. Damage Reduction does not apply to status effects, nor does it apply to any effect which does not actually deal damage to you.

Combining effects which reduce, or bypass, Damage Reduction works additively: If you use Raiton Chakra Flow (which bypasses half an opponent's Damage Reduction) with Kaminari (which does the same), then you completely bypass your target's Damage Reduction for that attack.  If combining something which reduces it by a set amount (i.e., 5 points) with something that reduces it by half, you apply the flat reduction first, then half any Damage Reduction they might have remaining.

### Mitigation Order
As it's inevitable that you will have multiple ways to reduce damage when hit, you apply effects in the following order:

1. Attacker's modifications to damage, applied additively.
2. Partial Success (as from Dodge, Parry) if applicable
3. Damage Reduction.
4. Blocking.
5. Any other percent-based (e.g., "10%") reductions of damage, applied additively.

"applied additively" means that the various methods of increasing or decreased your damage by a percentage are added/subtracted as a single value, rather than multiplying off of one another: An increase of your DB by 25% and one-third would yield (DB * (1+0.25+0.33) = DB * 1.58, while a Taijutsu Specialist using Sudden Attack 2 would yield a (base dice + DB * Speed)*(1.0+0.1-0.2), or a *0.9, damage modifier.

### Action Qualities
Some actions operate differently to others, or can be used in special ways that are otherwise distinct.  Below is the most common types of qualities you might see given to certain attacks and defenses to be aware of, though individual jutsu or abilities might list their own unique properties in their individual entries.

### Action Chains
Chains are a special type of action, where multiple techniques are combined or used at once. Each chain has a single Core action, and one or more Links. Your core action can be virtually any action in the PHB, from dodging an attack to using a high-ranked ninjutsu. What makes an action a Chain is, instead, its Links. Links are techniques which, rather than being used alone (or sometimes as an alternative to that), can be used to supplement or modify another action.

The easiest way to identify a Link is that rather than its own Speed value (like "Speed: 4"), it will say something like "Speed: +4". Many of these also have Stamina or Chakra costs written as a number to be added or subtracted. In the description of these techniques, they'll specify what they do, and when they can be used (for example, Kawarimi is linked to a Dodge action).

Using a chain is fairly simple. Simply sum up the Speeds and costs of all actions involved; these are the values for the Chain, which is treated as one single, complete action. For example, when you apply Kawarimi to a dodge, "Dodge + Kawarimi" is your new action, with a base Speed of 6, and a Seal Speed of 4. Any effects which modify an action's Speed (or other variables) do so to the Chain itself, not individual links (or the core action).

In the case of Chains where the Core action is a damage dealing attack, this becomes slightly more complicated. The Speed value used for your (Speed)*(appropriate Damage Bonus) will be the lower of the Core action's base Speed, or the Chain's final Speed (after all modifications), whichever is lower. The rank of the Core technique determines the rank of the chain; chains using Shuurai (a D-rank Raiton) would always be treated as D-rank attacks, even if you added an A-rank link to them.

There is no limit to how many links a chain may have. You could, for example, make a Chain out of Leaping Shadow Evasion (Core), Phantom Step (Link), Water Splash (Link) and, after that failed, Kawarimi (Link), all for a single dodge, so long as its Speed was still valid.

This action would have a Chakra cost of 15 (10+5, from Kawarimi and Mizuhane), and a fairly high Stamina cost (depending on how much effort you put into your Phantom Step).

How to form an Action Chain for dummies!
1. Choose (Virtually) any Action from the PHB.
2. Select a Link. Speed+(x), Stamina or Chakra +(x)
3. Tally the total Speed and Cost of your Chain.
4. Unleash the Beast!

### Interrupt
Being able to interrupt is a special quality certain abilities and techniques have, which allows them to be performed in response to another action, generally an attack directed at the user; for example, most defensive jutsu have this quality.

You may use an interrupt if the Speed of the interrupt (and in the case of ninjutsu, Speed + modified Seal Speed) is half or less that of the action you're interrupting. This is one instance where you may use a ninjutsu with handseals without having performed the handseals as a prior action.

The total Speed of the interrupt is added to your next action on the IC. Unlike normal Actions, the base Speed of Interrupts can start below 3, and be reduced by half (rounded up), going lower than 3, though in such a case they can never be reduced below Speed 1.

In the rare instance that you perform a defensive interrupt which requires Handseals, which then goes on to become an attack, the total Speed of the interrupt is what is used to determine the Speed of the associated attack, which then has a minimum Speed of 3 (like all attacks). 

### Delay
Delay is not, properly speaking, an action in and of itself, but rather a quality certain actions have. For an example of how this might be written, an attack could have "Speed 12, Delay 4". This means that while it would be declared normally on your turn, its effects would take place 4 initiative counts later. The action may be aborted any time up to the last IC of the delay.

For example, using the above attack on IC 10, you would have until IC 14 to abort; on IC 14 itself, so long as you did not abort the attack's effects would be resolved normally, and you would then act again on IC 22. An action's Speed may not be reduced below its Delay, and the Delay quality itself can not be lowered by AP or any other means, unless the effect in question specifically states otherwise.

### Abort *(Speed 1 or Speed +1)*
Certain actions will say they can be aborted, or just list "Abort" as one of their qualities along with Speed (such as the Perform Handseals action). Aborting may declared on any initiative count before your next action, allowing you to act on the following IC. When you abort an action, you stop performing it; exactly what this entails will usually be discussed in the individual actions. Alternately, you may choose to Abort as part of an Interrupt--for example, aborting handseals so you can perform a defensive ninjutsu technique. This adds 1 to the Speed of that Interrupt.

### Variable Speed Actions *(Speed Variable)*
Not to be confused with the above <i>(Speed Variable)</i> entry itself, Variable Speed Actions are those such as Block, and several abilities you can acquire with EXP (notably Guard and Total Defense), along with some specific jutsu which explicitly state they are Variable Speed Actions.  These actions do not have a set Speed, and instead you can declare their Speed to be whatever you wish: You could Block for 2 IC if you know your opponent is about to finish handseals and you want to prepare for a nasty attack, or for 20 IC if your opponent is hidden and you just want to let them plink away with ranged weapons while they make themselves easier to spot. Variable Speed actions typically come with the Abort property (meaning you can cancel them earlier than you initially declared, see Abort, above), though some specific instances might disallow this (forcing you to commit to doing it), and most simply give you a unique option you can choose to perform, not a requirement: When Blocking you can still Dodge if you wish, but you also have the Block defense available to you (at 'Speed 0').  

Variable Speed Actions are forcibly Aborted if you are ever affected by the Stun status while performing them (as in, the following IC, you immediately stop performing what you were doing), though can be restarted as your next action (taken after your Stun ends) freely.  Effects which modify the Speed of your actions (such as EF, Celerity, or Action Points) never apply to Variable Speed Actions, nor do effects which increase their speeds (such as some Wounds, or Shock), as they are based directly on the IC you choose to spend to do them.

### Willpower
Ninja are capable of incredible feats, and some are truly exceptional, performing astonishing deeds in the face of adversity. While you can be as determined (or not) as you please, Willpower represents your ability to use that determination to push yourself above and beyond your limits.

You can spend Willpower after you make an attack, or make a d20 roll, after you determine Success/Failure, but before you've seen the results. If somebody attacks you, and you fail your dodge, you may choose to spend Willpower before they roll damage. You may not wait until they've rolled damage, decide you don't want to take that much, and then declare Willpower on your defense. Similarly, you must do spend WP before an action is fully resolved; if someone dodges your attack, you cannot go back 10 IC later and spend Willpower to improve your Accuracy. You may also choose to spend Willpower after someone else has done so to alter the result of their action. However, any given roll or attack may only have Willpower applied to it one time.

When you spend a point of Willpower, reroll whichever roll it was used on (or, in the case of an attack, make an Accuracy Roll). If the d20 result is less than 11, add 10 to it; this is your new result for that action. Willpower may not, however, be used to reroll Stamina or Chakra Exhaustion rolls.

### d20 rolls
Some effects give bonuses to 'd20 rolls' as a generic benefit.  It can be confusing as to what they do or do not apply to, so for clarity, they apply to the following: 
- Defensive Rolls
- Skill Rolls
- Genjutsu Rolls
- Grapple Rolls

Which means this type of bonus **does not** apply to Accuracy (whether rolled, or as a TN), Fatigue rolls, or damage rolls which might happen to utilize a d20 for their damage dice. Generally speaking, they should apply to all bonuses which aren't those types, but check with a GM if you are uncertain.

## Basic Actions
These are actions that anyone can do in combat, and the rules associated with them.

**Basic Unarmed** ***(Speed 8, Stamina 5)***  
The simplest form of attack, this is a catch-all for punches, kicks, and any other attack which uses your body to cause harm to your opponent. This deals 2d4 base damage.

**Basic (Weapon)** ***(Speed Varies, Stamina Varies)***  
This is any ordinary attack with a weapon, from throwing shuriken to swinging oversized swords.  The base damage, speed, and stamina cost of using a weapon is listed in its entry, and they can all be found in the Equipment section.

**Block** ***(Variable Speed Action)***  
As an action, you may declare that you are blocking, and state a Speed for the action. Until your next action, you may use the Block defense (see 'Defending' above) against any incoming attacks, even ones that do not normally allow for a defense to be used (such as against jutsu with the Environmental Tag, or Explosive Tags).  Blocking reduces the damage of unarmed and ninjutsu attacks by 50%. However, weapon damage is only reduced by 25%; while it's all well and good to keep a punch away from your vitals, a sword cut is nasty business no matter where it lands.

**Dodge** ***(Speed 2, Interrupt)***  
The best defense against any attack is simply not being hit. When you dodge an attack you roll 1d20+(AGI)/10, plus any other bonuses to dodge you may have, such as from abilities or uniques, against the attack's Accuracy. Success means you completely avoid the attack and its effects.

**Move** ***(Variable Speed Action, Abort)***  
For the most part, ninja can move faster than ordinary people. When you actually devote time to moving in battle, you travel (AGI)*(number of IC spent moving)/50 yards.

Sometimes you may need to close the distance and attack an opponent all at once. When attacking, you may move towards your opponent a distance corresponding to half your attack's Speed, for free. Thus, if you needed to rush an enemy and throw a punch at them, and had 25 AGI, as a Speed 8 action you could move up to (25*(8/2)/50) = 2 yards and then use a basic unarmed attack.

Movement is unique, in that you cannot use Action Points to reduce its Speed. Your distance traveled is determined by the actual number of IC spent on movement.

**Multi-Throw** ***(Speed Varies, Stamina Varies)***  
Anyone familiar with fictionalized depictions of ninja has no doubt seen them flinging a handful of shuriken with pinpoint aim. As this game is about fictional ninjas, it stands to reason that they can do this! The term, appropriately enough, is "Multi-Throwing".

It helps to first be familiar with the two weapons you'll be throwing the most: They are the shuriken (weighing in at 1d6 base damage) and the kunai (beating it out with 2d6). While you could certainly throw a single shuriken or kunai (that would be a basic weapon attack), a real ninja would throw a bunch at once. By default, you may only throw one type of weapon at once; you could throw 6 shuriken, but not 4 shuriken and 2 kunai in the same action. After choosing your weapon, you decide how many you want to throw.

You throw at least 2 weapons, up to a maximum of DEX/10. The Speed is 3 + (number of weapons thrown)/2, and the Stamina cost is 5, +1 for every 2 weapons (6 for 2-3, 7 for 4-5, and so forth). Regardless of how many weapons you throw, the minimum total Speed of a multi-throw action is 5--this applies to both its base Speed, and its final Speed after any changes (such as spending AP). The rolled damage is the total for all weapons thrown; 6 shuriken would yield a 6d6 base damage. Your damage bonus is increased by +0.5 for every thrown weapon. So, if you had 60 STR in the above multi-throw, your damage bonus would be (60/15 = 4, 4 + 0.5x6 = 4+3 =) 7. The attack would be Speed (3 + 6/2 =) 6 and Stamina 8, and have a damage formula of: 6d6+7x6. If you are multi-throwing shuriken, their +2 Accuracy is applied only once. You do need to choose between shuriken or kunai when you multi-throw; you can't mix-and-match, tragically. Because wounds represent severe damage from a single powerful attack, and multi-throws are multiple weaker injuries delivered at once, the severity of all wounds caused by multi-throws is reduced by one category, to a minimum of Minor.

**Parry** ***(Speed 3, Interrupt)***
This entails deflecting an opponent's weapon with your own, or stopping their unarmed attacks with your bare hands. Accordingly, weapon attacks may only be parried with weapons (and when doing so can only use a single weapon to parry), and unarmed attacks may only be parried if you have at least one hand free to do so. Parrying works similarly to dodging, though uses an Accuracy Roll to determine its success. 

When something (such as Fatigue) penalizes both Accuracy and defensive rolls (or rolls in general), Parry only suffers the penalty to defensive rolls; if something penalizes only Accuracy, then Parry does suffer that penalty. Basically, it doesn't have to deal with 'double jeopardy'.

**Perform Handseals** ***(Speed Variable, Abort)***
Most Ninjutsu and Genjutsu techniques require the use of handseals, specialized hand signs that direct and mold the flow of chakra. Representing this, those jutsu have a Seal Speed listed in their description. That number, minus your DEX/10, gives you the modified seal speed, which is the Speed of your Perform Handseals, a Variable Speed Action. A Seal Speed of 0 means that while handseals are required, you can perform them so fast that the time required is negligible. You may forego part, or all, of your DEX/10 reduction of Seal Speed if you wish (for example, with 40 DEX you could use Perform Handseals action for a Seal Speed 10 jutsu at anywhere between Speed 6 and Speed 10, as you pleased).

Handseals require the use of both hands, and if they're interrupted for any reason you have to start over again. Although you don't have to declare what technique you're performing the handseals for when you start, all techniques have their own, unique combination of seals to perform them; this means that if you changed your mind partway through a Perform Handseals action, you'd need to start a new one.

If you take damage while forming handseals (between the declaration of your Perform Handseals action and when you actually use the jutsu), you must exceed 10 + (damage dealt / 10) on a Chakra Control skill roll in order to continue. Failure means you automatically Abort your Perform Handseals action.  Unlike other Variable Speed Actions, Stuns do not end your Perform Handseals action.

This should be obvious, but since it needs to be said, unless you can do Handseals one handed (i.e., unless you have Single-Handed Seals, the unique), while Performing Handseals, your hands are not free to do other things (such as parry, or grab someone, or draw a weapon).  Nor are they free to do a separate Perform Handseals action (even at SS 0) for a defensive interrupt.

**Rest** ***(Speed 5)***  
Resting is pausing to cool down and gather your breath. Since it doesn't directly lead to incapacitating your enemy, most ninja prefer to do this out of battle; however, sometimes pacing yourself is the only way to achieve victory. Every Rest action you take reduces your Stamina penalty (see the 'Fatigue' portion of this chapter) by 1, to a minimum of 0. Rest can not have its base Speed reduced, nor can you use AP to reduce the speed of your Rest action; 'resting as fast as you can' is, after all, something of an oxymoron.

**Take the Hit** ***(Speed 6, Interrupt)***  
Taking the hit is the glorious move the stronger person or sensei uses to protect their weaker ally! You make a Dodge roll with a +5 bonus; if successful, you've leapt in the way of an attack aimed at your ally. If you fail, your ally takes 20% of the damage per point you failed by. (For example: If you fail by 2 points, you'd take 60% damage, and your ally 40% damage). If you were Blocking as a Variable Speed Action when you used this, you may block as long as you were successful by 1 point or more. You may also use interrupts to defend yourself, up to a maximum Speed of how many points your Take The Hit roll beat the opponent's accuracy; you can't dodge, but you could parry, or use a ninjutsu-based defense that raises a protective wall.

You can not ordinarily Take the Hit against area of effect attacks, but for those willing to protect their allies at any cost, see the Defensive Formation ability.


## Stealth

### Hiding
Ninja hide. It's sort of their... thing. That said, hiding can be accomplished under one of four circumstances:
1. Nobody is watching you. Well, nobody you're trying to hide from. This automatically prevents usage in combat, though see the other situations.
2. Everyone you are trying to hide from has a -6 or higher visibility penalty.
3. You are already hidden, and taking another Hide action in hopes of getting a new, higher Stealth TN.
4. You use a jutsu which explicitly allows you to hide as one of its effects. Note that when you hide this way, the Hide action itself is reduced to Speed 0.

Once you meet one of those requirements, you may hide. Hiding is, of course, an action! When hidden, you may not be targeted by enemy attacks (because they don't know where you are!). It's possible to be hidden from some people, but not others.

**Hide *(Speed 10)***
<br>Make a Stealth skill roll; the result becomes your "Stealth TN" (target number), how hard it is to find you. You are hidden at level 1 Stealth. For every time you've hidden in a battle, your future Stealth rolls to hide have a -5 penalty (the third time you hid yourself, you'd have a -10 penalty; this applies even if you're hiding with jutsu or other effects).  If your stealth TN is ever reduced to 0 or below, you are no longer hidden.

**Improve Hiding *(Speed 7)***
<br>This action may be performed only while hiding at level 1 stealth. You take the time to make sure you're properly hidden and settle into place, moving you up to level 2 stealth. In case that wasn't clear, this cannot, by itself, take you from level 2 to level 3 stealth.

### Stealth Levels
There are three levels of Stealth, corresponding to different degrees of being hidden. Each level has limitations on what can be done in it; for example, in Level 2 and Level 3 Stealth, you cannot move. Thus, if you were at Stealth 3, and chose to spend an action moving, you would immediately be dropped to Stealth 1.  This is true of all actions you take in Stealth: If it isn't allowed in your current level of Stealth, but is in a lower level, you are immediately dropped to that lower Stealth level.  Actions which break Stealth, obviously, remove you from it entirely.

### Stealth, Level 1
Stealth 1 is as poorly concealed as you can be while still being unseen by your enemies. Your Stealth TN has no bonus at this rank. You may Dodge, Block, Parry, Move, Search (and do similar non-jutsu actions, such as Scan, and Observe Clones), Aim, Meditate, use Items, perform Handseals, make Surprise Attacks, and use Genjutsu (see below).

### Stealth, Level 2
Stealth 2 corresponds to being fairly well-hidden, having taken the time to adjust yourself and your hiding spot as necessary--you're not sticking your feet out past the edge of the rock you're hiding behind, for example. From Stealth 2 you may Search (and do similar non-jutsu actions, such as Scan and Observe Clones), Aim, Meditate, use Items, perform Handseals, make Surprise Attacks, use Genjutsu (see below) and prepare and perform Sneak Attacks.  At this level of Stealth, your Stealth TN has a +5 bonus.

### Stealth, Level 3
Stealth 3 is as well-hidden as you can be. You are somehow camouflaged, blending into your environment excellently. You may Search (and do similar non-jutsu actions, such as Scan and Observe Clones), Meditate, and prepare Sneak Attacks.  At this level of Stealth, your Stealth TN has a +15 bonus.

### Searching
Understandably, situations arise when Ninja want to find other, hidden ninja, or help others in doing so.

**Search** ***(Speed 6)***
<br>You look for hidden enemies, using your keen ninja senses. When you make this action, roll your Awareness skill and compare it to the Stealth TNs of all hidden enemies. If you get equal to or greater than someone's Stealth TN, you have found them. As far as you're concerned, they're no longer in stealth; they cannot perform surprise or sneak attacks against you, you can attack them, and so forth. Every time you use a Search action consecutively (without taking a non-Interrupt action between them) you get a stacking +2 bonus. Thus, your third attempt to find someone would use your Awareness skill +4. If you are the one doing the hiding, you do not automatically know that someone has discovered your hiding place; until they do something indicating they know where you are (such as attacking you, or running straight at you), you think you're still hidden from them.

**Point Out** ***(Speed 3)***
<br>You indicate where an enemy is hiding, typically by pointing at them and yelling "There he is!" loudly. This allows anyone else present to make a Search action immediately, as a Speed 0 Interrupt, with an additional +5 bonus.

### Actions from Stealth
As mentioned in Stealth Levels, your options for acting from Stealth are fairly limited, but attacking from Stealth allows for some powerful advantages.

### Surprise Attack
Any attack you make while hidden is a surprise attack. Performing a surprise attack ends your stealth, as you leap out and attack, or otherwise reveal your location in the process. If an opponent chooses to use an Interrupt to defend against your surprise attack, they may not lower its Speed by spending Action Points. Non-jutsu attacks with ranged weapons do not end your stealth, however, each time you perform one it reduces your Stealth TN by 5.

**Prepare Sneak Attack** ***(Speed Variable, Abort)***
<br>You take the time to line up a perfect attack. You may abort this action at any time, either as a normal abort, or to make your next action a sneak attack. To use an action as a sneak attack, the total Speed that you used your Prepare Sneak Attack action for must be at least equal to that of the action you're using as a sneak attack. If you take another action instead (such as moving to a new hiding spot, via another use of the Hide action), you lose your opportunity to Sneak Attack.

### Sneak Attack
A sneak attack is an improved surprise attack, and as such, all normal rules for surprise attacks apply. Additionally, any Accuracy penalties inherent to the technique or weapon you're using are removed. Penalties from other sources, such as visibility or wounds, are not negated.

A sneak attack may be used as a special type of Interrupt. You can Interrupt any action, taken by any person, with a sneak attack. They may either complete their action, and be automatically hit by your sneak attack, or call off their action and defend against your attack normally. If they call their action off they do not pay its cost, but their next action is still determined by their action's normal Speed. Sneak attacks may interrupt other actions as if their Speed was 1/4 its actual value. For example, you have been preparing a sneak attack for 18 initiative counts, when your opponent declares a basic unarmed attack (Speed 8) against your ally, on IC 80. You declare a sneak attack interrupt. You use a taijutsu technique which normally has 30 Speed; you spend 14 action points to lower its Speed to 16 (less than your 18 ICs of preparation). It now interrupts as if it was Speed (16/4 =) 4, which is half of the unarmed attack's 8, making it a valid interrupt. Your opponent would be wise to call off their attack; if they do so, they will not roll Stamina for their attack, they'll have their next action on IC 88, and they can defend with any Interrupt of Speed 8 (16/2 = 8) or lower.

In the case of jutsu which have a Seal Speed requirement that is above 0, you must first Prepare Sneak Attack for a number of IC equal to the combined (Seal Speed + Speed of the attack) you wish to use, then you must abort your Prepare Seal Speed action to use the Perform Handseals action, as would be normal for any jutsu with a Seal Speed above 0; the IC in which you finish your Perform Handseals action, you may utilize it as an interrupt following the above rules for Sneak Attacks.  If you do not use it on that IC, the jutsu is lost and you must redo the entire Prepare Sneak Attack and Perform Handseals actions all over again.  For Jutsu with a Seal Speed of 0 (after all modifications), you have no such restriction.

### Genjutsu
Genjutsu can be used from level 1 and 2 stealth, and unlike other jutsu does not break your concealment. However, it can never be a sneak or surprise attack. Genjutsu techniques which require your opponent to be able to perceive you cannot, for reasons that should be largely self-evident, be used on somebody who you're hiding from.

## Conditions and Status Effects
Conditions cover the overall health, well-being, and, well, condition, of your character. This lists the conditions, what they do, and where to find more information about them. For how to remove unwanted conditions, see the 'Recovery' section of this chapter.

### Wounded
Trained ninja can survive things that would kill or maim lesser humans, but sometimes a single blow will be so powerful that even their chakra-empowered, well-conditioned bodies cannot simply shrug it off. These are referred to as Wounds, and are explained in detail in the 'Wounds' section of this chapter. The effects, and healing requirements, for each type of wound can be found there.

### Fatigued
This is the result of (over)exerting oneself in battle. Rules for Fatigue, including how it's gained and the effects it has, are found in the 'Fatigue' section.

### Incapacitated
When your HP reaches 0, you are incapacitated. You're not necessarily unconscious, and you can still talk, but you're helpless, completely unable to take any kind of action or effectively defend yourself. An enemy who wants to can knock you unconscious with a single blow, or deliver a coup de grace to render you dead.

### Unconscious
One step up from incapacitated, this can result from being deliberately knocked out, or from severe Fatigue. When unconscious you are subject to all rules for being incapacitated, but cannot even talk or perceive your environment.

### Dead
Dying isn't as easy for ninja as normal people. There are two main ways you can die. The first is simple, overwhelming damage: If you are reduced to -100% HP, you die. The second is a coup de grace, a blow specifically designed to be lethal. You may deliver a Coup de Grace only against an Incapacitated or Unconscious opponent. A Coup de Grace is a Speed 10, Delay 5 melee-ranged action which can not have its speed reduced by any means.

### Status Effects
Status effects are things that will come and go throughout the course of battle. They come in many forms, and from many different sources. Some status effects may occur automatically (usually as a result of them applying to an area, rather than a specific target); Others, however, allow you a roll to avoid them.

Typically, this will be called a "status roll" or listed simply as "Status: (specific status, such as Burn)". Saying that the victim gets a Resistance roll against the effect is equivalent to saying that it has a status roll.

These rolls are either Chakra Control (for ninjutsu), Athletics (for taijutsu--but this is uncommon, as those effects are usually automatic), or Toxicology (for poisons). If anything else, that will be noted.

As implied above, the defender makes a Resistance skill check; if they equal or exceed the status roll, they avoid its effects. If not, they suffer them in full. Do keep in mind, if a technique or effect doesn't say it allows a roll, that probably means any special effects it has occur automatically.

Many of these status effects will be found on damaging attacks--for example, a sword slash that also causes its victim to start bleeding profusely. If the damage of such an attack is reduced to 0, none of its status effects will take place--with a few exceptions. Specifically, Immobilize and Paralysis will apply even if the attack causing them doesn't deal damage.  Likewise, status effects from paraelemental clans apply their effects so long as they hit, without the need for a status roll or to deal damage, unless stated otherwise.

Poison sometimes has special rules in this regard, but they can be found in the appropriate section of the Equipment chapter.

### Bleed
Profuse bleeding from an injury. Among other things, this can ruin your clothes; bloodstains absolutely refuse to come out of most fabrics.

While bleeding, you lose Vitality (or HP) equal to double the severity of the Bleed status every 5 IC, and have a penalty to your Stamina rolls equal to half its severity, rounded down. Every 20 IC, you reduce the severity of the status by RES/20 (after taking the damage, minimum 1).

Bleeds from the same source do not stack; the higher one overwrites the lower. Bleeds from different sources, however, all do their damage separately, though you still use only the highest Bleed to determine your Stamina penalty from the status.

### Burns
Generally resulting from exposure to fire or intense heat, such as some katon jutsu, being burnt makes it harder to fight effectively. Your Stamina rolls suffer a penalty equal to the strength of the burns on you.

You can suffer from multiple burn effects at the same time, though only the strongest penalty is actually applied. Any effects which reduce Stamina penalties reduce the severity of all your burns by the same amount. Accordingly, when you move to the next Fatigue category you are cleared of all burn effects.

### Ignite
You are on fire. Literally, you are burning. This is probably one of the most excruciatingly painful experiences of your life.

Ignite's effects are somewhat complicated. Like most statuses, it has a severity. You suffer a penalty to your Stealth checks equal to its severity, and every 5 IC you take damage equal to its severity, plus its severity in percent of your current Vitality.

Thus, an Ignite 10 would give you -10 to your Stealth and would deal 10 damage, plus 10% of your current Vitality. This damage can Wound, and wounds from Ignite are Energy Wounds. Each time it does damage, you subtract (RES/30, minimum 1) from its severity.

If you have no Vitality remaining, it instead does damage equal to its severity in percent of your maximum HP. The above Ignite 10 effect would deal 10% of your maximum HP in damage.

If someone ignites you again while you are already on fire (seriously, what kind of people are you fighting?), the more severe effect replaces the less severe one.

### Immobility
Immobilization effects are ones such as being stuck in mud or partially bound with ropes. An immobilization penalty reduces your defensive rolls by its value, and your Accuracy by half (rounded down) of its value; additionally, each point of immobilization penalty reduces your AGI for the purposes of movement by 10%. Immobilization 10 is "completely immobilized"; you cannot move at all, being rooted to your location (you could still attack and even attempt to dodge, just at a severe penalty). No matter how high your an immobilization penalty gets, its actual applied penalty can never go beyond -10. Multiple immobilization penalties do not stack; if you're suffering from a -8 and a -4, you ignore the -4 until the -8 goes away.

Many Immobilization penalties apply to an area, rather than a target, and will apply to anyone in the area until they leave it, at which point it ends; others will specify a condition (such as locks from Grapple jutsu, which apply only as long as the Grapple is maintained). Those which do not list any sort of duration or condition of their ending will fade at a rate of 1 per 10 IC after they're applied.

### Paralysis
Paralysis is an internal effect which impedes your ability to properly use your own muscles, temporarily causing spasms and twitches that prevent you from going full force.. which many ninja like to do, as it turns out.

When paralyzed, you treat the damage from your attacks as if they were (Paralysis severity) lower, to a minimum of half their final, modified Speed.

For example, at Paralysis 3 your Speed 8 Basic Attack would deal damage as if it were a Speed 5 attack; if you spent AP to reduce its Speed to 4, it would then be treated as a Speed 2 attack for its damage (because it can't reduce it by more than half, and its Speed is 4).

Paralysis effects do not combine. If you are afflicted with two paralysis effects at once, the more potent one overwrites the less severe one. If they both have the same severity, the one with the longer duration overwrites the other.

### Poison
When affected by a poison, you make a Resistance roll against some roll of the opponent's. Success means that you shrug off the effects of the poison. Failure means that you have been poisoned.

Actual poisons may carry any number of effects, but the most prominent is poison damage. For every IC that passes, you take damage equal to the poison's rating, for the full duration of the poison. For example, you're affected by a Poison 5 with a duration of 12. You take 5 damage per IC, each IC, until 12 counts after when you were first affected, for a total of 60 damage.

You may be affected simultaneously by multiple poisons. However, a single source (a specific jutsu or type of venom) may only affect you once; another application of it while under its effects simply renews the duration.

### Shock
Similar to Paralysis but more of a general impediment to one's ability to move and act, Shock effects slow down ordinarily fast-moving, fast-acting shinobi, making it easier to outmaneuver an enemy before they can recover.

Shock increases the effective Speed of all non-Variable Speed Actions by its Severity; a Shock 3 would increase a Basic Unarmed Attack from Speed 8 to Speed 11, but would deal damage based off of its original Speed (in this case, 8).  If it then had its Speed reduced (such as with AP), it could then be reduced to a minimum of Speed (11/2 = 5.5) 6 with AP, and deal damage as a Speed 6 attack; in essence, AP spent counteracts this status effect until you begin to lower its Speed below that of its unshocked amount.

Shock does apply to Interrupt actions, but at only half its severity, rounded down. Performing a Dodge (normally Speed 2) with a Shock 4 would increase it's Speed to 4 (meaning that some extremely quick, previously-avoidable attacks might become undodgeable).

Shock effects do not combine, and no action can have its speed more than doubled regardless of your Shock severity. If you are afflicted with two Shock effects at once, the more potent one overwrites the less severe one. If they both have the same severity, the one with the longer duration overwrites the other.

### Sleep
People sleep, generally because it's a necessary bodily function, but sometimes because they've been influenced by mind-affecting genjutsu. In reality, sleeping people are pretty much helpless. However, ninja develop a sixth sense that warns them of impending danger and functions even when not awake.

If someone tries to attack or sneak up on you while asleep you automatically wake up and can still roll initiative and/or defend yourself, though do so at a -5 penalty until your first action after waking up.

### Stun
Actions which stun you delay your actions by the magnitude of the stun. For example, if your next action is on IC 14, and you are affected by a Stun 5 effect, your next action would be on IC 19. Multiple stuns do not stack, but a newer one of higher magnitude will overwrite the older. Thus, using the above example, if you were hit by a Stun 7, your next action would be on IC (14+7) 21; if you were then hit by a Stun 3, there would be no change.

If an effect says that it increases stun, it means that it increase the stun status that the jutsu, weapon or attack would inflict, not that it modifies stuns that a person is suffering from. If an effect says that it extends an existing stun, it means that if a character has a stun effect, that effect is lengthened (and the character is stunned for longer).

Stun ends when get your next action; if the Stun is removed by some means prior to your next action, the effect the Stun has on your IC is removed, though this cannot bring your next action back to earlier than the current IC.  Variable Speed Actions being performed when affected by a Stun (of any severity) are forcibly Aborted.

### Suffocation
Someone or something is hindering your ability to breathe. Suffocation penalties stack, from different sources or multiple ones. Your suffocation penalty is applied to any Stamina and Chakra Exhaustion rolls you make, and every time its value increases you have to make a Stamina 15 roll (with a penalty to the roll equal to your new, increased Suffocation severity). Unlike normal Fatigue-related penalties, suffocation is not reset to 0 when your Fatigue advances. When you stop being suffocated, your suffocation penalty is reduced by 1 every 5 initiative counts.

### Visibility
These are penalties which reduce a person's ability to see clearly, impairing the use of their most valuable sense in combat. Visibility penalties do not stack; if you have a -6 and a -2, you ignore the -2 until the -6 is gone. The maximum visibility penalty you can suffer from (after any increases and reductions) is -10.

Total blindness is a -10 visibility penalty; one eye closed (or removed!) is -3. A visibility penalty reduces your Accuracy and Awareness by its value, and your defensive rolls by half (rounded down) of its value; even without their sight, a ninja's sixth sense often alerts them to danger and allows them to respond.

Many visibility penalties affect areas: clouds of smoke or mist and the like. In this case, you suffer the penalty when inside it, or when trying to attack or watch (but not defend against) someone inside it.

If it ever becomes relevant, closing or opening your eyes is a Speed 0 action--but not an Interrupt.

### Other Effects

### Area of Effect
Certain things apply not to an individual, but to all things within a given area--their "area of effect", or AoE. These include things like explosions. The simpler type of AoEs are ones which are not directly offensive, such as a smoke bomb or a jutsu that creates a thick cloud of mist. These apply certain effects so long as you're in them, and can only be avoided by moving out.

Others, however, are attacks: they cause damage to everyone within an area. Depending on that area, it may not even be possible to avoid one effectively. When being subjected to an AoE attack, the first thing to determine is if you can dodge it effectively. To do this, take the attack's Speed, and determine how far you could move (see 'Actions') in that time. If that distance is greater than the effect's radius, then congratulations, you can dodge normally. If not, you have a -2 penalty to Dodge per yard you're short by.

Taijutsu Area of Effect techniques (such as Senpuu) can be parried, but parrying an AoE attack does not 'stop' the attack outright, and anyone else who was within the area of effect can still be hit by the attack: each person must defend against it individually, and a successful parry does not stop secondary effects of the attack (such as Tsukenyaku's shockwave), though effects dependent upon a successful hit or dealing damage, obviously, do not apply on a successful parry.  Ninjutsu AoE's can not be parried by Taijutsu, but can by ninjutsu. Other defenses, such as raising a ninjutsu-based wall, are typically effective.

### Knockback
Certain jutsu have an effect referred to as "knockback", which does about what it sounds like: pushes you away from its user or point of origin. Knockback is measured in yards; a 10 yard knockback means that, if you are hit, you will be moved 10 yards away from wherever the jutsu originated from. Some may have more complex rules, such as pushing you to the edge of their area of effect.

When a technique knocks you back a certain number of yards, if partial success applies then you will also reduce the knockback by that amount. The exception is area-of-effect knock backs centered on an individual (such as a Hyuuga's Kaiten and the A-rank jutsu Eye of the Storm): partial defense does not reduce the knockback from these, as they essentially "push" everything away from them equally.

Knockback effeccts which move you through a ground-based effect does not consider you to have been 'affected by' the distance moved, and any environmental or effects based on the terrain only affect someone based on where they end up.  This means that being knocked back through Caltrops, or similar effects, would not damage someone, though being moved through walls (such as Maru o Moyashi) still affects someone normally, as would any cloud-based effects.

#### Clones and Conditions
Any clones you summon are subject to the same statuses and conditions you are suffering from at the time you summon them. This includes wounds or any status effect. Note: It may be a bad idea to make clones while on fire.



## Fatigue

### Stamina
People get tired; it just happens, even to supernaturally empowered ninja. To represent this, certain attacks have a stamina cost, listed in a format such as "Stamina: 10."

Whenever you use a move with a listed Stamina cost, you make a stamina roll: 1d20+RES/10. Regardless of the result, your attack is resolved normally. However, if you got less than the TN for your roll (that is, the move's Stamina rating) your Fatigue is raised by one category.

Realistically, continued exertion even at the same level will tire people out. Every time you make a Stamina roll, you incur a penalty equal to (the Stamina cost)/5, rounded down, on all future Stamina rolls you make. You cannot reduce the Stamina cost of any action below 5, if its unmodified cost was 5 or higher. This penalty is reset to 0 every time you advance a Fatigue category, and at the end of battle. It can also be reduced by spending your time Resting in combat.

### Chakra Exhaustion
The counterpart to stamina. Shinobi have the ability to use all manner of fantastic abilities by drawing on the chakra within themselves and manipulating the environment. While very potent, this energy comes from their body, and it's easy for a shinobi, especially an inexperienced one, to overtax themselves.

Ninjutsu and Genjutsu moves have a chakra cost, listed in a form such as "Chakra: 10." When you use these moves, you make a roll against Chakra Exhaustion; to pass, you must get equal to or greater than the technique's cost on a roll of 1d20+CHA/10. If you fail, your Fatigue is raised one category. Whether you pass or fail, your jutsu works normally.

The more chakra a shinobi spends, the more strain they put on their body. Every time you make a Chakra Exhaustion roll, you incur a penalty equal to (the Chakra Exhaustion cost)/5, rounded down, on all future Chakra Exhaustion rolls you make. You cannot reduce the Chakra cost of any action below 5, if its unmodified cost was 5 or higher. This penalty is reset to 0 every time your Fatigue category increases, and at the end of battle.

### Upkeep
Some techniques require a constant expenditure of your energy to maintain; this is what upkeep represents. So long as you maintain these techniques (which typically can be done indefinitely) you suffer a penalty to all Stamina and Chakra Exhaustion rolls equal to that technique's Upkeep. If you're maintaining multiple techniques with Upkeeps, these penalties stack, however, you can not have multiple Upkeeps from the same source, to stack the same benefit: You could not use Chakra Strengthening multiple times to gain its benefit multiple times, for example, even though you could both have an Upkeep from using Chakra Strengthening and Rock Smashing Staff together, if you wished, combining their Upkeeps together to determine your total penalty to both Stamina and Chakra Exhaustion rolls.

If your total Upkeep ever exceeds your total bonus to Chakra Exhaustion rolls (not counting any penalties), you automatically advance a Fatigue level. For example, if you had a Chakra Exhaustion roll modifier of +6+2+10-8, your total bonus would be +18. If you had an Upkeep of 19, your Fatigue would automatically advance a category, giving you another +5, for a total bonus of +23.

You may only have a single instance of any given Upkeep active at once:  You couldn't use Chakra Strengthening twice, to have multiple different upkeeps from it applying.  This includes things like weapon creation, and paraelemental conversion.

You may end any Upkeeps you're sustaining at will, even when it's not your action.

### Fatigue Levels
Fatigue represents the effects of weariness on your body. Shinobi can push themselves well beyond normal human capabilities, often displaying determination that exceeds their body's limits. You begin a battle at Fatigue 0. Whenever you fail a Stamina or Chakra Exhaustion roll, your Fatigue increments up one category, and your penalties to both those rolls reset to 0. For every 15 points you fail a roll by, you automatically advance an additional Fatigue category; thus, rolling a 12 on a Stamina 45 technique would cause you to advance 1+(45- 12)/15 = 3 Fatigue categories.

If an action (attack, defense, etc) requires you to make *both* a Stamina and Chakra Exhaustion roll, you roll the Stamina cost first.  If you for some reason need to roll multiple Stamina and/or Chakra costs as part of the same action, unless the jutsu or effect in question specifies an order you roll from lowest to highest.

For each level of Fatigue, you apply the following effects:
 - -1 to your Accuracy, offensive rolls, and skill rolls
 - -2 to your defensive rolls
 - +5 to your Stamina and Chakra Exhaustion rolls

In the case of things Genjutsu rolls or Grapple rolls, use the appropriate penalty: the person in control of a grapple is the 'attacker' making an offensive roll, and the person being grappled is the 'defender' making an appropriate defensive roll.  Likewise, the person making the Genjutsu Offense roll takes the offensive roll penalty from Fatigue, and the person making the Genjutsu Defense roll takes the defensive roll penalty.

Fatigue only goes up to 5. If you fail a Chakra Exhaustion or Stamina roll when at Fatigue 5, you complete your action and then fall unconscious, your body pushed beyond its limits.

One exception to that last paragraph, though: If you fail a technique badly enough that you would advance a Fatigue level beyond unconsciousness, the technique you were using fails to activate. Thus, say you're at Fatigue 4, and you fail a technique by 32 points. Failing it advances you to Fatigue 5; the first 15 points you fail it by advances you a second Fatigue category, placing you unconscious; however, you failed by another 15 points, and so not only are you unconscious, but your technique also fails to activate.

#### Example
>Naruto and Sasuke are fighting over who shall be Sakura's boyfriend.
>
>Sasuke starts accosting his nemesis with multiple Shishio Rendan attacks, a Stamina 15 technique. The first, he rolls a plain 1d20+7, with a total of 16, narrowly avoiding failure. Still, he's angry, and he keeps going. The next roll is 1d20+7- 3; and, the next, 1d20+7-6. Both times he passes.
>
>Not wanting to exhaust himself too quickly, Sasuke switches to his ninjutsu, tossing off a Grand Fireball, a ninjutsu with a Chakra cost of 16. He rolls his 1d20+6, and passes the roll. He follows that with a Housenka (Chakra cost 14), rolls 1d20+6-3 for Chakra Exhaustion, and again passes his check.
>
>At this point, Sasuke's next Stamina check will have a -9 penalty, and his next Chakra Exhaustion roll will have a -5 penalty.
>
>Deciding that he'll probably fail his next roll regardless, he attacks with an impressive Chidori: the move has a Chakra Cost of 25, meaning there's no way he can pass its Chakra Exhaustion check. As expected, Sasuke fails, and advances to Fatigue 1.
>
>At this point, his Stamina and Chakra Exhaustion rolls both have their penalty reset to 0, and since he's Fatigued, those rolls also have a +5 bonus. He considers following immediately with another Chidori (he'd have a small chance of avoiding failure; a roll of 14 or better, 14+6+5=25, would be sufficient), but instead decides to pace himself.



## [Wounds](https://anchorsify.github.io/Wounds/)
Shinobi can, and frequently do, endure beatings that would leave ordinary people as lifeless, mangled pulps--something about the increased flow of chakra and physical conditioning giving them unnatural durability.

Enough of a beating, over a long enough period of time, will still bring a ninja down, but little things like getting knocked off a roof or stabbed with a knife are not nearly so fatal as they'd be for normal people.

Even so, some blows are too much to just shrug off. These are called wounds, injuries that have some lasting effect on your ability to fight.

Below is the way in which you determine which wound you inflict (or suffer from!) in combat:

### Wound Categories
Simply put, you acquire wounds by taking too much damage at once. When a single source of damage deals more than a certain percent of your maximum Vitality at once, you suffer a wound of the corresponding severity. Wounds are divided into four severities: Minor, Major, Severe, and Critical.
- **Minor:** 10%
- **Major:** 25%
- **Severe:** 50%
- **Critical:** 75%

Damage dealt to your HP wounds you based on your maximum HP, as should make sense! However, the percentages are higher, to offset HP being much lower than Vitality:
- **Minor:** 25%
- **Major:** 50%
- **Severe:** 75%

For the sake of demonstration, we'll say that you have 600 Vitality, and 200 HP. An attack hits you for 100 damage. If you take this damage to your vitality (16%), you suffer one Minor wound. If you take it to your HP (50%), you'd instead suffer a Major wound.

On the other hand, if you had 60 Vitality remaining when that same attack hit, you'd lose 60 Vitality (10%) and 40 HP (25%), resulting in two Minor wounds.

### Damage Types
After determining the severity of a wound, the next (fairly simple!) step is determining what type of wound it is. Being cut by a sword and being hit by a magical ninja fireball, even if they do the same amount of damage, have significantly different effects on the human body. For the most part this is self-explanatory, with only four damage types recognized: Blunt, Slashing, Piercing, and Energy.

Unarmed attacks are always blunt damage, nice and simple. Weapons have their damage type, or types, listed in their descriptions. If a weapon can do multiple types of damage, the attacker declares which type of wound they'll be inflicting after the severity is confirmed, but before the location is determined. Some weapon jutsu require a weapon of a specific damage type to be used; in this case, damage from that jutsu is considered to be of that type.

Ninjutsu are simpler than weapons! Katon and Raiton jutsu inflict energy damage. Doton and Suiton inflict blunt damage. Fuuton inflicts slashing damage. An exception! Some jutsu augment a weapon strike, or actually create a weapon. In these cases, use the damage type of that weapon, not the element it was made from.

### Location
After determining severity and damage type, you roll to determine location--where you hit, and what you injured. It's all well and good to say you threw a punch at their face, but this is battle, with ninjas! Things rarely go as planned. You roll a percentile die (1d100) for location, and check the relevant damage type's wound list, under the appropriate severity, to determine the effect. If it's an arm or leg that's been wounded, odds on the 1d100 are the right arm, and evens the left. This all gets simpler if the defender is blocking; in that case, they choose the location.

Multiple wounds, even multiples of the same effect, stack. Two broken left arms means that your arm is broken twice, with double the normal penalties.

One exception. If you suffer a critical wound, it overrides all lesser wounds on that location--having an arm reduced to useless deadweight makes the fact that it's broken in six places kind of, well, irrelevant. Two criticals in the same place, however, is oh so very possible.

### Called Shots
A called shot is an attack specifically targeting a certain location. After checking your attack's damage type, choose any of the locations which can be Wounded by damage of that type. You declare that when you make your attack, for example, "Hinotama, Called Shot: Arm".

The attack has a -4 Accuracy penalty. However, if it hits, any wounds it inflicts will automatically be dealt to that location. You can not used Called Shot with Area of Effect attacks, except for Targeted Area of Effect attacks, where you can make the attack a Called Shot against your chosen target, but anyone else within range to be hit by it will not consider it a Called Shot (though the penalty to its Accuracy applies regardless, as it is penalizing the attack itself).


## Recovery

### Hit Points and Vitality
Lost Vitality recovers fairly quickly; ninja don't get too far through their training without being able to get back on their feet. You recover 10% of your maximum Vitality every 10 minutes OOC.

Lost Hit Points are harder to deal with. By the time you're taking HP damage, your body's already reached its limit as far as soaking damage goes. You recovery 10% of your max HP every 1 hour OOC.

### Fatigue
Fatigue is more than just being a little winded; it's exhaustion and bone-deep weariness. Ninja are just much better able to deal with such things than normal people. Every hour that passes OOC, your Fatigue is lowered by one level.  Uniques and effects which recover penalties over time (such as Endless energy, or Regenerative Chakra) do not noticeably impact how quickly you recover fatigue, or fatigue penalties, outside of battle.

### Willpower
You begin every (OOC) day with your full amount of Willpower. With the exception of some rare effects, you can't get Willpower back any faster than that.

### Wounds
Wounds are particularly grievous injuries, ones powerful enough to have effects beyond just beating you that much closer to unconsciousness. The rules for what causes Wounds are discussed in the appropriate section of the combat chapter.

And, so are their recovery times! How long a given wound takes to heal will be listed in that wound's own description. Many can be reduced by medical attention (as described below).

Minor wounds all heal at the same rate, with or without rest or medical attention. Most wounds will heal even if you're not getting rest, with details listed for each individual wound; if it says nothing on the matter, rest or lack thereof won't change its recovery time.

### Medical Attention
Many of the listed recovery times assume you're waiting to get better on your own; ninja have a remarkable ability to recover from injuries, full as they are of vim and vigor. Naturally, you heal faster when you're actually getting rest and have trained medical professionals looking after you. In fact, you regain everything except Willpower twice as fast when receiving medical attention.

...Which brings us to what 'medical attention' means. It means you are in a hospital, or getting an equivalent amount of bed rest, with one or more doctors or medics checking up on you regularly. You are getting sleep and being taken care of, not training or researching a new jutsu. You can most likely have visitors.

Every ninja village's hospital is always open to its shinobi. That said, if you try to check yourself in because you have no vitality and half your HP, and want to spar your friend again that afternoon, you will promptly get kicked out. On the other hand, if you're beaten to a pulp (unconscious at 0 HP) or severely injured (you have a Wound of Major or greater) you can check yourself in.

However, once you've gone to a hospital they won't let you leave for 24 OOC hours, unless it's on important business-- such as being required for a mission your village is sending you on. The doctors have gotten very good at seeing through people's excuses.

### Guidelines
Sometimes people get silly ideas and have to be corrected. This is to hopefully preempt that, by clarifying a few things! You probably don't need to read anything in this section unless it actually comes up during gameplay.

### IC and OOC Recovery
What happens if you're IC and need to know how fast you heal? For example, if you're on a mission, or trying to buy time between fights. If it takes ten minutes to RP a conversation, have you healed in that time? What about if you need to step away from your computer for an hour to do laundry, but there's someone who just drew a knife on you? For the most part, this really doesn't matter; you can assume OOC healing times apply unless it actually is an important situation.

Should such a situation (that is, an important one, or a GM-run event), use the following in-character times:
- 10% Vitality: 1 hour
- 10% HP: 6 hours
- 1 Fatigue level: 6 hours
- Willpower: Restored fully after six consecutive hours of restful sleep.
- Wounds: 1 OOC day = 1 IC week

Medical attention halves all of these, except as detailed above.

### Rest
Your body can't heal when you're putting too much stress on it. It's why doctors recommend bed rest (and lots of fluids, and "grape" flavored medicine that tastes just horrid, and nothing like grapes).

'Rest' for a ninja, however, does not entail laying in bed for the afternoon. Taking damage, or failing a Stamina or Chakra Exhaustion roll, interrupts your healing; this applies to Vitality, HP, and Stamina. So, if you had been recovering from 0 Vitality, Fatigue 3, and full HP for an hour and fifteen minutes, then did something to exert yourself and failed a Stamina roll, you'd have recovered 70% of your maximum Vitality (75 minutes, /10 = 7) and 1 Fatigue level, putting you at Fatigue 2--except you just failed that roll, so back to Fatigue 3 you go.

That doesn't apply to Wounds (unless specified otherwise) or Willpower. If your healing of a Wound is interrupted (usually by a method mentioned in that Wound's description), you still keep however many days of progress you've made towards recovering from it--you just don't get to count the current day.

If, for some reason, you are suffering from starvation, dehydration, or sleep deprivation (less than 6 hours of restful sleep a night), all of your healing times, including Willpower, are doubled. For wounds, this means that every 2 consecutive days of healing count as only 1 (in case you, before having fully recovered, return to sleeping/eating/drinking and are able to resume healing at the normal rate).

