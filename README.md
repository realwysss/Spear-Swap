<p align="center"><img src="res/assets/sprswp/icon.png" width="128"></p>

# spear swap

client side fabric mod for minecraft 1.21.11 that makes spear lunging easier.

press the key (R by default) while you have a spear with lunge in your hotbar. it swaps to your hand slot (an empty slot, or a totem if that option is on), waits for the hand to be charged, swaps to the spear, attacks, then swaps back to the slot you started on. the delays between each step are random between a min and a max that you set.

this version only works on servers that run the spear swap guard plugin and let you use it. when you join, the mod asks the server and stays off until the server says yes. on other servers nothing happens.

## settings

mod menu, spear swap, config. you can turn the mod on or off, turn on the totem option and set the min and max ticks for the hand swap, the spear + attack and the swap back. the key is in controls under spear swap.

## install

you need fabric loader 0.15 or newer, fabric api and cloth config. mod menu is optional but you need it for the settings screen. put the jar from the releases page in your mods folder.

## about the code

i do not have the original project anymore, so the code in `src` is decompiled from the jar. that is why the names look like class_1661. the files in `res` are the resources from the jar.

all rights reserved, see LICENSE.
