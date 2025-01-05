---
title: Arcane Archer Rework
subtitle: homebrew update
date: 2025-01-04
tags: ["homebrew", "D&D"]
---

Of the Fighter subclasses, the Arcane Archer might have one of the most defined themes: the archer with an arsenal of magical ‘trick’ arrows at their disposal. However, due to the subclass’s mechanical execution in D&D 5e, I have almost never seen or heard of anyone actually using it. In this article, I’ll be breaking down why it is so mechanically lackluster, and then creating a homebrew version that should be able to (be equivalent to other fighter subclasses).

## Why does it need revision?
The core mechanic of the Arcane Archer revolves around Arcane Shots, magical effects that you can use to enhance your attacks. In this respect, it has some parallels with the Battlemaster, one of the most popular Fighter subclasses. Both have subclass-granted resources that allow your character to apply additional effects when they land their attacks. However, compared to the 'superitority dice' of the Battlemaster, the Arcane Shots have
- Too Few Uses
- Too Few Options Known
- Low Power Level of Options (With One Exception)
- Poor Scaling Overall
### Too Few Uses
Like Maneuvers from the Battlemaster, Arcane Shots have a limited number of uses, which are regained on a short or long rest. However, while Maneuvers start at four uses, gaining additional ones at levels 7 and 15, Arcane Shots start at *two* uses, and *never gain more*.
### Too Few Options Known
There are eight Arcane Shots available for Arcane Archers to choose from. (Battlemasters got to choose from 16 Maneuvers in the Player’s Handbook (2014), and Tasha’s Cauldron of Everything added seven more.) However, there is a specific reason why there are only eight: each Arcane Shot is inspired by one of D&D’s eight schools of magic. Thus, I don’t feel the need to add more Arcane Shot options. 

Instead, the problem is how many Arcane Shots an Arcane Archer gets to learn when they gain the subclass. They gain two Arcane Shots, learning an additional one at levels 7, 10, 15, and 18. Battlemasters, on the other hand, start with three Maneuvers, and learn an additional *two* at levels 7, 10, and 15.

One could argue that the Arcane Shots, which can do things like banish a target for a round or fly around corners, are more impactful than Maneuvers, and thus the Arcane Archer should have fewer uses and options. I agree that sometimes the Arcane Shots can be more impactful, but I think limiting the number of options is not the way to balance the power level of the options. As for the number of uses, Arcane Shots in my homebrew version will still be more limited than Maneuvers.

### Power Level of Options
Most of the Arcane Shot options add a little damage for free, and apply an additional effect. While some of the Arcane Shots can do things that no other effect in the game can do, the execution is often underwhelming. Half of the Arcane Shots are save-or-suck, meaning that on a successful save, no additional effect occurs at all. While this might be acceptable given that the effect is applied on an attack roll, which has theoretically also done some damage, it results in options which are not very impactful. 

The one exception to this is Grasping Arrow. It has no saving throw against its effect, instead requiring an action by the affected creature to attempt to remove it via an Athletics check (which could fail, resulting in a wasted action). It also does additional damage every turn where the affected creature moves. With the prevalence of forced movement options in 5e, especially post-Tasha’s, this will be very easy for other party members to trigger, even without the creature having to move on its turn.

So to fix the power level, some other arrows will be getting an upgrade, and Grasping Arrow will be brought in line.

### Poor Scaling Overall
We’ve already identified how Arcane Archers never getting more than two Arcane Shot uses is poor scaling, but the subclass also falters in other ways. The additional damage from Arcane Shots starts at 2d6 for most of the options, but never increases until level 18, when it increases to 4d6.

2d6 is pretty good damage at 3rd level, considering it is added to the damage the attack is already doing, but it falls off after a few levels. By 18th level, 2d6 is hardly anything, and doubling it to 4d6 feels like too little, too late. Scaling at earlier levels, like the Battlemaster’s Superiority Dice (used to calculate, among other things, extra damage done by Maneuvers), will help address this.

In addition, the Arcane Archer has no new subclass features at level 10 or 18. Instead, its existing features merely scale at this level. Battlemaster is similar. However- and this is just my opinion- I think that is kind of boring. These kinds of subclasses, with their core feature at level 3, are already front-loaded. To reward players for sticking with the subclass, I’ll add meaningful features at levels 10 and 18.

### Goals for Revision:
- Increase number of uses of Arcane Shots
- Increase number of known Arcane Shots
- Adjust balance of Arcane Shot options
- Scale damage of Arcane Shot options
- Add subclass feature at 10th and 18th

## Revision Time
My general philosophy for homebrew revisions of existing material is to not change anything without a reason. So I’ll be leaving much of the subclass alone, including what the Arcane Shot options are- I see no reason to alter the ‘eight options inspired by the schools of magic’ gimmick. 

I’ll go feature by feature, displaying the old version and my revised one below. Here we go!

### Level 3
___
Original Feature: **Arcane Archer Lore**

At 3rd level, you learn magical theory or some of the secrets of nature — typical for practitioners of this elven martial tradition. You choose to gain proficiency in either the Arcana or the Nature skill, and you choose to learn either the *prestidigitation* or the *druidcraft* cantrip.
___
Well, not a very dramatic start. This is a ribbon feature (a feature intended to provide flavor or theming, but not major mechanical impact) and I see no reason to change it.


___
Original Feature: **Arcane Shot**

At 3rd level, you learn to unleash special magical effects with some of your shots. When you gain this feature, you learn two Arcane Shot options of your choice (see “Arcane Shot Options” below).

Once per turn when you fire an arrow from a shortbow or longbow as part of the Attack action, you can apply one of your Arcane Shot options to that arrow. You decide to use the option when the arrow hits a creature, unless the option doesn’t involve an attack roll. You have two uses of this ability, and you regain all expended uses of it when you finish a short or long rest.

You gain an additional Arcane Shot option of your choice when you reach certain levels in this class: 7th, 10th, 15th, and 18th level. Each option also improves when you become an 18th-level fighter.
___

As far as I can tell, the only reason Arcane Archers are restricted to using bows is game tradition, or perhaps aesthetics. I think it would be quite cool to have an Arcane Crossbowman, or an Arcane Slinger, or even an Arcane Blowgun-user. In my revision, I change the wording to allow that, though I do specify ‘simple or melee ranged weapon’ to avoid allowing unforseen interactions with non-standard ranged weapons (such as Armorer Artificer’s Lightning Launcher).

___
Revised Feature: **Arcane Shot**

At 3rd level, you learn to unleash special magical effects with some of your shots. When you gain this feature, you learn <u>three</u> Arcane Shot options of your choice (see “Arcane Shot Options” below).

Once per turn when you <u>fire ammunition from a simple or martial ranged weapon</u> as part of the Attack action, you can apply one of your Arcane Shot options to that <u>ammunition</u>. You decide to use the option when the <u>ammunition</u> hits a creature, unless the option doesn’t involve an attack roll. You have <u>three</u> uses of this ability, and you regain all expended uses of it when you finish a short or long rest. <u>You gain an additional use of this ability at level 7, and another additional use at level 15.</u>

You gain an additional Arcane Shot option of your choice when you reach certain levels in this class: 7th, 10th, and 15th level. <u>At 18th level, you gain all remaining options. Each option also improves when you reach 10th level in this class, and again at 18th level.</u>
___

When Arcane Archers would start with two options, they would eventually learn six out of the eight Arcane Shots. Starting with three, they would learn seven out of eight, and it seemed silly that they could learn all but one, so I decided that they would learn all eight at level 18. If you think that gives them too many options, I will remind you that wizards can cast Wish at this level, which grants them access to any spell of 8th level or lower, and so I think the humble Fighter is fine to learn all eight of the Arcane Shots.

### Level 7
___
Original Feature: **Magic Arrow**

At 7th level, you gain the ability to infuse arrows with magic. Whenever you fire a nonmagical arrow from a shortbow or longbow, you can make it magical for the purpose of overcoming resistance and immunity to nonmagical attacks and damage. The magic fades from the arrow immediately after it hits or misses its target.
___

We have seen features like this on several classes and subclasses, such as Monk and Circle of the Moon Druid. It allows a character to deal full damage to a creature when that creature might otherwise resist the non magical damage. I see no reason to change it, except to allow it to work with any ammunition.

___
Revised Feature: **Magical Ammunition**

At 7th level, you gain the ability to infuse <u>ammunition with magic</u>. Whenever you fire nonmagical <u>ammunition from a simple or martial ranged weapon</u>, you can make it magical for the purpose of overcoming resistance and immunity to nonmagical attacks and damage. The magic fades from the <u>ammunition</u> immediately after it hits or misses its target.
___

___
Original Feature: **Curving Shot**

At 7th level, you learn how to direct an errant arrow toward a new target. When you make an attack roll with a magic arrow and miss, you can use a bonus action to reroll the attack roll against a different target within 60 feet of the original target.
___

The wording of this feature is unnecessarily specific. Why say ‘an attack roll with a magic arrow’ when the previous feature causes all of your arrows to be considered magical? In my revision, I will simplify the wording to allow it to work with attacks using any ranged weapon.
___
Revised Feature: **Curving Shot**

At 7th level, you learn how to direct an errant <u>attack</u> toward a new target. When you make an attack roll with a <u>ranged weapon</u> and miss, you can use a bonus action to reroll the attack roll against a different target within 60 feet of the original target.
___

### Level 10

At level 10, the original Arcane Archer doesn't have any actual subclass features. Instead, Arcane Shot scales. Not by much, however; all you get is one additional Arcane Shot option known. Instead, the next actual class feature they get comes at level 15.
___
Original Feature: **Ever-Ready Shot**

Starting at 15th level, your magical archery is available whenever battle starts. If you roll initiative and have no uses of Arcane Shot remaining, you regain one use of it.
___

This is another kind of feature that is fairly common at high levels in classes and subclasses. Battlemaster’s level 15 feature, Relentless, grants one superiority dice when the fighter starts initiative with none. Bards and Monks each have a capstone that grants a class resource when they roll initiative with none. 

However, I generally have a low opinion of these features. Once characters get past the first few levels of play, they rarely roll initiative with no resources, and at 20th level that happens pretty much never. However, characters might still roll initiative while having spent some but not all of their resources, and so with some alteration Ever-Ready Shot can still be useful. I am basing the revision to Ever-Ready Shot off of Superior Bardic Inspiration and Perfect Focus, the old capstones to Bard and Monk that have been revised for the 2024 Player’s Handbook. Both of those features now work when the character is at low resources but not necessarily zero resources, and have each been moved to earlier levels.

Given that Arcane Archer doesn’t have a defined level 10 subclass feature, and Ever-Ready Shot less of a *power* increase than a *reliability* increase, I decided to move it from level 15 to level 10.
___
Revised Feature: **Ever-Ready Shot**

Starting at 10th level, your magical attacks are available whenever battle starts. If you roll initiative and have fewer than two uses of Arcane Shot remaining, you regain uses until you have two.
___

That’s all the existing Arcane Archer features! Time to create brand new features for level 15 and 18.

### Level 15

The feature I came up with for level 15 is inspired by one of the magic arrow items from Baldur’s Gate 3. (Honestly, the whole game has so many cool magic arrows that you could feel like an Arcane Archer while playing one of the base game subclasses). That item is the Arrow of Transposition. Fire it, and you teleport to where it has landed. That sort of blend of magic and archery feels right on them for the Arcane Archer.

___
New Feature: **Repositioning Shot**

Starting at 15th level, when you take the Attack action on your turn, you can replace two of the attacks with a use of Repositioning Shot. When you do, you teleport up to 60 feet to an unoccupied space you can see that isn’t behind total cover, provided you have a ranged weapon in hand. You have a number of Repositioning Shots equal to your proficiency bonus, and regain all uses when you finish a long rest.
___

### Level 18

At level 18, other classes already have their 9th level spells. Wizards are casting Wish, Clerics are healing the party for 700 hit points with Mass Heal, and Druids are turning into angels or dragons with Shapechange. In terms of power level, we have a lot of leeway when comparing to other classes. 
With Arcane Archer, throughout the lower levels we’ve constantly had to be mindful of how many Arcane Shot uses we had remaining. Ever-Ready Shot and the additional uses at levels 7 and 15 have helped with that, but nonetheless there are many times when an Arcane Archer will have run out of Arcane Shots entirely. Now, at 18th level, that can become a problem of the past with Effortless Shot.

___
New Feature: **Effortless Shot**

Starting at 18th level, you may use Arcane Shot twice per turn instead of once. The first time you use Arcane Shot each turn, it doesn’t expend one of your uses of Arcane Shot.
___

## Arcane Shot Option Revision

Now that we’ve finished the class features, it is time to revise the balance of the individual Arcane Shots.


The first thing I’m revisiting is the additional damage (2d6) that many of the shots deal when they hit. Of the 2014 Fighter subclasses, the Battlemaster, the Arcane Archer, and the Psi Knight each have a subclass resource (superiority dice, Arcane Shot uses, and Psionic Energy dice, or ‘psi dice’) that allows them to add damage to an attack, usually with extra effects. If each subclass uses its resources purely for damage against a single target, here are the results of the damage totals. (Assume the Psi Knight has a +2 Intelligence modifier).

There are other factors to each subclass besides damage, such as what the additional effects are, what ability score the DC for the additional feature is based on (Battlemaster uses Strength or Dexterity, the other two use Intelligence), how often the resource can be used (Battlemaster can use dice on any attack, the other two are limited to once per turn), or what else the resource can be used for. However, even greatly simplified, it should be obvious that the Arcane Archer is always behind on damage from this metric.

Average damage of subclass resouces at different levels
| Level: | B.M. | A.A. | P.K. | A.A., add uses | A.A, add uses and scaling |
| :------ | :---| :--- | :--- | :--- | :--- |
| 3rd level: | 18 (4d8) | 14 (4d6) | 22 (4d6+8) | 21 (6d6) | 21 (6d6) |
| 7th level: | 22 (5d8) | 14 (4d6) | 39 (6d8+12) | 28 (8d6) | 28 (8d6) |
| 10th level: | 27 (5d10) | 14 (4d6) | 52 (8d8+16) | 28 (8d6) | 42 (12d6) |
| 15th level: | 33 (6d10) | 14 (4d6) | 75 (10d10+20) | 35 (10d6) | 52 (15d6) |
| 18th level: | 39 (6d12) | 28 (8d6) | 102 (12d12+24) | 70 (20d6) | 70 (20d6) |

After adding the extra uses our revision granted the Arcane Archer, the damage total improved but still eventually fell behind the Battlemaster, and way behind the Psi Knight.
Finally, after adding the damage from scaling the dice at level 18, with an intermediate step at level 10, the damage curve fell to a satisfactory place between Battlemaster and Psi Knight. The reason I wanted the total damage higher than Battlemaster, is because the Battlemaster has the advantage of being able to use all of its Superiority dice resources in one round, and doesn’t have to rely on a secondary ability score for DC. The reason I wanted the damage to remain less than the Psy Knight is because the Arcane Archer has more varied, and more potent, secondary effects besides damage.

Next, the details of each individual shot!

### Banishing Arrow

___
Original Wording:

You use abjuration magic to try to temporarily banish your target to a harmless location in the Feywild. The creature hit by the arrow must also succeed on a Charisma saving throw or be banished. While banished in this way, the target’s speed is 0, and it is incapacitated. At the end of its next turn, the target reappears in the space it vacated or in the nearest unoccupied space if that space is occupied.

After you reach 18th level in this class, a target also takes 2d6 force damage when the arrow hits it.
___

Banishing Shot is pretty good. It duplicates, for one round, the Banishment spell, which is a 4th-level spell. If the target fails, it automatically breaks their concentration and skips their turn. I don’t think this one actually needs adjustment, except that the target takes 1d6 force damage when hit if the fighter is 10th level or higher, before increasing to 2d6 at 18th. While Banishment is a higher-level spell than what the rest of the Arcane Shot options compare to, by lasting only 1 round it loses the main advantage of the Banishment spell: completely taking a creature out of the fight for multiple rounds.

___
Revised Wording:

You use abjuration magic to try to temporarily banish your target to a harmless location in the Feywild, or another plane of your choosing. The creature hit by the arrow must also succeed on a Charisma saving throw or be banished. While banished in this way, its speed is 0, and it is incapacitated. At the end of its next turn, the target reappears in the space it vacated or in the nearest unoccupied space if that space is occupied.

<u>After you reach 10th level in this class, a target also takes 1d6 force damage when the arrow hits it, and</u> once you reach 18th level in this class, the extra damage increases to 2d6.
___

### Beguiling Arrow
___
Original Wording:

Your enchantment magic causes this arrow to temporarily beguile its target. The creature hit by the arrow takes an extra 2d6 psychic damage, and choose one of your allies within 30 feet of the target. The target must succeed on a Wisdom saving throw, or it is charmed by the chosen ally until the start of your next turn. This effect ends early if the chosen ally attacks the charmed target, deals damage to it, or forces it to make a saving throw.

The psychic damage increases to 4d6 when you reach 18th level in this class.
___

Beguiling Arrow is pretty bad. Wisdom saves are one of the more commonly resisted saving throws, and many creatures are straight-up immune to being charmed. In addition, even if the target fails the saving throw, nothing stops them from simply attacking one of your other allies, or even you.

Let’s look at some other single-target enchantment spells for ideas about what else this arrow could do. Since we start at level 3, I’ll look at 2nd-level spells, which first become available at level 3. As it turns out, there is a single-target, one-round, 2nd-level enchantment spell: *Tasha’s Mind Whip*! If we base our new Beguiling Shot on this spell, many of our problems our solved: the saving throw becomes Intelligence, which monsters tend to be either pretty bad or pretty good at, and immunity to charm doesn’t do anything against it. We will adjust the damage from 3d6 psychic to 2d6 psychic to bring it in line with our other options.

___
Revised Wording:

Your enchantment magic causes this arrow to temporarily beguile its target. The creature hit by the arrow takes an extra 2d6 psychic damage, and <u>must make an Intelligence saving throw. On a failed save, the creature can’t take a reaction until the end of its next turn, and on its next turn, it must choose whether it gets a move, an action, or a bonus action; it gets only one of the three. On a successful save, a creature suffers no additional effect.
</u>
The psychic damage increases to <u>3d6 when you reach 10th level in this class, and 4d6 once you reach 18th level in this class.</u>
___

### Bursting Arrow

___
Original Wording:

You imbue your arrow with force energy drawn from the school of evocation. The energy detonates after your attack. Immediately after the arrow hits the creature, the target and all other creatures within 10 feet of it take 2d6 force damage each.

The force damage increases to 4d6 when you reach 18th level in this class.
___

Bursting Arrow is… fine. The damage isn’t great, but there is no saving throw and the damage type is very reliable. None of the options from the other subclasses we are comparing to have an AOE effect to reference, so let’s calculate the total damage the arrow will usually deal. Based on the Targets in Areas of Effect table, a 10-foot radius will on average be able to hit two creatures. We’ll assume that one of those creatures is the target of the arrow. That means that the arrow will deal a total of 4d6 damage. This does more damage than the other arrows, but it is multi-target, and since spreading a given amount of damage across multiple targets instead of one target is worse in D&D, I think it could use a buff. Let’s make it 3d6 to start- it will increase to 4d6 at level 10, and 5d6 at level 18. That means that at level 3 we are doing 6d6 split across multiple targets (plus the attack damage against one target). If this sounds high, compare it to Shatter, a 2nd-level spell that does, on average, 6d8 across two targets, and is accessible at level 3. 

I considered adding a saving throw for half damage, but adding a saving throw to this effect would reduce its effectiveness compared to all the other Arcane shots (except Seeking and Piercing), which do their extra damage with no saving throw. Not to mention, it was originally printed without a saving throw, and I’m trying to change as little as possible while leaving things balanced.

___
Revised wording:

You imbue your arrow with force energy drawn from the school of evocation. The arrow detonates after your attack. Immediately after the arrow hits the creature, the target and all other creatures within 10 feet of it take <u>3d6</u> force damage.

The force damage increases to 4d6 when you reach <u>10th level in this class, and 5d6 when you reach 18th level in this class.</u>
___

### Enfeebling Arrow

___
Original wording:

You weave necromantic magic into your arrow. The creature hit by the arrow takes an extra 2d6 necrotic damage. The target must also succeed on a Constitution saving throw, or the damage dealt by its weapon attacks is halved until the start of your next turn.

The necrotic damage increases to 4d6 when you reach 18th level in this class.
___

Enfeebling Arrow is also not impressive. Monsters are most likely to have strong Constitution saves, necrotic damage is not super reliable, and the damage-halving from weapon attacks won’t always come up.

That said, we probably don’t need to do a complete overhaul. Enfeebling Arrow has a similar effect to Ray of Enfeeblement, a 2nd-level spell, so the power level of the effect should be about right. One thing, though- Ray of Enfeeblement only allows a saving throw to end the effect, otherwise the damage-halving is automatic once you hit. So let’s remove the saving throw from Enfeebling Arrow, since the effect will last just one round anyway. I’m also going to allow the ability to affect all attacks, not just weapon attacks, to make it less situational. Since that leaves this still just a little lackluster in my eyes, I’ll add the anti-healing clause from Chill Touch.

___
Revised wording:

You weave necromantic magic into your arrow. The creature hit by the arrow takes an extra 2d6 necrotic damage, <u>and the damage dealt by its attacks is halved until the start of your next turn. In addition, the target cannot regain hit points until the start of your next turn.</u>

The necrotic damage increases to <u>3d6 when you reach 10th level in this class,</u> and 4d6 when you reach 18th level in this class.
___

### Grasping Arrow

___
Original wording:

When this arrow strikes its target, conjuration magic creates grasping, poisonous brambles, which wrap around the target. The creature hit by the arrow takes an extra 2d6 poison damage, its speed is reduced by 10 feet, and it takes 2d6 slashing damage the first time on each turn it moves 1 foot or more without teleporting. The target or any creature that can reach it can use its action to remove the brambles with a successful Strength (Athletics) check against your Arcane Shot save DC. Otherwise, the brambles last for 1 minute or until you use this option again.

The poison damage and slashing damage both increase to 4d6 when you reach 18th level in this class.
___

Grasping Arrow is… weird. It is the only Arcane Shot option that lasts longer than one round, and unlike every other option except for the original Bursting Arrow, there is no saving throw to avoid the additional effect. This is probably because, by itself, Grasping Arrow isn’t that great. But when you start combining it with forced movement, it becomes quite good. As Chris from the YouTube channel Treantmonk’s Temple points out in his video about the Arcane Archer, forced movement has become very common in D&D, to the point where it isn’t that difficult for every character in the party to have some kind of forced movement. That’s potentially an extra 2d6 damage each turn. 

To make matters worse, the affected monster must use their action to attempt to escape from the effect, as opposed to a repeated saving throw. This means that they have a chance of doing absolutely nothing on their turn if they attempt the check and fail.

In light of these issues, we have a lot of changes to make. First step is to bring back the one-round duration and saving throw. Next, we’re going to replace the strange, exploitable damage-upon-movement clause and movement speed reduction with an alternate effect. Looking at other effect in D&D that summon vines and brambles, we often see the restrained condition occur, such as in the Entangle Spell, the Ensnaring Strike spell, and the Oath of Ancients Paladin’s ‘Nature’s Wrath’ option for Channel Divinity. Let’s use that.

While we’re comparing this to Ensnaring Strike, let’s change the damage type to piercing. Poison is the most unreliable damage type, and I want all the Arcane Shots to be on a mostly even playing field.

___
Revised wording:

When this arrow strikes its target, conjuration magic creates grasping brambles which wrap around the target. <u>The creature hit by the arrow takes an extra 2d6 piercing damage, and must make a Strength saving throw. On a failure, it is restrained until the start of your next turn.

The extra damage increases to 3d6 when you reach 10th level in this class, and 4d6 when you reach 18th level in this class.</u>
___

### Piercing Arrow
___
Original wording:

You use transmutation magic to give your arrow an ethereal quality. When you use this option, you don’t make an attack roll for the attack. Instead, the arrow shoots forward in a line, which is 1 foot wide and 30 feet long, before disappearing. The arrow passes harmlessly through objects, ignoring cover. Each creature in that line must make a Dexterity saving throw. On a failed save, a creature takes damage as if it were hit by the arrow, plus an extra 1d6 piercing damage. On a successful save, a target takes half as much damage.

The piercing damage increases to 2d6 when you reach 18th level in this class.
___

While there aren’t any other effects that let you attack through cover in D&D 5e (even Psychic Lance is blocked by total cover), I expect that will be a use of this feature that comes up relatively rarely, so instead I am going to treat it like a normal Area of Effect. 

According to the Targets in Areas of Effect table, a 30-foot line can be expected to include one creature. However, I expect that usually a player would only use a line if they could hit two or more creatures with it. Thus I am going to treat our Piercing Shot as being expected to include two creatures in the area. 

Our new version of the other Arcane Shot option that hits an area, Bursting Shot, can be expected to deal 6d6 + one instance of weapon damage total. Piercing shot as written, deals 2d6 + two instances of arrow damage. Assuming ‘weapon damage’ is about 1d8+4 (average longbow damage dice + Dexterity at level 4), here are the expected damages for each, assuming all targets fail saving throws.

Revised Bursting Shot: 21 (6d6) + 7 (1d8+4) = 28

Original Piercing Shot: 7 (2d6) + 7 (1d8+4) + 7 (1d8+4) = 21

Revised Piercing Shot: 14 (4d6) + 7 (1d8+4) + 7 (1d8+4) = 28

By returning the original bonus damage to 2d6, we can put the two about on par. Bursting Shot will be easier to catch two creatures with, but Piercing Shot has the additional ability to go through cover.
And as always, we are altering the damage progression to our new, revised one.

___
Revised wording:

You use transmutation magic to give your arrow an ethereal quality. When you use this option, you don’t make an attack roll for the attack. Instead, the arrow fires forward in a line, which is 1 foot wide and 30 feet long, before disappearing. The arrow passes harmlessly through objects, ignoring cover. Each creature in that line must make a Dexterity saving throw. On a failed save, a creature takes damage as if it were hit by the arrow, plus an extra <u>2d6</u> piercing damage. On a successful save, a target takes half as much damage.

The piercing damage increases to <u>3d6 when you reach 10th level in this class, and</u> 4d6 when you reach 18th level in this class.
___

### Seeking Arrow
___
Original wording:

Using divination magic, you grant your arrow the ability to seek out a target. When you use this option, you don’t make an attack roll for the attack. Instead, choose one creature you have seen in the past minute. The arrow flies toward that creature, moving around corners if necessary and ignoring three-quarters cover and half cover. If the target is within the weapon’s range and there is a path large enough for the arrow to travel to the target, the target must make a Dexterity saving throw. Otherwise, the arrow disappears after traveling as far as it can. On a failed save, the target takes damage as if it were hit by the arrow, plus an extra 1d6 force damage, and you learn the target’s current location. On a successful save, the target takes half as much damage, and you don’t learn its location.

The force damage increases to 2d6 when you reach 18th level in this class.
___

There aren't really any analogous effects to compare Seeking Arrow to in D&D 5e. Even spells like Psychic Lance that don’t require you to see their target don’t pass around corners. Given the lack of things to compare to, and this Arcane Shot’s excellent thematic concept, I am going to leave it alone except for one thing. I’m going to change the damage back to the normal progression, to place this Arcane Shot option on equal footing with the others.

___
Revised wording:

Using divination magic, you grant your arrow the ability to seek out your target, allowing the arrow to curve and twist its path in search of its prey. When you use this option, you don’t make an attack roll for the attack. Instead, choose one creature you have seen in the past minute. The arrow flies toward that creature, moving around corners if necessary and ignoring three-quarters cover and half cover. If the target is within the weapon’s range and there is a path large enough for the arrow to travel to the target, the target must make a Dexterity saving throw. On a failed save, it takes damage as if it were hit by the arrow, plus an extra <u>2d6</u> force damage, and you learn the target’s current location. On a successful save, the target takes half as much damage, and you don’t learn its location.

<u>The force damage increases to 3d6 when you reach 10th level in this class, and increases to 4d6 when you reach 18th level in this class.</u>
___

### Shadow Arrow
___
Original wording:

You weave illusion magic into your arrow, causing it to occlude your foe’s vision with shadows. The creature hit by the arrow takes an extra 2d6 psychic damage, and it must succeed on a Wisdom saving throw or be unable to see anything farther than 5 feet away until the start of your next turn.

The psychic damage increases to 4d6 when you reach 18th level in this class.
___

I don’t understand why this Arcane Shot doesn’t just give the blinded condition. Preventing a creature from seeing anything further than 5 feet away is quite similar to imposing blindness, and Imposing the blindness condition is about the power of a 2nd-level spell, which meets our power criteria. 

___
Revised wording:

You weave illusion magic into your arrow, causing it to occlude your foe’s vision with shadows. The creature hit by the arrow takes an extra 2d6 psychic damage, and it must succeed on a Wisdom saving throw or be <u>blinded</u> until the start of your next turn.

The psychic damage increases to <u>3d6 when you reach level 10 in this class,</u> and 4d6 when you reach 18th level in this class.
___

And we're done!
