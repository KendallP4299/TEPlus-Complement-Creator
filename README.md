# TE+ Complement Creator V2.3.0 for TE+ Renewed version 7.4.0

This application, made by Kendall Payton(Ziromanean#3173 on discord), 
is for the creation of custom complements to the "Technical Enchant+ Renewed"! Datapack (created by Frektip)
In this app, you can add many different items and blocks to the datapacks' functionality
and is intended to add mod support to TE+ Renewed by allowing the user to add whatever items they choose.

To use this software, extract these files to a new folder and run the "TE+ Datapack Creator.exe" file.
When you're finished adding items, press the "Build" button in the bottom menu bar to create a complement.
Enter the a unique path name and complement name.
A zip file will be saved to a complements folder in assets. This is where all the complements you create, will be stored.

# Newest Additions/Changes
  * Custom addon support
  * File formatting for preset data has changed, presets made before 2.0.0 are no longer supported and will throw an error. Sorry :(

# Custom Addon Support
In the Addon Support tab, you wil be able to add support for your custom item types to be enchanted with the addons that you've created.
If you have made your own addon datapacks for Technical Enchant+ before, the following is a list of things you'll need to know for this section:
   * The ID of the addon being added.
   * The name of the addon folder located at: (addon).zip\\data\\<ADDON PARENT FOLDER NAME>.
   * The name of the MCFunction file located at: <PARENT FOLDER>:teplus/techanv/interaction/merge/<MCFUNCTION NAME>.
   * The level of the addon enchantment.
   * What tool type the addon is for.
   * And, if the addon has incompatibilities, the ID of said enchantment and if it is a custom or vanilla enchantment.

Once you have added all the addons you wish, you can build the pack as normal and add it to your world save!
   
# Compatible with stand-alone addons:
   * Expertise
   * Compact
   * Spawner Touch
   * Uncover

# Below is a list of the types of items that can be added thus far:
   * Ore Types
   * Shovelable Blocks
   * Swords, Tridents, Bows, Crossbows, Shields
   * Pickaxes, Axes, Shovels, Hoes, Fishing Rods
   * Custom Items
   * Armor Sets
   
You can also clear all items from the list if want to start from scratch.

# CUSTOM ITEMS
In the Tools Tab, you'll notice a section labeled "Custom Item ID:"
This is where you can add modded items that fall under more than one category of tool. For example, some mods have tools that 
combine Pickaxes, Axes, and Shovels called a "Paxel".
Like the other Item ID boxes, enter the full item id in the textbox.

In the "Type" section, enter the type of tool it is that is being added.

Finally, the "Item Interactions" section is where you can select the kind of tool types that apply to the tool you are adding. 
Be sure to select at least one, or it won't be added.

(Full Example):
   ID - gobber2:gobber2_paxel_nether,
   Type - paxel,
   Interactions - (Pickaxe, Axe, Shovel)

# WEAPONS
In the Weapons Tab, the sword and trident have a box for entering damage values.
These values are written as decimal numbers: X.X

(Technically you can make this value whatever you wish, but bugs may occur, so perform at your own risk!)

**New Format Example:** (Quotations Included!)  
  * "betterend:aeternium_sword", 8.5

# ARMOR
In the Armor Tab, both the chestplate and boots have some extra features.
Both allow for the user to specify the amount of basic Armor, Armor Toughness, and Knockback Resistance. 
If you choose to enter number value that are different than the default ones on the armor when hovering over the item in-game, these values are applied to the item only AFTER the 
Life Plus or Agility enchantment is added to the armor pieces.

Armor, Toughness, and Knockback Resist are measured as a decimal. (ex. 5.0, 2.3, and 0.4 respectively), if an armor piece doesn't have one of the three number values, just input 0.

**New Format Example:** (Quotations Included!)  
  * "betterend:aeternium_chestplate", 3.5, 9, 2

# Presets
From the main menu, you'll see a Preset menu button. 
This is where you can load or delete any presets you have. 
The window next to the selection drop down provides a preview of what the preset has in it before you load it.
A Save Preset button is always present at the bottom-left of the app.

Currently the following presets are included:
  * Goober2
  * Impaled
  * Upgraded Netherite
  * Go Fish 
  * Better Nether
  * Better End
  * Additional Additions
  * Biomemakeover
  * Immersive Armors
  * Mythic Metals
  * Ad Astra

(For Go Fish: To get the vanilla rod to work on the table, you'll need to add "minecraft:fishing_rod")

Due to file format changes of v2.0.0, if you are updating to a newer version, any preset that were made in a older version won't be compatible. 
**See Armor and Weapons sections for new format details.**

More built-in presets will be added in the future. 
If there are any more presets that you would like to see add by default, let me know!

# Troubleshooting
A troubleshooting button is present on the main menu. 
If your complement isn't functioning properly when in-game, there could be one or more factors involved.
These reasons could include:
   * You don't have the mod for the complement installed
   * There's a typo in a ID or number value
   * Complements might be conflicting with one-another
   * Your creator version is not up-to-date
   * The creator is not yet updated for the latest version of TE+

If issues still persist, please feel free to contact me and I will try to assist as best I can.

# Credits
_**If you would like to reach out with suggestions or help, you can always ping me on Discord at Ziromanean#3173.
Also check out Frektip's Planet Minecraft Page for the Original TE+ Renewed Datapack! Without his help, none of this would be possible!**_

https://www.planetminecraft.com/data-pack/technical-enchant-for-1-17/

_All Rights Reserved. Do Not Claim As Your Own._
