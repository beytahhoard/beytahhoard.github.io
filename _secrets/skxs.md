---
layout: subpage
title:  "Shi Kong Xing Shou"
---
**Shi Kong Xing Shou** is your average monster-hunter game for the Game Boy Color. A favorite among Vast Fame's other output, yet cobbled together with subpar code and duct tape.

## Sound Test
A hidden soundtest routine can be found in GameBoy address `62:5f9c`.
To access it, first go to the title screen, enable the code `0119FAD0` and then start a new game. Once Ballot leaves his house the sound test appears!

![Sound test](img/skxs_soundtest.png)

## Items used in testing
At `00:2d50` there exists item data to be copied into the inventory, which was most likely used for testing the game:
* Super Capsule x99 (Master Ball)
* Magic Fruit x50 (Rare candy)
* Magic Fruit x99 (Rare candy)
* Shrink Ray x99 (Escape Rope)
* TM13 x1
* TM33 x1

After that there is more (albeit unused) item data, although it's just 12 of every item in the game except items 1 to 7.

## Cheat Codes
There are several cheat codes that can be entered in the title screen:

1. Up, A, A, Up, B, B, Select, Select: 99,999 money
1. Down, Down, Left, Right, Select, A, Select, B: Same as above, but with Bali Fruit x2, Magic Fruit x99 + x99 and Shrink Ray x99.
1. Left, Left, Right, Right, Up, Up, Down, Down: Clears SRAM. (Broken due to bad programming)
1. Right, B, B, B, Left, A, A, A: Same as the money+items cheat.
1. Left, Left, Right, Right, Up, Up, Down, Down: Also clears SRAM. (Also broken)

