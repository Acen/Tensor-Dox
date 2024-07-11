---
title: TensorReactions
layout: default
nav_order: 2
has_children: true
---

# Tensor Reactions

## tbc


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

