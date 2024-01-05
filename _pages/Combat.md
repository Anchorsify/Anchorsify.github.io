---
layout: distill
title: Combat
permalink: /Combat/
nav: true
nav order: 10

toc:
 - name: Initiative
 - name: How to Fight
 - name: Basic Actions
 - name: Stealth
 - name: Pursuit
 - name: Conditions and Status Effects
 - name: Fatigue
 - name: Wounds
 - name: Recovery
 - name: Weather Conditions
---

## Inititiative
Combat begins with all participants making an Initiative roll: 1d20+(AGI)/10. From there, everyone is assigned a number depending upon how well they did compared to one another.

Everyone subtracts their roll from the person who rolled the highest; this is the initiative count they will act on.

>For example, Choji, Shikamaru, and Ino are all preparing to fight, and so they roll initiative. Choji scores a 6, Shikamaru a 16, and Ino a 12. They will act on the following initiative counts: Choji: 16 - 6 = 10 Shikamaru: 16 - 16 = 0 Ino: 16 - 12 = 4

People who join an Initiative after it has begun simply join on the IC the combat has advanced to upon their arrival, unless multiple people join at once, in which case they all roll initiative as normal; the highest then joins at the current IC, and others join a number of IC later as determined above.

#### Flow of Time
Combat begins on Initiative Count 0, or "Init 0", or simply "IC 0". Players act whenever their initiative count is reached.

Every action a player can take has a given Speed associated with it. When they take an action, its effects are resolved immediately, and its Speed is added to their current initiative count; that is when they will be able to act again.

For example, if you use a Speed 6 action on IC 5, your action will be resolved then and there. After it finishes, combat will progress to IC 6, other people will take their turns, and so on, until IC (5+6 =) 11 is reached, when you will be able to act again.

Some effects may lower an action's Speed. No matter how many such effects are applied, no action's Speed may ever go below half its original value, rounded up, and no action's Speed can be reduced below 3, which means that an action with a base Speed of 3 or lower may not have its Speed decreased at all. Interrupts are the sole exception to this: They can start below 3, and be reduced by half (rounded up), going lower than 3, though in such a case they can never be reduced below Speed 1.

#### Simultaneous Actions
If two people act on the same initiative count, both of their actions are declared and resolved simultaneously. Thus, you and your opponent will both fully declare and resolve your attacks (you can take turns doing so, for the sake of convenience), but not apply their effects until after you've both done so, at the very end of the IC. The exception to this is any Fatigue rolls which you must make during that IC: You roll and resolve them immediately in the midst of that IC, though you can choose to do so in any order. Penalties or changes from advancing a Fatigue level, however, do not apply to any other rolls for that IC (such as rolling a Dodge after you advanced a Fatigue level from your attack).

Variable speed actions (such as Block, Observe, or Guard) are partial exceptions: If you were utilizing such an action when your turn came up, and you choose to use it again as your simultaneous action, it takes priority; that is to say, you may use Block (or Total Defense, or Guard, etc.) as a defense against an attack delivered on the same IC, under those circumstances.

#### Action Points
One of the things that makes battles dramatic is one or both sides pulling out sudden, unpredicted surprises, and among shinobi that's par for the course. Mechanically, this is represented by "Action Points"; thematically this can be a burst of adrenaline, or the result of you carefully luring your opponent into just the right position for you to counter-attack.

You gain 5 AP every time the Initiative Count reaches a multiple of 20. You start the battle with zero, and can have up to a maximum of AGI/2.

You can spend AP whenever you take an action. Each AP spent reduces the action's Speed by 1.

#### Combat Example

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

#### Attacking
The simplest and most effective way to resolve a conflict is often violence. In some cases, it's the only way. Thus, it behooves any shinobi to be able to, when necessary, incapacitate or kill an opponent. The first step of attacking is to declare what your attack will be, its speed, and its accuracy, so that the other player knows what defenses they can use against it.  Typically, you should do so as follows:

>Choji rushes toward Shikamaru and swings a heavy fist toward his face to knock some sense into his teammate! (Basic Unarmed, Speed 8, Stamina 5, Accuracy 20)

#### Accuracy
Accuracy is a measurement of how precise your attacks are, represented by a target number (TN) your opponent has to match or beat on their defense roll. Your attack's Accuracy is 10+(DEX)/10, plus any bonuses you may get from abilities, uniques, or the technique you're using. After you've declared your attack, your opponent will declare and, if applicable, roll their defense. If you hit them successfully (by beating their defense by one or more, or by them utilizing a defense such as Block, which ensures you hit), you'll then roll damage.

#### Accuracy Rolls
Sometimes you'll have to make an "accuracy roll". This is essentially the same as your accuracy, but you replace the base 10 with a 1d20 roll. In other words, it's 1d20+(DEX/10) plus any other Accuracy modifiers. When something penalizes both Accuracy and d20 rolls, apply only the penalties to Accuracy; if it penalizes only d20 rolls, however, then those penalties also apply.

#### Damage
Every attack has a "base damage", a number of dice of a certain size you roll. For example, a basic unarmed attack does 2d4 of base damage. The actual damage formula is, (Base Damage) + (Damage Bonus) * (Speed) + (any other bonuses).

Your damage bonus is the value determined by your STR (for most attacks) or CHA (for ninjutsu). The damage bonus is multiplied by Speed to represent that slower, more solid attacks are able to better benefit from your raw power. Unless otherwise noted, any alterations to an action's Speed also affect the Speed the action's damage bonus is multiplied by; faster isn't always better. Some abilities may add bonus damage, but unless they explicitly say so, this does not affect your stat-based "Damage Bonus."

Damage is done to an opponent's Vitality unless stated otherwise, until that reaches 0. Any overflow, and all future damage, goes straight to their Hit Points.

#### Handseals
The majority of Ninjutsu and Genjutsu techniques have an entry for Seal Speed in their description. Those that don't, and those with a Seal Speed of 0, can be used at will, like regular actions. For the rest, however, they may not be used unless preceded by a Perform Handseals action (see Basic Actions). The jutsu you're using must be used on your next action, at which point its effects are resolved and you, as normal, will determine your next action based on the jutsu's speed.

#### Genjutsu
Genjutsu are the mind-affecting, often-illusionary techniques used by ninja. While they can be potent in some situations, they're difficult to use against experienced ninja. Attempting to influence someone with Genjutsu (whether directly, such as a mental attack, or indirectly, casting an illusion over an area and determining if it fools them) is resolved through a set of opposed Genjutsu rolls.

The 'attacker' rolls 1d20+XP/400, and the 'defender' rolls 1d20+XP/200, both adding any bonuses or penalties they have to Genjutsu and d20 rolls. Some bonuses may apply only to offensive or defensive genjutsu rolls: In these cases, the person using the genjutsu is the 'attacker' and making the 'offensive' roll, and the person trying to avoid being affected is the 'defender' and accordingly making the defensive genjutsu roll. If the defender rolls lower than their opponent, they suffer the effects of the technique being used.

Genjutsu relies upon confusing the senses, which is a powerful tool in the arsenal of someone who relies on subterfuge... or even just a shinobi needing an extra edge in combat. It's quite possible to realize one's under a genjutsu, but that doesn't give any special ability to overcome its effects ("disbelieving the illusion", so to speak, doesn't actually work). On the other hand, it's hard to fool someone again and again with the same trick. Each time a Genjutsu is successfully used against you in combat, you have a (cumulative) +5 bonus to defensive rolls against that specific jutsu for the rest of the battle.

There are three ways to break free from most Genjutsu:
 
 - Genjutsu Kai, the D-rank Ninjutsu Technique.
 - If you suffer a Wound of any severity, all Genjutsu effects applied to you end as your mind gets its act back together.
 - Many Genjutsu will have upkeeps, durations, or the like.  Details will exist in the specific jutsu entries.

By their nature, it's hard to realize that one is suffering from the effects of a Genjutsu technique. It's possible to be afflicted by a genjutsu that you know and use frequently, with obvious 'tells', and still mistake it for reality--such is the nature of delusions. Mechanically, this means that if you fail a genjutsu roll by 5 points or fewer, you realize that you've been afflicted by an illusionary technique; any higher, and you have no reason to suspect that what you're experiencing is anything but reality.

#### Defending
Inevitably, you will at some point be attacked. Accordingly, ninja are trained to defend themselves in a variety of ways. Normally, you may only use a single defense against any given attack.  Like with Attacks, they follow a similar format:

>Shikamaru needs all his teeth to eat Choji's snacks when he isn't looking, and tries to slip under the shadow of the Akimichi's meaty arm for safety! (Dodge, Speed 2)

The most common defenses are Dodge and Parry, but others, such as Block, also exist.  See Basic Actions for the most common defenses.  Abilities and Jutsu can also grant you other defensive options.

#### Partial Success
Just because you failed to evade a shuriken or deflect a sword slash doesn't mean they struck a vital area (you are a ninja, after all). When you make a defensive roll to avoid an attack, for each point you fail by you take 20% damage. Any status effects that are part of the technique, however, will apply normally.

That can be confusing, so, it's example time! So you roll a 14 on your dodge, against an Accuracy 15 attack. You failed by 1 point, so you take 20% of the attack's normal damage. Had you rolled a 12, you would take 60% damage. And, if you had rolled a 7 (failing by 8 points), you would take the full 100% damage.

With regards to defensive jutsu: Partial success typically applies to any jutsu which works similar to a dodge or parry. That is, you make a d20 roll, and if successful the attack you are defending against does not hit you. However, if the technique has another effect (such as make a d20 roll, and if you succeed you reduce the attack's damage by a set amount), partial success does not apply. Exceptions to this will be noted otherwise in the individual technique's description.

#### Damage Reduction
Some effects, such as uniques and clan abilities, provide Damage Reduction (DR). This reduces incoming damage directly: if you have 10 DR, and an attack does 100 damage, you would only take 90 damage from it. Damage Reduction does not apply against status effects.

#### Mitigation Order
As it's inevitable that you will have multiple ways to reduce damage when hit, you apply effects in the following order:
1. Partial Success (as from Dodge, Parry) if applicable
2. Actual DR.
3. Any other static number-based (e.g., "5") reductions in damage (such as Domu).
4. Blocking
5. Any other percent-based (e.g., "10%") reductions of damage.

#### Action Qualities
Some actions operate differently to others, or can be used in special ways that are otherwise distinct.  Below is the most common types of qualities you might see given to certain attacks and defenses to be aware of, though individual jutsu or abilities might list their own unique properties in their individual entries.

#### Action Chains
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

#### Interrupt
Being able to interrupt is a special quality certain abilities and techniques have, which allows them to be performed in response to another action, generally an attack directed at the user; for example, most defensive jutsu have this quality.

You may use an interrupt if the Speed of the interrupt (and in the case of ninjutsu, Speed + modified Seal Speed) is half or less that of the action you're interrupting. This is one instance where you may use a ninjutsu with handseals without having performed the handseals as a prior action.

The Speed (not, in the case of ninjutsu, counting Seal Speed) of the interrupt is added to your next action on the IC. Actions used as Interrupts with base Speeds of 3 or below may still be reduced to half (rounded up) of their base speed (normally, an action with a base Speed of 3 or lower cannot have its Speed reduced further).

#### Delay
Delay is not, properly speaking, an action in and of itself, but rather a quality certain actions have. For an example of how this might be written, an attack could have "Speed 12, Delay 4". This means that while it would be declared normally on your turn, its effects would take place 4 initiative counts later. The action may be aborted any time up to the last IC of the delay.

For example, using the above attack on IC 10, you would have until IC 14 to abort; on IC 14 itself, so long as you did not abort the attack's effects would be resolved normally, and you would then act again on IC 22. An action's Speed may not be reduced below its Delay, and the Delay quality itself can not be lowered by AP or any other means, unless the effect in question specifically states otherwise.

#### Abort *(Speed 1 or Speed +1)*
Certain actions will say they can be aborted, or just list "Abort" as one of their qualities along with Speed (such as the Perform Handseals action). Aborting may declared on any initiative count before your next action, allowing you to act on the following IC. When you abort an action, you stop performing it; exactly what this entails will usually be discussed in the individual actions. Alternately, you may choose to Abort as part of an Interrupt--for example, aborting handseals so you can perform a defensive ninjutsu technique. This adds 1 to the Speed of that Interrupt.

#### Variable Speed Actions *(Speed Variable)*
Not to be confused with the above <i>(Speed Variable)</i> entry itself, Variable Speed Actions are those such as Block, and several abilities you can acquire with EXP (notably Guard and Total Defense), along with some specific jutsu which explicitly state they are Variable Speed Action.  These actions do not have a set Speed, and instead you can declare their Speed to be whatever you wish: You could Block for 2 IC if you know your opponent is about to finish handseals and you want to prepare for a nasty attack, or for 20 IC if your opponent is hidden and you just want to let them plink away with ranged weapons while they make themselves easier to spot. Variable Speed actions typically come with the Abort property (meaning you can cancel them earlier than you initially declared, see Abort, above), though some specific instances might disallow this (forcing you to commit to doing it), and most simply give you a unique option you can choose to perform, not a requirement: When Blocking you can still Dodge if you wish, but you also have the Block defense available to you (at 'Speed 0').

#### Willpower
Ninja are capable of incredible feats, and some are truly exceptional, performing astonishing deeds in the face of adversity. While you can be as determined (or not) as you please, Willpower represents your ability to use that determination to push yourself above and beyond your limits.

You can spend Willpower any time you attack, or make a d20 roll, after you've seen the action's normal results. When you spend a point of Willpower, reroll whichever roll it was used on (or, in the case of an attack, make an Accuracy Roll). If the d20 result is less than 11, add 10 to it; this is your new result for that action. Willpower may not, however, be used to reroll Stamina or Chakra Exhaustion rolls.

You may also choose to spend Willpower after someone else has done so to alter the result of their action. However, any given roll or attack may only have Willpower applied to it one time.

#### d20 rolls
Some effects give bonuses to 'd20 rolls' as a generic benefit.  It can be confusing as to what they do or do not apply to, so for clarity, they apply to the following: 
- Defensive Rolls
- Skill Rolls
- Genjutsu Rolls
- Grapple Rolls

Which means this type of bonus **does not** apply to Accuracy (whether rolled, or as a TN), Fatigue rolls, or damage rolls which might happen to utilize a d20 for their damage dice. Generally speaking, they should apply to all bonuses which aren't those types, but check with a GM if you are uncertain.


## Basic Actions

These are actions that anyone can do in combat, and the rules associated with them.

#### Basic Unarmed *(Speed 8, Stamina 5)*
The simplest form of attack, this is a catch-all for punches, kicks, and any other attack which uses your body to cause harm to your opponent. This deals 2d4 base damage.

#### Basic Attack: Weapon *(Speed Variable, Stamina Variable)*
This is any ordinary attack with a weapon, from throwing shuriken to swinging oversized swords.  The base damage, speed, and stamina cost of using a weapon is listed in its entry, and they can all be found in the Equipment section.

#### Block *(Speed Variable)*
As an action, you may declare that you are blocking, and state a Speed for the action. Until your next action, you may use the Block defense (see 'Defending' below) against any incoming attacks.

#### Move *(Speed Variable, Abort)*
For the most part, ninja can move faster than ordinary people. When you actually devote time to moving in battle, you travel (AGI)*(number of IC spent moving)/50 yards.

Sometimes you may need to close the distance and attack an opponent all at once. When attacking, you may move towards your opponent a distance corresponding to half your attack's Speed, for free. Thus, if you needed to rush an enemy and throw a punch at them, and had 25 AGI, as a Speed 8 action you could move up to (25*(8/2)/50) = 2 yards and then use a basic unarmed attack.

Movement is unique, in that you cannot use Action Points to reduce its Speed. Your distance traveled is determined by the actual number of IC spent on movement.

#### Multi-Throw *(Speed Variable, Stamina Variable)*
Anyone familiar with fictionalized depictions of ninja has no doubt seen them flinging a handful of shuriken with pinpoint aim. As this game is about fictional ninjas, it stands to reason that they can do this! The term, appropriately enough, is "Multi-Throwing".

It helps to first be familiar with the two weapons you'll be throwing the most: They are the shuriken (weighing in at 1d6 base damage) and the kunai (beating it out with 2d6). While you could certainly throw a single shuriken or kunai (that would be a basic weapon attack), a real ninja would throw a bunch at once. By default, you may only throw one type of weapon at once; you could throw 6 shuriken, but not 4 shuriken and 2 kunai in the same action. After choosing your weapon, you decide how many you want to throw.

You throw at least 2 weapons, up to a maximum of DEX/10. The Speed is 3 + (number of weapons thrown)/2, and the Stamina cost is 5, +1 for every 2 weapons (6 for 2-3, 7 for 4-5, and so forth). Regardless of how many weapons you throw, the minimum total Speed of a multi-throw action is 5--this applies to both its base Speed, and its final Speed after any changes (such as spending AP). The rolled damage is the total for all weapons thrown; 6 shuriken would yield a 6d6 base damage. Your damage bonus is increased by +0.5 for every thrown weapon. So, if you had 60 STR in the above multi-throw, your damage bonus would be (60/15 = 4, 4 + 0.5x6 = 4+3 =) 7. The attack would be Speed (3 + 6/2 =) 6 and Stamina 8, and have a damage formula of: 6d6+7x6. If you are multi-throwing shuriken, their +2 Accuracy is applied only once. You do need to choose between shuriken or kunai when you multi-throw; you can't mix-and-match, tragically. Because wounds represent severe damage from a single powerful attack, and multi-throws are multiple weaker injuries delivered at once, the severity of all wounds caused by multi-throws is reduced by one category, to a minimum of Minor.

#### Perform Handseals *(Speed Variable, Abort)*
Most Ninjutsu and Genjutsu techniques require the use of handseals, specialized hand signs that direct and mold the flow of chakra. Representing this, those jutsu have a Seal Speed listed in their description. That number, minus your DEX/10, gives you the modified seal speed, which is the Speed of your Perform Handseals action. However, other speed-reducing effects do not apply to Perform Handseals. A Seal Speed of 0 means that while handseals are required, you can perform them so fast that the time required is negligible. You may forego part, or all, of your DEX/10 reduction of Seal Speed if you wish (for example, with 40 DEX you could use Perform Handseals action for a Seal Speed 10 jutsu at anywhere between Speed 6 and Speed 10, as you pleased).

Handseals require the use of both hands, and if they're interrupted for any reason you have to start over again. Although you don't have to declare what technique you're performing the handseals for when you start, all techniques have their own, unique combination of seals to perform them; this means that if you changed your mind partway through a Perform Handseals action, you'd need to start a new one.

If you take damage while forming handseals (between the declaration of your Perform Handseals action and when you actually use the jutsu), you must exceed 10 + (damage dealt / 10) on a Chakra Control skill roll in order to continue. Failure means you automatically Abort your Perform Handseals action.

#### Rest *(Speed 10)*
Resting is pausing to cool down and gather your breath. Since it doesn't directly lead to incapacitating your enemy, most ninja prefer to do this out of battle; however, sometimes pacing yourself is the only way to achieve victory. Every Rest action you take reduces your Stamina penalty (see the 'Fatigue' portion of this chapter) by 1, to a minimum of 0. You cannot use AP to reduce the speed of your Rest action; 'resting as fast as you can' is, after all, something of an oxymoron.

#### Take the Hit *(Speed 6, Interrupt)*
Taking the hit is the glorious move the stronger person or sensei uses to protect their weaker ally! You make a Dodge roll with a +5 bonus; if successful, you've leapt in the way of an attack aimed at your ally. If you fail, your ally takes 20% of the damage per point you failed by. (For example: If you fail by 2 points, you'd take 60% damage, and your ally 40% damage). If you were blocking when you used this, you may block as long as you were successful by 1 point or more. You may also use interrupts to defend yourself, up to a maximum Speed of how many points your Take The Hit roll beat the opponent's accuracy; you can't dodge, but you could parry, or use a ninjutsu-based defense that raises a protective wall.




## Stealth
## Pursuit
## Conditions and Status Effects
## Fatigue
## Wounds
## Recovery
## Weather Conditions


