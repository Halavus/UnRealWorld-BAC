## TODOs
- create a readme
- **keep diy_glossary as vanilla as possible**: if a file is not labelled "BAC", it should be changed the least possible. (although sometimes imperative for fixes) NB: some vanilla recipes have been updated by Sami but never updated in the BAC files (see Lumber below)
- update [diy_BAC_Lumber](/diy_BAC_Lumber.txt) and [mod_diy_BAC_Carpentry](/mod_diy_BAC_Carpentry.txt) with the 3.86 added \[masterwoodtype] modding tag. 
- merge changelogs & contributors (currently kept separate for ease of use)
- split new changelogs and archive changelogs (before GitHub, currently kept together for ease of copy/paste)
- clean up all BAC files from contributor mentions & changelog comments, and add them to their respective file
- add informations about modded items to the encyclopedia (GAME.NFO)
- Clarify if diy_BAC_Knitting (currently obsolete) should make a comeback: mod_diy_BAC_Wool has the recipes and both versions use Wool in separate ways. One with cloth, the other with Knitting needles. The TILEGFX of those needles seems to be missing and the process of Knitting shouldn't consume wool "Cloth" but wool yarn.

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
- added some infos about what is a Tiller. [source](https:www.howtomakealongbow.co.uk/part-5-tillering)
- changed rope to strong cordage in the "Bark tassets" recipe (Barkware)

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
- cleaned up comments and logs in [diy_BAC_Textilecraft](/diy_BAC_Textilecraft.txt)
- removed Vanilla Spindle from the BAC files (still present in the Textilecraft menu)
- archived "\[...] textile needles" (Knitting needles?) from [diy_BAC_Textilecraft](/diy_BAC_Textilecraft.txt) to [ObsoleteFiles](ObsoleteFiles/old_BAC_Textilecraft.txt) as Knitting currently is disabled. Their TILEGFX is missing too.

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

- diy_BAC_Textilecraft.txt  
	Arimon 3.7x:  
	- .Loom.  
	moved from Weaving to Textilecraft  
	changed {\*Cord} to {Thin cordage}  
	added \[nominlen] to {Thin cordage}  
	- .Nettle Cloth.  
	moved from Weaving to Textilecraft  
	changed \*COMMON\* to \*TEXTILECRAFT*  
	changed Yarn needed from (1) to =50=  
	added \[nominlen] to {Nettle Yarn}  
	- .Weave Hemp Linen Cloth.  
	moved from Weaving to Textilecraft  
	changed \*COMMON\* to \*TEXTILECRAFT*  
	changed Yarn needed from (1) to =50=
	added \[nominlen] to {Hemp Yarn}  
	- .Weave Flax Linen Cloth.  
	moved from Weaving to Textilecraft  
	changed \*COMMON\* to \*TEXTILECRAFT*  
	changed Yarn needed from (1) to =50=
	added \[nominlen] to {Flax Yarn}  

### Brygun's watercraft overhaul
- in diy_BAC_Transport.txt & mod_diy_BAC_Boats.txt  

Primary discussion at:
https:www.unrealworld.fi/forums/index.php?topic=4654

Assumes Bouidda's mod or similiar already installed
(note: outdated comment, needed items have long been added to BAC)

Raft tweaked to between vanilla and Jeb's thoughts
You can now dismantle a raft to get ropes back 

(note: sections about every boat below, merged, slightly edited and informative descriptions added to the encyclopedia)
- Tarp-weave punt
Brygun's portable leather punt  
A large tarp over a woven frame making an upside down bowl  
Comes out as a very light punt  

uses 3 entries  

https:www.unrealworld.fi/wiki/index.php?title=Punt  
This variation of the punt uses simple woods and a section of sealed leather  
It is a light water craft option most useful in early play or as something you can make a few of to stock various camps or river crossings  
Now uses entries from Bouidda's hideworking section to make the tarp

Reworked to use a leather sheet from hideworking

Corracle weblinks
https:www.youtube.com/watch?v=FcAzWOBAfo8&t=209s
https:www.youtube.com/watch?v=V2WJeuA_iKY&t=574s
https:www.youtube.com/watch?v=bmY0vQmen2A
https:www.youtube.com/watch?v=8Q6NUsPymMQ
https:www.youtube.com/watch?v=sujYuLMjnH0&t=229s

Floatation at only a portion of the half sphere from the tarp as it needs to deal with waves and motion.  
Assume 6 oz leather for 24 sq ft tarp  
Half sphere area 24 sq ft, full sphere 48  
Volume from that area ~31 cubic feet  
Half that volume to get back to one sheet is 15.5 ft  
Covert to lbs displacement 961 lb (at pure half sphere)  
Set safety margin at 1/2 for 480 lb  

A little of an under performer due to rounded shape can still manage a game character and what they carry plus the weight of a boat and paddle  
can't carry a tree trunk  

Price = leather tarp + woven branches + a little for work  

- Woven boating frame  
Set to built by a knife only for early play  
Branches woven form a "wicker"  
This size adapted for a leather tarp  
Set to 2 slender trunks as that is compatible with the "Tarp shelter" biy if you choose to use it  

- Birch-bark punt  
Birch-bark punt is based on north american canoes also known as a Birch-bark Canoe
Come out as a reduced though still fair size punt  

uses 4 entries

Being Canadian, canoes are a familiar item. There is no evidence that iron age finland used canoes. This alternate punt was also an early mod of brygun showing multi stage production  
Recipes set to use only knives not axes  

Real life it could take over 7 man days of work. Long times with gravity bending weight assists in the a longer overall build time  
I considered replacing the weight source of stones with wooden blocks those need an axe to make. Likewise boards are made by axes so no boards are in this version of the birch-bark punt. Wooden stakes and staffs are used instead.  

2019-Jan-09 Rework what happens in each stage to better match new learnings on building canoes  

Weight is based on https:www.canadianoutdoorequipment.com/13ft-traditional-algonquin-birchbark-canoe.html and http:www.barkcanoe.com/birchbark.htm 
Then adjusting for recipe weight likely length is 17ft  

Load of a 17 ft canoe mentioned in https:www.mec.ca/en/product/5041-407/Prospector-17-Fibreglass-Aluminum-Canoe  

Canoe terms  
http:canoeing.com/canoes/canoe-design/  

Another excellent make a canoe video with Ray Mears  
https:www.youtube.com/watch?v=XOM2s6y08PQ  

A crafter in Minnesota explaining the steps  
https:www.youtube.com/watch?v=qFSjKRnUzVo&t  

Text based description of canoe building  
http:www.native-art-in-canada.com/birchbarkcanoes.html  

Other weblinks  
http:www.native-art-in-canada.com/birchbark-canoes.html  
http:www.northwestjournal.ca/VIII4.htm  

A website of a modern builder listing materials:  
http:naturalbirchbarkcanoes.com/craftsmanship/  
Along with an estimate of 350 man hours, barely a fraction of which we have in these recipes. Some may be the time preparing resources.  

As seen in some of vidoes, like the Ray Mears one, they did use split spruce twigs (or very close) for sewing the birch bark. The amount they mention is 200 meters (600 ft) so I increased the total cordage calls to 10 unit summed across the different steps.

- Braced bark hull
put main on ground, lay frame on it, then bend sheets up  
exterior braces hold sheet upright  
Sew extra sheet pices  
put the stones and braces in place to push on sheets  
needs to sit a long time to take shape  
Arimon 3.7x: added \[nominlen] to {Tying equipment}

- Sheathed bark hull
\#8# fits in one wooden tub  
Bend and install two outer end posts  
Split stakes into thin sheathing and lay in canoe  
Replace weights, let it sit like this  
Alot of the time is in splitting the wood  

- Ribbed bark hull
\#8# fits in one wooden tub  
Seal sewn sides, bow, stern and any defects  
Let cool and to settle in shape the last time  

- Birch Bark Punt
Good nautical shape with minimal wall structure means above averate flotation of cargo e.g. it's effiecient. Can manage a tree trunk if crew has light or medium gear.  

Birch-punk firewood is used only to keep a small fire going to heat the pitch glue to apply it. So it wouldn't be 3 woods put on all at once but added 1 at a time over the time. Query on how long one added fire wood last. Secondly the glue being sticky to seal isnt the whole 6 hours either. Its a sealing step after the tying is done. So that slow fed fire need not be burning for the whole time. 

- Finnish punt  
Finnish dug out style punt based on what Erkka told us about  
This is a punt as in the vanilla game  
Low skill medium equipped characters should be able to attempt this
Requires a Stone adze axe or Iron adze axe  


Brygun's inspiraton based on discussions at https://www.unrealworld.fi/forums/index.php?topic=4661.0 espicially Erkka (co-dev of UrW) sharing a youtube https://www.youtube.com/watch?v=kW7BdhOZZ_c&t=4s  

- Pointed log
Start with "log" not trunk  

- Shallow log  
Here a hand axe can be used as you are at the open top  
2023-12-A as per Saami the max safe weight for containers is 25.5  
2023-12-05 limited capacity put back in  

- Deep dug hull
here the adze axe is needed due to working in the confined space  
This stage could also be used as a trough for soaking leather  
2023-12-A as per Saami the max safe weight for containers is 25.5  

- Medium dug hull  
Here the adze axe is needed due to working in the confined space. This stage could also simulate a feeding trough for animals.  
2023-12-A as per Saami the max safe weight for containers is 25.5  
2023-12-05 limited capacity put back in  



- Clinkered punt
Clinker style punt  
A very large punt comparable to small viking boat  
Uses advanced building methods and tools  
Not for starting or underequipped characters  

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>

Dec 2020 Price increase, 
Game uses squirrel hides as internal pricing
reference (older 3.40 game version)
https:unrealworld.fandom.com/wiki/Prices_(v3.40)
1 squirrel hide is worth 17 torches
In that a tub holding 8 lbs of liquid is price 1
larger containers less utility so ratio of hold to price goes down
the dug out canoe phase produces such large trough like conatiners


The tarp for a punt is Price 12
mod tarp weave punt is Price: 13 for floation 480
baseline 1 Price per 40 float intended, plus a bit

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
BAC needed

Collecting large whole sections of birch-bark

Adze axe based for working on better watercraft
Auger for holes on clinker style punt peg holes
Iron nails for the clinker style punt


>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
Bouidda needed items

Leather cover from hideworking for punt
Pitch glue (or * glue) for all others
Clay pots can work for heating the glue
Bouidda iron working for iron and tool inputs

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
Programming note:
A note for a suggested "flotation" represents the weight the
craft can carry including its own weight and the operator
Currently this is not an option in the game though I have 
suggested it



>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>


