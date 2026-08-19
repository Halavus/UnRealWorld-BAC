## TODOs
- create a readme
- **keep diy_glossary as vanilla as possible**: if a file is not labelled "BAC", it should be changed the least possible. (although sometimes imperative for fixes) NB: some vanilla recipes have been updated by Sami but never updated in the BAC files (see Lumber below)
- update [diy_BAC_Lumber](/diy_BAC_Lumber.txt) and [mod_diy_BAC_Carpentry](/mod_diy_BAC_Carpentry.txt) with the 3.86 added \[masterwoodtype] modding tag. 
- merge changelogs & contributors (currently kept separate for ease of use)
- split new changelogs and archive changelogs (before GitHub, currently kept together for ease of copy/paste)
- clean up all BAC files from contributor mentions & changelog comments, and add them to their respective file
- add informations about modded items to the encyclopedia (GAME.NFO)

## unreleased changes
- \[DEV] edited .gitattributes with export-ignore in order to generate clean and user-friendly releases from GitHub
- added BAC_changelogs.md
- added BAC_contributors.md
- added BAC_dev_notes folder (This directory won't be part of the releases, but kept on GitHub for references.)
- moved \_modguide to "BAC_dev_notes" directory. 
- moved and renamed "Thiebs 3.87 to 3.88 changelog.txt" to "BAC_dev_notes" as it contains experimentation testing logs.
### unreleased fixes/updates
- corrected Vanilla Lumber recipes with their missing \[masterwoodtype] tag from 3.86
- fixed "Tall roll of Birch-bark" with the correct {*Birch* Tree Trunk} ingredient
- added 2 small handles to the draw knife recipe
- fixed Ball steel hammer recipe that was making ball iron hammer
- fixed short spear recipe with 'small spear head' instead of 'short spear head'
- tweaked building menu and submenu for making the modded Kota work again

### Mod files cleanup
- Added GAME.NFO to the mod package to start documenting modded items in the encyclopedia instead of using comments in the code.
- archived diy_BAC_Bows
- archived bin_BAC_kota_standard
- cleaned up comments and logs in [diy_BAC_Fishing](/diy_BAC_Fishing.txt)
- cleaned up comments and logs in [diy_BAC_Fletching_and_Bowying](/diy_BAC_Fletching_and_Bowying.txt)
- archived outdated Bowstrings from [diy_BAC_Fletching_and_Bowying](/diy_BAC_Fletching_and_Bowying.txt) to [ObsoleteFiles](ObsoleteFiles/old_BAC_Fletching_and_Bowying.txt)
- cleaned up comments and logs in [diy_BAC_Lumber](/diy_BAC_Lumber.txt)
- archived outdated Big Spruce Branch from [diy_BAC_Lumber](/diy_BAC_Lumber.txt) to [ObsoleteFiles](ObsoleteFiles/old_BAC_Lumber.txt)
- cleaned up comments and logs in [diy_BAC_Hafting](/diy_BAC_Hafting.txt)

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

## Archive changes (before 3.88.x), by file or feature
- Clean Fish  
2023-12-25 returned to make-fishing menu after attempts to put in cooking found it made them cooked no longer raw  

- Bait cutting  
2023-12-08 added bait cutting from JP Finn original forum thread: https:www.unrealworld.fi/forums/index.php?topic=7112.0  
2023-12-25 cooking menu failed on bait so moved to utility  
3.84 relocated to fishing menu  

- diy_BAC_Fletching_and_Bowying.txt  
	Based on Buoidda's fletching  
	Created .Fur-fletched Broadhead Arrow.  
	Created .Branch arrow shaft. with high skill penalty  
	Modified arrow shaft recipes to be able to use stored birch and rowan saplings  
	Moved .Broadhead Arrow. here from Buoidda's ironworking  
	Moved bone fletching items from Buoidda's boneworking  
	For 3.8 having A for Arrows as a hardocded menu this is all moved under that letter  
	updated vanilla to 3.84, tuned arrowmaking to be in line with vanilla  

	- .Forked bone arrowhead.  
	2023-06-08 time increased to be above vanilla bone (non-forked) arrowhead  
	3.84 changed skill to common, changed type to weapon  
	  
	- .Arrow.  
	BAC version disabled to avoid conflict with 3.80 vanilla arrow making  
	  
	- all arrows  
	Arimon 3.7x:  
	changed {Fibre from*} to {Thin cordage}  
	added \[nominlen] to {Thin cordage}  
	2023-06-08 needs tuning to match 3.80 arrow making  
	- .Antler-tipped blunt arrow.  
	2023-12-05 3.82 shifted from using stake to arrow shaft  
	2023-12-05 Increased skills bonus on quality to balance materials needed from 10 to 20  
	- .Repair arrow.  
	disabled due to possible conflicts with 3.80 arrow making  
	maybe have it recover feathers?  
	but the head may be more valuable  
	type of head not yet recorded in "broken arrow"  
	- all modded arrow shafts  
	Disabled now there is a vanilla arrow shaft  

- diy_BAC_Lumber.txt  
	Gathered numerous lumber recipes  
	Intention is for raw or close to raw materials without much wood to wood joining, which goes into carpentry
	Adds Bryguns' wooden block pots
	Brygun adapated alternate log splitting from Bouidda 
	From Nerjpez Cookery = kebab sticks for use in that cookery mod
	Iago.Hach whittling = Small wooden block
	Pricing adjustments based on ptr987 Woodworking which found that old wiki prices were in torches but game currently uses squirrel hide (which is 17 torches)
	Sanded board included as a way to integrate ptr987 in this menu rather than the crowded Carpentry
	- 2023-05 Wooden Stake (fix), needs the \[patchwise] as would staff
	- .Small wooden block.  
	From whittling by Iago.Hach, replaces material for wooden cup  
	- Sapling fix/restoration  
	missing reported by cheesealmighty and fix from Signatus  
	modified rowan fix to look for a young rowan  
	Birch sapling removed as 3.62 has its own  
	- Log splitting, larger than boards  
	Set up so stone axe and low skills can still manage someting  
	Compare to vanilla splittig boards, vanilla guess 4h (240 min) to split trunk into 20 boards  
	Steps needed: +1 -> half log, +2 -> quarter logs, +4 -> radial boards x 16  
	240/7 = about 34 minutes per step  
	Inefficient on materials but breaks down production tasks so things like stone axes can make them.  
	adjust time from 60 to 30 for more likely stone axe and low skill  
	Testing in freezing conditions lead to a tweak to max 25 minutes as really the character could pause a few minutes to put more wood on the fire but current game mechanics don't allow restarting craft tasks only buildings  
	- .Half log.  
	Desired flotation 200 (its own weight)  
	Former Bouidda "Split trunk" which gave 4 x 60 lbs  
	- .Quarter log.  
	Desired flotation 100 (its own weight)  
	Former Bouidda "Split trunk" which gave 4 x 60 lbs  
	Usable as boards, used as bowstaves  
	Brygun changed to 4 x 100 lbs as equal to a log  
	- .Short quarter log.  
	Desired flotation 0 (no longer suitable for towing)  
	Cut in across middle for more likely crafting lengths  
	Estimate length now 1 to 1.5 m 3 - 4 1/2 ft  
	No longer counts as boards once radial board was added  
	Quality affects now in \[...] *note from halavus: remaining text is missing in the original file*  
	- .Tall roll of Birch-bark.  
	No longer destroys tree trunk  
	3.60 time increase from 2h to 3h to better fit longer times  
	
