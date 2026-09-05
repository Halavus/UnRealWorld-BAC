## TODOs
- update the 3.85 readme
- **keep diy_glossary as vanilla as possible**: if a file is not labelled "BAC", it should be changed the least possible. (although sometimes imperative for fixes) NB: some vanilla recipes have been updated by Sami but never updated in the BAC files (see Lumber below)
- evt. merge changelogs & contributors (currently kept separate for ease of use)
- clean up all BAC files from contributor mentions & changelog comments, and add them to their respective file
- add informations about modded items to the encyclopedia (GAME.NFO)
- Review Tying Equipment recipes to ensure ingredients' required lengths and weights are consistent with vanilla Textilecraft options
- check up intended birch requirements for the hardwood bows and find solutions for the too long text descriptions
- update prices and attack values of the bows, as they're harder to make than vanilla

## Known issues
- [issue with resumability](https://www.unrealworld.fi/forums/index.php?topic=7678.msg24897#msg24897) of modded items is caused by the recipe's \[name] tag not matching the '.name.' of the item.  
	Many, many BAC items and tweaks use this naming trick to work (e.g. "Offload a tree trunk") or use this naming convention for simply... good naming. \[NOPAUSE] tag has been added to them.

## v3.88.3 - Encyclopedia release
### Notable changes
- **added GAME.NFO to the mod package to document modded items in the **Encyclopedia (F1)** instead of leaving comments in the code, hidden from the player**
- **added BAC_contributors.md**
- **tweaked building menu and submenu for making the modded Kota work again**
- **renamed Boats menu to 'Brygun's watercrafts', this person needs credit for the research and work they've done for all BAC enjoyers.**
- **reworked the Transport menu**
- **temporarly disabled the custom naming of certain items (e.g. <ins>Elk</ins> antler comb -> Antler comb) for allowing them to be pausable again**
- **updated Tying Equipment recipes with TEXTILECRAFT skill instead of Hideworking**
- **renamed "Grind xyz-flour" to "xyz-flour" to make them pausable**
- **changed COMMON to AGRICULTURE for grinding flours**
- **moved BAC Bowying recipes out of the 'Arrow' menu, as well as Bows out of Weapons to have all elements of these complex recipes in one place. Access them in the modded handcraft submenu: Bowyer ([O]-[Q])** (Fletching stays in 'Arrow')  
	Clarification after some research:  
	3.86 introduced the 'Modded handcraft options' submenu (\[M]-\[+] or \[O]) and the old recipes dispatch hasn't been updated correctly since.  
	BAC Bowyer options were merged into 'Arrow' by Brygun in v3.80, when the menu letter A got taken by vanilla and as new space for submenus became scarce. This merger is not required anymore, because 25 new free submenu were made available in 3.86.
- **reworked many text descriptions in recipes (☐ you need this and that) that were extending beyond the game window and became partly unreadable and others badly formatted.**  
	If meaningful informations about the work being executed were given by these descriptions, they've been replaced by encyclopedia entries.

### Other fixes
- renamed "Tall roll of Birch-bark" to "Tall Birch-bark roll" to make its hyperlink work correctly in the encyclopedia
- fixed "Tall Birch-bark roll" with the correct {Birch Tree Trunk} ingredient
- added 2 small handles to the draw knife recipe
- fixed "Ball steel hammer" recipe that was making ball iron hammer
- fixed "Short spear" recipe with correct "small spear head"
- added some infos about what is a Tiller. [source](https://www.howtomakealongbow.co.uk/part-5-tillering)
- changed rope to strong cordage in the "Bark tassets" recipe (Barkware)
- grouped every watercraft entry together in the game menu using alternating numbers and letters groups
- renamed "Lumber pack frame" to "Lumberpack frame" for it to show in the encyclopedia
- changed Sledwagon recipe to 'Rope for pulling harness' but 'Strong Cordage' for securring the load left as is
- removed "Gather Rowan Sapling" as it was used for the already removed BAC Arrowshaft making
- added \[masterwoodtype] tag to half and quarter logs [a wildcard is needed when used as ingredients](https://www.unrealworld.fi/forums/index.php?topic=7699.msg24992#msg24992) (\*) in the subsequent recipes
- removed nopause where unnecessary in boneworking recipes
- removed unnecessary descriptive text in boneworking recipes
- changed the canteen's needed tying equipment to cord (who wants to carry liquid around with yarn?) and upped the price accordingly
- made the washed bandage less controversial by requiring a knife
- changed base item of the quern's recipes to huning horn to avoid them being consumed as stones by other recipes
- renamed "Grind xyz-flour" to "xyz-flour" to make them pausable
- changed COMMON to AGRICULTURE for grinding flours
- archived outdated broadhead arrow, as it's craftable in vanilla since 3.80 (fur fletched variant remains)
- changed base item of the Forked bone arrowhead. to "Bone arrowhead" according to Buoidda's statment that their penetration [cannot be modded](https://www.unrealworld.fi/forums/index.php?topic=5865.msg17575#msg17575)
- changed Tree trunk to Pine tree trunk in the "Compression Pine Belly" as stated by the comments in the code
- changed name of 'unfinished bow' to 'unfinished shortbow' for the sake of clarity

### v3.88.3 Mod files cleanup
- added BAC_changelogs.md
- added BAC_dev_notes folder (This directory won't be part of the releases, but kept on GitHub for reference)
- moved \_modguide to "BAC_dev_notes" directory
- moved and renamed "Thiebs 3.87 to 3.88 changelog.txt" to "BAC_dev_notes" as it contains experimentation testing logs
- corrected Vanilla Lumber recipes with their missing \[masterwoodtype] tag from 3.86
- archived diy_BAC_Bows
- archived bin_BAC_kota_standard
- cleaned up comments and logs in diy_BAC_Fishing
- cleaned up comments and logs in diy_BAC_Fletching_and_Bowying
- archived outdated Bowstrings from diy_BAC_Fletching_and_Bowying to [ObsoleteFiles](https://github.com/Halavus/UnRealWorld-BAC/tree/main/ObsoleteFiles)
- cleaned up comments and logs in diy_BAC_Lumber
- archived outdated Big Spruce Branch from diy_BAC_Lumber to [ObsoleteFiles](https://github.com/Halavus/UnRealWorld-BAC/tree/main/ObsoleteFiles)
- cleaned up comments and logs in diy_BAC_Hafting
- cleaned up comments and logs in diy_BAC_Textilecraft
- removed Vanilla Spindle from the BAC files (still present in the Textilecraft menu)
- archived "\[...] textile needles" (Knitting needles?) from diy_BAC_Textilecraft to [ObsoleteFiles](https://github.com/Halavus/UnRealWorld-BAC/tree/main/ObsoleteFiles) as Knitting currently is disabled. Their TILEGFX is missing too.
- cleaned up comments and logs in mod_diy_BAC_Bryguns_watercrafts
- all useful informations found in the cleaned comments above have been added to the encyclopedia
- archived diy_BAC_Trapping as it only contains vanilla items
- removed outdated bigsprite.png references (:148:, etc.) in cookery_glossary
- archived inactive recipes from diy_BAC_Tying_Equipment to [ObsoleteFiles](https://github.com/Halavus/UnRealWorld-BAC/tree/main/ObsoleteFiles)
- cleaned up comments and logs in diy_BAC_Tying_Equipment
- started mod_diy_BAC_Boneworking.txt
- archived inactive recipes from mod_diy_BAC_Boneworking.txt to [ObsoleteFiles](https://github.com/Halavus/UnRealWorld-BAC/tree/main/ObsoleteFiles)
- started cleaning up comments and logs in diy_BAC_Utility (does glue need special treatment for clarity?)
- changed base item of the craftable canteen to Wooden canteen
- removed Elk hunting horn duplicate from hafting 

## v3.88.2
- Commented out vanilla arrow recipes in the diy_glossary file as they are being added by diy_BAC_Fletching_and_Bowying in order to keep menu order (having both was creating duplicate menu items)
- Changed mod shortbow and longbow in diy_BAC_Weapons to hardwood shortbow/longbow to fix issue of overlapping item names with vanilla bows

## v3.88.1
- Bloomery furnace (forge) now Bloomery furnace forge due to bug with parentheses in recipe names

## v3.88 "no ai" by Thiebs
- reverted numerous changes that caused issues introduced by the use of Claude AI
- biy_BAC_home_cabin.txt verified to be identical to vanilla log cabin
- bin_BAC_kota_standard.txt also identical to vanilla
- biy_BAC_shelter_standard.txt also identical
- remainder of biy_glossary.txt also matches
- Replaced BAC version of diy_glossary.txt with vanilla 3.88 version. Vanilla version includes changes to clothcrafts, required sewing needle, new clothcraft skill, as well as better sorting of containers.
- edited mod_diy_BAC_Clothing.txt to use new vanilla {Sewing needle} tag instead of modded, and all finished clothing recipes to use *CLOTHCRAFT* instead of *TEXTILECRAFT* to be in line with vanilla 3.88
- mod_diy_BAC_Armor_Leather_Fur.txt changed all 'vanilla'-clone recipes to their 3.88 vanilla counterparts. Changed *HIDEWORKING* to *CLOTHCRAFT* on all modded recipes (to match vanilla). Considered changing to require needle, but not sure if recipes are intended to represent more crude or sophisticated stitchworking, so left as-is for now.
- mod_diy_BAC_Barkware.txt changed birchbark shoes and cap to new vanilla versions. All modded recipes that made clothing items changed from *HIDEWORKING* to *CLOTHCRAFT* to match vanilla
- mod_diy_BAC_Boneworking.txt changed Animal headdress from *HIDEWORKING* to *CLOTHCRAFT*
- mod_diy_BAC_Wool.txt changed all equippable clothing items to *CLOTHCRAFT*, and replaced modded textile needle with {Sewing needle}
- issue with resumability is caused by the recipe's name not matching the name of the item  
Updated all modded recipes to use item name as recipe name and removing "NAME:" tags accordingly.
- added \[NOPAUSE] to recipes that use "\[name]" in the body
- added \[NOPAUSE] to Hafting recipes
- added \[NOPAUSE] to Transport recipes
- added \[NOPAUSE] to fur and leather simple clothes to retain ability to use fur types (they are also all shorter time cost)
- added \[NOPAUSE] to Bark equipment  
Note that some bark equipment have longer (4h) times, which may be an issue, but these are mostly more decorative/RP items than strict survival, so it should be okay for now
- added \[NOPAUSE] to other decorative/RP items in boneworking, eg the various combs
- Commented out backstraps and sinew recipes as this is now a vanilla feature
