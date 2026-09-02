NEW README section from Rudy

BACKING UP FILES - if you want to be able to remove this mod without reinstalling, back up your diy_glossary, biy_glossary, cookery_glossary files, as they will all be over-written by this mod. Steam updates may also update these files, and you will need to "reinstall" the mod. Then, copy the contents of the zip into your main directory, allowing it to overwrite files.

----------

OPTIONAL BUILDING FILES - there are multiple versions of several files. Note that some files start with biy, and some start with bin. Think of that as yes/no. bin files are inactive and do not do anything. You can only one home, one kota, one shelter, and one one water file active at once without running into problems, because the game cannot handle multiple recipes to create the same tile. 

HOME
bac_home_cabin - active by default. Allows building of a log cabin.
bac_home_cave - inactive by default. Allows improving the interior of a cave (same as the interior of a house, but easier, or removing those improvements.)
Ovens and furniture are available under either.

KOTA
bac_kota_hideworking - Active by default. Kotas are made with the kota covers created with the Hide & Bone menu. 
bac_kota_standard - Inactive by default. Kotas are made as in vanilla, and do not require crafted kota covers.

SHELTER
bac_shelter_standard - Active by default. Shelters are built as per the vanilla recipe.
bac_shelter_punt - Inactive by default. Allows constructing a shelter more quickly using an overturned punt.
bac_shelter_tarp - Inactive by default. Allows constructing a shelter more quickly using a leather tarp.

WATER
bac_water_roof - Active by default. Can create a water tile meant to simulate catching rainwater off of a roof of a cabin.
bac_water_well - Inactive by default. Can create a water tile meant to simulate digging a well.
bac_water_cliff - Inactive by default. Can create a water tile meant to simulate catching rainwater off a cliff. Good for cave dwellings.

----------

COOKERY OPTIONS - There are two cookery files that you can use.

cookery_glossary - default cookery recipes for the mod. Probably closer to "reality".

OFFEASIER_cookery_glossary - has shorter cook times, and longer shelf life for many items. If you want to use this, rename the default cookery_glossary to OFF_cookery_glossary, and rename this to cookery_glossary



------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------






ORIGINAL BAC mod readme for users - preRudy



BAC stands for Brygun And Community

>>>>>>>>>>>>>
Install Instructions

Recommend backing up your game files. 

Note: As the diy_glossary core file (and possibly others) will change this will likely fail a Steam check of the game's installation.

1) download the BAC zip

2) unzip the BAC files to its own directory

3) Locate your Unreal World directory, such as by using Steam's show local files. Tip: you may  want to a shortcut to it.

4) It is a good idea to store the biy, diy and cookery glossary files.

5) BAC will have to overwrite a few files so really should back these up and any steam auto-update will affet these files:
biy_glossary.txt
diy_glossary.txt
cookery_glossary.txt


4) Copy the BAC unzipped files and subdirectories into your Unreal World directory. You should see a question to overwrite the diy_glossary (and maybe others) that is to be allowed.


6)In the process the BAC truetile subfolder contents should copy into the Unreal World truetile subfolder.

Special:
As of this writing modders have limited intereaction with the "build" menus so a work around is needed to allow multiple versions of doing a similiar thing.
The boff_biy_XXX files are meant to be activated when needed then turned off again. This is due to how overlapping recipes currently work. To activate rename the file to remove the "boff_" portion of the name. To store the file rename and restore the the "boff_".

Be sure to report any bugs or issues on the forums so we can all share in their resolution

>>>>>>>>>>>>>

Forum links

Current thread for this mod:
https://www.unrealworld.fi/forums/index.php?topic=4712.0

Precussor Brygun added items developed for Bouidda is at:
https://www.unrealworld.fi/forums/index.php?topic=4654.0

The much older old forum thread for my mod initial Rain's cloth mod is at:
https://www.tapatalk.com/groups/urwforum/3-4-brygun-additional-t3818.html

>>>>>>>>>>>>>
Discussion

Brygun's mod of "added items" dates to mid 2010s (?) with the old Unreal World forums. Part of my goal was to also inspire others to mod and encourage a vibrant community. Admittedly I have wandered from Unreal World yet also returned. That is something about the longest programmed game that is the origin of the open world survival genre (so sayeth the Guiness book of recods).

There are now many modders contributing to this project. Brygun is the current lead adding his own code while incorporating the suggestions and interests of others. The list below is meant to honor those contributors. It may miss someone for which a squirrel cut has been left in the woods as a peace offering.

>>>>>>>>>>>>

Does BAC reduce realism?
A question from JaxonThomas in the thread 
https://www.unrealworld.fi/forums/index.php?topic=5533.0

Brygun answers thus:

Well, now. Didn't expect that question.

Fair disclosure: I'm Brygun. The B in the BAC mod. Organizer of the mod from its various sources including my own addittions.

So where to being:

Q: Is play balance different with BAC?
A: Yes
Of course it does. There is many ways to get different tools or results other than the options in the vanilla game. 
Ways of generating wealth bundled up in ways of entertaining your self with role playing whittle a board game. Even if the game tracks how much of a different good is sold that there exists multiple new items means you could profit by selling them to a village.

Q: Does it change realism?
Well what is your reference for realism? Many, though not all, players are modern urbanites enjoying the game as a trip to the woods. I'm a bit urbanized but also grew up in the country side running around in forest was normal. It was a very safe wood without bears or lynxes or wolverines or Nerjpez to worry about. 

Q: Is there realism basis for items in the BAC?
A: Yes
In fact if you open up the diy_BAC_XXXX.txt files I specifically included references including links to youtube videos you can watch. Those certainly show there is realism is the mod.

Q: Did item XXX exist in real world Iron Age Finland?
Oh now there is a varied question. Item by item of all items would be too much so here is a few. Again many others have references in the .txt file comments.
= As a Canadian with a tradition of birch bark canoes I put it in yet as Saami, maker of Unreal World and a native Finlander, pointed out is the sort of birch trees in Finland are different so they probably couldn't even made at all.
= The largest of the boats, the clinkered punt, is a combination of the steamed open tree logs known to Finland plus the clinkering and caulking of what is known for sure in later ages but possible in that age.
= The steps for making iron come from Rain's Ironworking mod and do indeed match up to my own studies of blacksmithing in that period. I was surprised to find that lake ore is a real thing. I thought it was a quirky gamey thing but low and behold if one looked into it this actually is realism. Secret: Finland has/had so much surface and near-surface iron ore that it flowed down with the rains into rivers into lakes. In the lakes, like the bogs, biological processes pulled it out and tended to make it into clumps mixed with non-iron. Thus you did need to roast the lump of lake ore (or bog ore) and process.

= Back strap weaving is a real world thing. I believe there is a video for that in the .txt files.

=  Cordage is easier to make in BAC through various real world ways. Only the recent 3.60 ish (IIRC) added the withe making. Prior to that it took capturing animals to get leather to get the cords to hang meat to dry in the winter. A rather recursive if you have it (an animal kill) you can do it but if don't have it you can't do it (if that makes sense). In my own research I looked into real world ways for making cordage, like digging up spruce roots, and added them in. Real = yes. Changing the play balance = yes. 

Part of the BAC goals was to include things that were known or plausible to teach woodland survival skills. Thats why the Shaman mod was excluded, that is well researched but deals with a metaphysical.

If you are new to UnReal World you might want to give a few goes at playing without the mod. It can be added mid-play or removed. The way Unrweal World recipes work once an item is created its properties are assigned to the instance thus not needing an ongoing reference. IF there is a graphic custom that might end up being empty but it should still show up in the list if you stand on a tile to pick it up. Of course without  the mod you don't need a Ball Hammer.

Good question. Think I will add the answers to the BAC forum and the text files.


>>>>>>>>>>>>>
Contributors


Rain = Original iron working with his massively complex mod many of us in the early days used

Endive = Another early modder with a self sufficiency mod that became all but a standard install across the community

Privateer = one of the most active on the forums over many years, both with his own mod and helping others (including Brygun) develop theirs. His fish cuts are also in this mod.

Bouidda = For a newer comprehensive mod. More recent game updates duplicated some features which was a part of the decisiion to make a comprehensive mod.

JEB = offering his lamellar armor recipes which will hopefully be incorporated by the time you read this or soon(tm).

Signatus = for support during the rework of brygun's added items and doing his own integration, which also inspried brygun to do likewise and thus was born the BAC mod.

Bedlam = for his nerjpez cookery mod now incorporating many recipes

Fataal = For his hard tack recipe, long may it go before spoiling

Iago.Hach = Whittling mod, roasted fish cuts

caethan = Elements of caethan's self sufficiency mod included, in some cases as they were part of the Bouidda mod

Frostbit = Big Rock in biy, for making stone walls as a late game activity

zhihao1 = Finnish cheese mod

Bard of Prey = Graphic, brown kiln.

ptr987 = Woodworking and wood pricing improvements

Adamsor = truetile update for fixing backgrounds for non-windows gamers

Galgana = Log transport sledwagon based on Cathegus, independent version at:
https://www.unrealworld.fi/forums/index.php?topic=5673.0

rudy = For the Quern stone that once made speeds up turning grains into flour, including the truetile graphic. Also took over the mod for the 3.72 update that changed the cord system used in almost all recipes.

JP Finn = for the hot smoker and brine recipes matching the real world practice of field smoking preserving foods for a moderate time. Also bait cutting recipes.

Apologies to anyone else not listed. Large scale integration projects do at times miss a contributor. If you post on the forum thread I will investigate adding another contributor.

>>>>

From the old forums there are various items that got passed forward and passed forward again. I was active there at times and away at others. People's whose work is likely within this mod include:

Rain (mentioned already), Endive (mentioned already), Rudy (Lamellar), thefinn


>>>>
Community members doing testing, error checking and giving feedback during the mod development include but not limited to:

Frostbit, KKarlssoNN, Signatus, Jeb

>>>>>
As you can see with the list haven gotten so long it is time I, brygun, feel the time has come to consider this a community mod. Thus the efforts to change the name to the Brygun And Community mod or "BAC" mod for short.

Finally, I consider the principle of stewardship to apply. I am a caretaker, a steward and a keeper of a thing many have made. So I ask of the community: Should I be gone or taken in death who shall take up this shield and this sword? For those that do have my blessing to do so. 

With thanks twinkling in the stars,

Brygun

>>>>

