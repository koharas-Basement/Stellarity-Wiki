# Sharanga

<div class="result kohara-infobox-grid" markdown>
<div markdown class="kohara-infobox-text">
**Sharanga** is a pre-Dragon bow which converts <i class="icon-minecraft icon-minecraft-spectral-arrow"></i>Spectral Arrows into Spectral Bolts. They travel faster, deal more damage and are unaffected by gravity.

<i class="icon-minecraft icon-minecraft-enchanting-table"></i> Sharanga can be enchanted with any Bow enchantment.

<i class="icon-minecraft icon-minecraft-anvil"></i> Sharanga can be repaired by fusing it with a different <i class="icon-minecraft icon-minecraft-bow"></i>Bow.

<br><br>

[TOC]

</div>
<div class="kohara-infobox-table">
  <table id="kohara-infobox--item">
	<tr>
		<th colspan="2" class="kohara-infobox--top-image"><img src="../../assets/items/sharanga.png"></th>
	</tr>
	<tr>
		<th colspan="2">Info</th>
	</tr>
	<tr>
		<td><b>Damage</b></td>
		<td>Varies</td>
	</tr>
	<tr>
		<td><b>Tooltip</b></td>
		<td>Spectral Arrows travel in a straight
		<br>
		line and deal increased damage
		<br>
		25% chance to save Spectral Arrows
		</td>
	</tr>
	<tr>
		<td><b>Durability</b></td>
		<td>424</td>
	</tr>
</table>
</div>
</div>

## Obtaining
Sharanga has a 9% chance to be dropped by Illusioners in [Strongholds](../structures/stronghold.md). Each level of Looting increases the odds by 3%, up to a total of 18% with Looting III. 

It drops paired with 7 - 22 <i class="icon-minecraft icon-minecraft-spectral-arrow"></i>Spectral Arrows.

## Usage
When using <i class="icon-minecraft icon-minecraft-spectral-arrow"></i>Spectral Arrows as ammunition, they are converted into high velocity Spectral Bolts. Bolts deal 30% more damage and fly 30% faster and in a straight line. They can also pierce up to 4 mobs, dissipating upon hitting the 5th.

Sharanga has a 25% chance to not use up fired <i class="icon-minecraft icon-minecraft-spectral-arrow"></i>Spectral Arrows. This chance is doubled by the Infinity enchantment for a total of 50%.

## Tips
- Bolts always disappear after either hitting a block or after 3 seconds have passed, not after travelling a set distance.
- Sharanga enchanted with Infinity is superior to one enchanted with Mending due to increased chance of conserving <i class="icon-minecraft icon-minecraft-spectral-arrow"></i>Spectral Arrows.
- Skeletons in The End drop <i class="icon-minecraft icon-minecraft-spectral-arrow"></i>Spectral Arrows on death while being inflicted with Glowing, meaning that setting up a mob farm there could be a really good way to get the special ammunition for Sharanga.

## Trivia
- This is the first ranged weapon to ever be added into Stellarity.
- Prior to v2.1a, Bolts would explode in a small radius when expiring or when coming into contacts with a non-solid block, dealing 66% of Arrow's __base__ damage with 20% armor penetration.
    - Additionally, prior to 2.0a, explosions didn't have any armor penetration and dealt flat 10 damage.
- The End Rod particles which spin around the Spectral Bolts always spin clockwise.

## Advancements
| Icon | Title | Description | Parent | Actual requirements (if different) | Resource Location |
| :--- | :--- | :--- | :--- | :--- | :--- |
| <div class="adv-div"><i class="adv adv-task"></i><i class="icon-adv icon-stellarity icon-stellarity-sharanga"></i></div> | Robbing the Fortress | <span style="color: #55FFFF;">Get a rare item from an Illager in the Stronghold</span> | Eye Spy | Have either Sharanga, Clockwork Crossbow or any pre-Dragon Spellbook in your inventory | `stellarity:story/drop_rare_illager_loot` |

## History
=== "**Indev-2.3.0**"
	- :red_circle: Reduced pierce count (4 -> 3)
	- :red_circle: Reduced extra damage multiplied (+30% -> +12%)
=== "**2.2.0**"
	- :green_circle: Bolt damage and velocity mutliplier increased (+20% -> +30%)
	- :green_circle: Increased the lifetime of Spectral Botls (1s -> 3s).
	- :red_circle: Reduced pierce count (inf -> 4).
	- :bug: Fixed jank.
	- Improved Bow and Bolt sounds and visuals.
	- Resprited.

=== "**v2.1a**"
	- :red_circle: Bolts no longer explode upon expiring.

=== "**v2.0a**"
    - :red_circle: Extra velocity multiplier reduced (1.25x -> 1.2x).
    - :red_circle: Reduced bolt lifespan back to 1s.
    - :red_circle: <i class="icon-minecraft icon-minecraft-spectral-arrow"></i>Spectral Arrow save chance reduced to 25%. Infinity chance reduced to 50%.

=== "**vIndev-1.6a**"
	- :green_circle: Increased Bolt lifespan by 50% (1s -> 1.5s).
	- :green_circle: Increased drop chance (5% base chance -> 9%,  with 2% -> 3% extra chance from Looting).
	- :green_circle: Now drops with 7 - 22 <i class="icon-minecraft icon-minecraft-spectral-arrow"></i>Spectral Arrows.
    - :green_circle: Now has a 33% chance to not consume <i class="icon-minecraft icon-minecraft-spectral-arrow"></i>Spectral Arrows. This chance is increased to 66% if enchanted with Infinity.
	- :green_circle: Increased Spectral Bolt velocity multiplier (1x -> 1.25x).
	- :green_circle: Increased durability (384 -> 424).
	- :yellow_circle: Bolt explosions no longer deal flat 10 damage, and instead deal 66% of Arrow's base damage with 20% armor penetration.
	- Dying to a Spectral Bolt explosion will now result in a custom death message.
	- Optimized and cleaned up Sharanga's code.
	- Slightly tweaked sound and particle effects.

=== "**v1.5b**"
	- Introduced
