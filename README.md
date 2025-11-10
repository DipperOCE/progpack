# progpack
Minecraft Add-On for v1.21.120.4

## Helpful Development Resources
### Vanilla Files from Mojang (Bedrock Samples):
https://github.com/Mojang/bedrock-samples/releases/tag/v1.21.120.4
### Minecraft: Bedrock Edition Creator Documentation:
https://learn.microsoft.com/en-us/minecraft/creator/?view=minecraft-bedrock-stable
https://learn.microsoft.com/en-us/minecraft/creator/documents/practices/guidelinesforbuildingcooperativeaddons?view=minecraft-bedrock-stable
### Bedrock Wiki
https://wiki.bedrock.dev
https://wiki.bedrock.dev/meta/useful-links
https://wiki.bedrock.dev/items/custom-armor
### MCBE Essentials
https://mcbe-essentials.github.io
### bridge. IDE
https://bridge-core.app

## Intended Features
The following features are experimental and subject to change
### Armor
-New end-game armor sets added; Prismarine (Veryllium), Ender/Purpur (Chorasteel), Sculk (Reverberum)
-Relevant end-game progression set bonuses added for each e.g Prismarine armor will make building and existing underwater more convenient
### Villager Trading
-Trades are 1(? or limited, or permanently increasing cost each time) time only, does not apply to trading for emeralds
-Wandering trader removed
-Discount from curing removed
-Treasure enchantments removed from trading pool
### Mending Functionality Changed
-No longer passively siphons XP to repair item when equipped
-Instead, (removes repair cost cap for item via anvil and lowers levels required for subsequent repairs to (10?))
-Still makes item functionally infinite but requires repair resource and intentional XP investment
### Elytra Functionality Changed
-Can no longer boost with rockets to fly infinitely
### Player Health and Durability
-All armor tiers nerfed (including diamond) and end-game sets will give bonuses that make each feel powerful and unique
-Protection enchantment nerfed (4% > 3%?)
-Natural healing speed nerfed (same total healing from saturation effect, happens slower)
### Combat and Mob Behaviour
-Zombies and Skeletons inc. Nether counterparts can now spawn holding shields that can absorb 2 hits of any strength from the player
-Dying in the presence of a Zombie or Zombified piglin will spawn another that wears the player's existing gear (similar to how a nearby 
zombie may pick up the player's dropped equipment, but now plays into the idea that the player has been zombified)
-All spiders now apply poison, are faster, and do not take fall damage. Upon death, spawn a cobweb trap?
-If agro Enderman cannot reach target player, player will be teleported as though they ate a chorus fruit, has a cooldown
-Mobs that can equip gear now have increased gear and enchantment potency caps based on difficulty
### Phantoms
-No longer spawn after not sleeping for too many nights in a row
-'Nightmare' phantoms now have a random to disrupt the player from their sleep and attack them (cannot occur for first 2(?) sleeps or for the next 2 sleeps after)
-Dying to phantoms should give player 'Insomnia' curse, summons phantoms for 2 nights and player is unable to sleep for next 2 nights
### Exploration and Structures
-Single stack, repairable item with durability to replace ender pearl found in End City?
-Opening the Stronghold portal now requires you to explore the Stronghold itself (requires items guaranteed in Stronghold chests?)
### Boss Fights
Wither
-The Wither can now only be summoned in the Nether
-The Wither can now no longer take suffocation damage
-The Wither summons more reinforcements
Ender Dragon
-Rewards more XP on subsequent defeats
-Dragon is more aggressive, opting for more swoop attacks, DoT fields
-End Crystals must now be destroyed by right clicking with eye of ender (consumes eye of ender). Destroying an end crystal
will deal a burst of damage to the dragon and give the player regeneration
-Dragon cannot take damage by other means until all crystals are destroyed (50% health)
-Dragon becomes even more aggressive after all crystals are destroyed

### Reduced Incentive for Neutral Mob Farms
-Endermen no longer hostile towards Endermite
-Iron Golems no longer drop iron, drop reduced XP
-Guardians now drop significantly reduced XP
-Elder Guardians now drop significantly increased XP (see Prismarine Cutter)
-Zombified Piglins can no longer drop gold
-Blaze's can now drop gold
### Prismarine Cutter
-Can transmute cobblestone into rough prismarine, stone bricks into prismarine bricks, deepslate into dark prismarine
-Maybe furnace type block that uses water bucket as a fuel source
-Crafted using prismarine and prismarine upgrade template




