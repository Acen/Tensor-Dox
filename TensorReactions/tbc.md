---
title: To Be Confirmed
layout: default
nav_order: 2.5
parent: TensorReactions
---

# To Be Confirmed details


> Added new `reaction` variable that has the current reaction object for action/condition lua

> Added `reaction.reference` that has the actual reaction stored, not just the current instance of it


[Return values](https://discord.com/channels/617481815418077185/673326353243832349/690846130124095529)
> Added some new possible return values for lua reactions and actions.
> 
> You can now return (table)action, (number)targetID, (bool)ignoreWeaveRules, (bool)allowInterrupt (ignoreWeaveRules and allowInterrupt are optional) from your lua action or reaction, and assuming action is a valid ActionList action, reactions will use it's own override system.
>
> Note: If you choose to return an action from lua, make sure the “Lua Returns Action” box is checked!


Allows subfolder support - sorts alphabetically.
[https://discord.com/channels/617481815418077185/673326353243832349/695882685029285888](https://discord.com/channels/617481815418077185/673326353243832349/695882685029285888)



### Has Buffs / Missing Buffs check type, chilod of Buff Check

Added "Has Buffs" and "Missing Buffs" to make checking multiple buffs easier
![example of Has Buffs / Missing Buffs](https://i.imgur.com/MHqFBZF.png)

### OnMapChange event
[https://discord.com/channels/617481815418077185/673326353243832349/696656594326388816](https://discord.com/channels/617481815418077185/673326353243832349/696656594326388816)
