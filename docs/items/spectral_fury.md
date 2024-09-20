# Spectral Fury

<div class="result kohara-infobox-grid" markdown>
<div markdown class="kohara-infobox-text">
**Spectral Fury** is a post-Dragon bow with the ability to convert <i class="icon-minecraft icon-minecraft-spectral-arrow"></i>Spectral Arrows into homing Wisps on overcharged shots. Wisps slowly fly and seek out nearest mobs.

<i class="icon-minecraft icon-minecraft-enchanting-table"></i> Spectral Fury can be enchanted with any Bow enchantment.

<i class="icon-minecraft icon-minecraft-anvil"></i> Spectral Fury can be repaired by fusing it with a different <i class="icon-minecraft icon-minecraft-bow"></i>Bow.

<br><br>

[TOC]

</div>
<div class="kohara-infobox-table">
  <table id="kohara-infobox--item">
	<tr>
		<th colspan="2" class="kohara-infobox--top-image"><img src="../../assets/items/spectral_fury.png"></th>
	</tr>
	<tr>
		<th colspan="2">Info</th>
	</tr>
	<tr>
		<td><b>Damage</b></td>
		<td>Varies (Arrows)
		<br>
		7 - 11.5 (Wisp)
		</td>
	</tr>
	<tr>
		<td><b>Tooltip</b></td>
		<td>Overcharged shots convert
		<br>
		Spectral Arrows into wisps
		<br>
		which seek out and attack mobs
		<br>
		25% chance to save Spectral Arrows
		</td>
	</tr>
	<tr>
		<td><b>Durability</b></td>
		<td>636</td>
	</tr>
</table>
</div>
</div>

## Obtaining
Spectral fury can be obtained by combining a [Sharanga](sharanga.md), 3 Diamonds, 8 Phantom Membranes and an [Enderite Upgrade Smithing Template](materials/enderite_smithing_template.md) on the [Altar of The Accursed](../mechanics/altar_of_the_accursed.md).

## Usage
When using <i class="icon-minecraft icon-minecraft-spectral-arrow"></i>Spectral Arrows as ammunition, shots charged for a total of 1.5 seconds or longer will instead shoot a Wisp. Wisps last for 7 seconds and slowly move forwards, homing in on any mob in a 16 block radius.

Wisps can pierce 2 enemies, dissipating upon hitting the 3rd. Wisps try to home in a 'smart' way:

- If there are 3 mobs near each other, Wisps will try to hit all 3 of them, one after another.
- If there are 2 mobs next to each other, Wisps will first hit mob #1, then fly and attack mob #2 and then back to mob #1.
- If there is only 1 mob and no other mobs in a 16 block radius, it will instead hit the same mob 3 times.

Wisps deal `4 + (1.5 * arrowdmg)` damage, where `arrowdmg` is Arrow's base damage value[^1]. After piercing an enemy, Wisps damage for the next hit will be reduced by 40% (rounded to the nearest tenth), stacking multiplicatively.

### Wisp damage
| Power level | Damage | Damage on the second hit* | Damage on the third hit* |
| :--- | :--- | :--- | :---|
| :x: | 7:heart: ₓ ₃․₅ (`4 + 2.0 * 1.5`) | 4.2:heart: ₓ ₂․₁ | 2.5:heart: ₓ ₁․₂₅ |
| 1 | 8.5:heart: ₓ ₄․₇₅ (`4 + 3.0 * 1.5`) | 5.1:heart: ₓ ₂․₅₀₅ | 3:heart: ₓ ₁․₅ |
| 2 | 9.2:heart: ₓ ₄․₆ (`4 + 3.5 * 1.5`) | 5.5:heart: ₓ ₂․₂₅ | 3.3:heart: ₓ ₁․₆₅ |
| 3 | 10:heart::heart::heart::heart::heart: (`4 + 4.0 * 1.5`) | 6:heart::heart::heart: | 3.6:heart: ₓ ₁․₈ |
| 4 | 10.7:heart: ₓ ₅․₃₅ (`4 + 4.5 * 1.5`) | 6.4:heart: ₓ ₃․₂ | 3.8:heart: ₓ ₁․₉ |
| 5 | 11.5:heart: ₓ ₅․₇₅ (`4 + 5.0 * 1.5`) | 6.9:heart: ₓ ₃․₄₅ | 4.1:heart: ₓ ₂․₀₅ |

\* Due to rounding, the damage gains might be incosistent across levels.

## Tips
- Bolts always disappear after either hitting a block or after 3 seconds have passed, not after travelling a set distance.
- Spectral Fury inherits Sharanga's arrow conservation chance, meaing that enchanting it with Infinity is superior to enchanting it with Mending due to increased chance of conserving <i class="icon-minecraft icon-minecraft-spectral-arrow"></i>Spectral Arrows.
    - Mending is made redundant even further with Spectral Fury's increased durability.
- Skeletons in The End drop <i class="icon-minecraft icon-minecraft-spectral-arrow"></i>Spectral Arrows on death while being inflicted with Glowing, meaning that setting up a mob farm there could be a really good way to get the special ammunition for Spectral Fury.

## Trivia
- Wisps move at a speed of 13 blocks per second (0.65 per tick).
- Spectral Fury has exactly 50% more durability when compared to Sharanga.
- kohara sometimes refers to this bow as `Spectral Furry` when talking to himself.
- Spectral Fury is based on the Spectre Staff from Terraria.

## Advancements
| Icon | Title | Description | Parent | Actual requirements (if different) | Resource Location |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <div class="adv-div"><i class="adv adv-goal"></i><i class="icon-adv icon-stellarity icon-stellarity-aota"></i></div> | Cursed Crafting |  | An Introduction to Dark Magic | Craft anything at the Altar of The Accursed | `stellarity:aota/cursed_crafting` |

## History
=== "**Indev-2.3.0**"
	- :green_circle: Reduced damage falloff per pierced entity (-40% -> -30%)
	- :green_circle: Wisp movement speed +30%.
	- :green_circle: Max hit count increased (3 -> 4)
	- :green_circle: Increased wisp damage (4 + 150% of base arrow damage -> 5 + 150% of base arrow damage)
	- :green_circle: Increased Wisp homing strength.
	- :bug: Fixed the crafting recipe not working.
=== "**2.2.0**"
	- :rocket: Introduced
	- :bug: Bug: The recipe does not work

[^1]: https://minecraft.wiki/w/Power#Usage
