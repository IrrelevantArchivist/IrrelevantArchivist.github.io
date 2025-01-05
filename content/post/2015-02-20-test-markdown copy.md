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




Here's a useless table:
 
| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |
 

Here's a code chunk with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```
