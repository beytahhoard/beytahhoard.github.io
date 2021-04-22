---
layout: subpage
title:  "Pokémon Gold"
---

## Unused Battle Transition (SW'97)

In the Spaceworld 1997 demo, four transition types can be seen. Three of which (wavy, clockwise wipe, speckle) make it to the final game, and an additional one (scanlines) that can be seen in demo footage. These transitions are triggered at random on every battle (wild or trainer).

However, there is an additional transition present in the ROM, which looks like folding blinds. This transition type is never seen under any normal circumstance.

<video controls width="250">
	<source src="img/sw97_transition.webm" type="video/webm">
</video>

To see this transition on every encounter, replace 4 bytes in the SW'97 ROM, starting at address `0x8C5C6` (`23:45C6`) with `08 08 08 08`. Alternatively, you can enter these Game Genie codes:

* `085-C6B-E6E`
* `085-C7B-91E`
* `085-C8B-D56`
* `085-C9B-B32`

## Sweet Kiss and Curse (SW'99)

In the Spaceworld 1999 demo, the sprites for the Sweet Kiss and Curse
animation look less cartoony.

| Spaceworld 1999                    | Final                                             |
| ---------------------------------- | ------------------------------------------------- |
| ![Early Sprites](img/GHOSTCHR.png) | ![Final Sprites](img/angels.png)                  |
