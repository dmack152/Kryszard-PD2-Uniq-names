This is a fork of Kryszard loot filter which adds in the unique names of the bases. 
It is updated manually by me if Krysz drops an update, I will update this as soon as possible. 

To add this in, go to your PD2 folder and then filters --> Local. Save the .filter file here. Then on the launcher go to item filters and select local and select the one you just added. 


**When this gets updated, you must copy and paste the filter code over your previous code in your local file. Or redownload and paste it over the old file** 

![image](https://user-images.githubusercontent.com/25261174/235166806-538eb480-f8db-4282-a9f6-dc35804b1ab7.png)


# Kryszard's PD2 Loot-Filter
**Hello PD2 Fans!**

Welcome to **Kryszard's PD2 Loot Filter!**  
You can know me from: [Twitch](https://twitch.tv/kryszard). Feel free to follow me there *(I'll try to stream as much as I can for you)*

Link to filter: https://raw.githubusercontent.com/Kryszard-POD/Kryszard-s-PD2-Loot-Filter/main/item.filter

# About
I am trying to make one filter, which will suit most players needs.  
Filter is good for both: leveling and endgame experience.  
It's gonna show you almost everything which can help you during leveling process at early stages of your new characters, and became more strict after you hit **lvl 80+** (select your lootfilter level in-game settings to adjust it more for your needs)

## Season VII Update:

![image](https://user-images.githubusercontent.com/63604590/233369590-f72dfb33-08a0-4817-bb6e-dd0c4154c936.png)

What's new:

- Info about currently selected loot filter level added to horadric cube description,
- Charges weapons "Notice me" note color reduced from green to dark green,
- "Notice me" Notes are showing only for uncorrupted items now,
- Charms now displays it's orginal name + what stats it adds if its good in next line,
- eth unique Tomahawk added for better highlighting,
- Ohm Rune and other misc items descriptions updated,
- Possible RuneWords Note updated for RW bases,
- Added Notes for new S7 items like Hellfire Ashes, Catalyst Shard, etc.,
- Updated already existing Notes to match s7 changes,
- Added new "+Xdwo" abbreviation on NMAG barb helms to catch new Deep Wounds skill,
- Adjusted Filter code with new avaliable improvements
- Paladin shields will show exact Enhanced Damage % automod values,
- Removed Spirit Sword bases from filter level 4+,
- Added few more staves RW bases for your new A4 Merc,
- Removed Gold-worthy items from filter level 4+ (hidden gold piles are auto-picked up now),

## Season VI Update:
General changes:
* Added all ETH EXC and ELT weapons with 0 and 2 or more sockets to "FILTER LEVEL 1 - Hide Just Trash Items",
* Changed how info about max sockets is displayed. Before it was using shortcuts of:
**Q, PB and C** - stands for Larzuk Quest, PuzzleBox and Corruption
Changed to:
**L, P and C** - stands for Larzuk Quest(and Larzuk Mallus - magic items will still show value of 2 sockets, but you need to know that Larzuk Mallus will give always 1 socket, mechanism is diffrent then Larzuk Quest - Larzuk Mallus description shows correct value of possible sockets which is 1), P is for Puzzle(Piece/Box) and C for Corruption,
* Few small fixes.

Season VI update changes:
* Added new items with accurate descriptions of what they do: Larzuk Mallus and Orb of Fortification,
* Map Tier changes - Maps now show correct values of tiers in their names (rotation of tiers),
* Map Immunes changes - Maps now show correct immunes values (to verify and adjust during the season if needed),
* Runes Descriptions changes - Affected runes: Dol, Ist, Ohm, Ber and Jah,
* New Runewords (Asylum and Shattered Wall) added to Possible Runewords descriptions for correct bases,
* Doom shown as possible Runeword for 5sock Scepters,
* Rift shown as possible Runewerd for 4sock Swords.


## Season V Update:
I made 5 strictness levels, which you can choose directly from in-game settings menu:

* 0 - Show All Items - Default setup for all Filters - Like it say's, It gonna show you every garbage.
* 1 - Hide Just Trash Items - Clear your screen a little bit, hide just junk items
* 2 - Item Filter - More Notify - This one is classic Item.Filter that you all know and love, but with extra notifies for more items - all uniques and sets, low runes, flawlesses etc.
* 3 - Item Filter - Recommended - Classic Filter that most of us were using to this day :) I Recommend you use it, or use option 1 for first days of the ladder.
* 4 - Strict Filter - Something like my current strict filter, but with super health and mana potions
* 5 - Max-Strictness Filter - For EndGame Maniac Farmers - Should show just good stuff.

Those Strict Levels are not perfect for now (but should be fine), and we need to balance them to suit most of our needs, so I really want to hear your feedback.

There is also a change for Crafting Recipes descriptions. I've decided to transfer them from items to Perfect Gems instead. It gonna make our Items much Cleaner and Better! QoL Descriptions updated, all new Items and Runewords Supported!
I would describe it more, but don't have much time lately.
Please report any bugs you gonna notice. I need your Feedback to make it better.

![SeasonV.1](https://i.redd.it/o022vrzios891.png "SeasonV.1")  
![SeasonV.2](https://i.redd.it/saodw48and891.png "SeasonV.2")
![SeasonV.3](https://i.redd.it/4666g25zbeb91.png "SeasonV.3")

Below description is outdated, but filter works still on similar behaviour.

## Some Filter Features:

* Filter adds a lot of **useful NOTES** in item descriptions *(like crafting formulas, socketing and upgrading recipes, possible runewords, usability info etc.)*.  
* Inferior items are always hidden *(except for useful class items with +skills)*.  
* Filter is showing exactly +skills values on all NMAG items, even when item is on the ground *(so you don't have to pick those up to check +skills on them)*.
* Filter highlight useful vendor items to make those easier to catch *(like +3 to Warcries Weapons, Teleport Charges staves, Life Tap Charges wands, +3skill/+20IAS gloves, Trap Claws, etc.)*.  
* Every MAG and RARE WEAPON or ARMOR displays a PRICETAG only when its IDENTIFIED *(so you can know if its wotrh to visit Charsi)*.  
* Good CHARMS have changed names to make those easier to mule and organise in your inventory. *(for e.g. +1 to Warcries Grand Charm gonna be called "Warcries Skiller")*.
* hp and mana potions which are showing on screen depends of difficulty of your game. You gonna see every potions on normal diff. On nightmare only Great +, and on hell only Super and Juvies *(and antidotes)*. Showing gems depends of game difficulty aswell. Perfect Gems drop with chat notify.  
* Gold piles with low amount of gold are hidden  
* You can see most of the items and runeword bases when you are on low lvl. Items gonna dissapear when your character gain more lvls. You gonna see every white item *(RW base)* to lvl 30. Normal tier runeword bases gonna be hidden when you hit lvl 30+. Then you will still see every runeword base *(exceptional and elite tier ones)* until you hit **lvl 80+**. Similar rule counts with every magic/rare item will be shown until you hit **lvl 80+** *(normal tier ones only to lvl 40)*.  

## "EndGame" experience starts when you hit lvl 80+, then:

* Filter will show you only good runeword bases. *(check supported RW bases below)*  
* You gonna see exactly ED values on superior RW bases, exactly RES values on Paladin shields RW bases, exactly +skills values on Class-Specific RW bases.
* You will be able to see magic and rare: Circlets and Class Items like Barb Helms, Druid Pelts, Sorc Globes, Wands, Assasin Claws, Amazon Javelins and:  
* Rare gloves, boots and belts (and since rares are better then in LoD also chests, helmets and shields) and:  
* Every ETH Rare and Magic WEAPONS, and:
* Good magical bases for crafting, and:  
* Potentially expensive (Woth some GOLD) items are shown with a PRICETAG, like 2square in eq throwables, wands, sorc orbs etc.  
* Gold piles only in stacks **5k+**  
* Good Uniques (only when UNID!) will be shown with Chat Notification, Minimap Pin and extra colorful ** **STARS** **, the Best Uniques with extra green note. *(pick up!)*
* Runes Number colors 1-14 and 16-17 TAN, 15 and 18-19 WHITE with extra TAN *, 20-25 RED with extra RED * and chat notification, and 26+ GREEN with extra wide-box with COLORFUL ** **STARS** ** . *(to build some hype)*
* New PD2 items like: WorldStone Shards, Larzuk Puzzleboxes, Maps, DClone parts, etc. are included.

## Supported RuneWord bases:

*List coming soon. Meanwhile you can test it using [FilterBird Tool](https://betweenwalls.github.io/filterbird/?v=PD2).*

# ScreenShots preview:
![ScreenShot 5](https://user-images.githubusercontent.com/63604590/146273870-9d67317f-3ae7-4e0a-8ca1-1ad451d866aa.png "ScreenShot 5")
ver 4.4.1 update
![ScreenShot 1](https://preview.redd.it/55pqcgwugvl61.png?width=1920&format=png&auto=webp&s=b276f3bad428f6ee403ea28b247ab20d73f1ec76 "ScreenShot 1")  
![ScreenShot 2](https://i.postimg.cc/38mfnbD2/1.png "ScreenShot 2")  
![ScreenShot 3](https://i.postimg.cc/3NLF0GfF/2.png "ScreenShot 3")  
![ScreenShot 4](https://i.postimg.cc/mZVwnxZ1/3.png "ScreenShot 4")  

# Futureal version:
![ScreenShot 4](https://i.postimg.cc/y6PrDd5Q/obraz-2021-07-29-192957.png "ScreenShot 6")  
Tweaked for [Futureal](https://www.twitch.tv/futureal) - Less colorful, more Vanilla looking version of the filter. No more "colorful *STARS*" and "PICK UP" things.
Few small changes compararing to orginal item.filter, but still almost the same functianolity and QoL features.

# strict.filter:
![ScreenShot 4](https://i.postimg.cc/QXZjWxXw/compare.png "ScreenShot 7")  
More strict version of a filter for late season farmers.
Filter is pretty much the same for characters below lvl 80, at 80+ diffrences are:
- Keys removed
- Mana and Health potions removed (only juvies and antidotes will be shown)
- Class items (magic and rare) will show only to class which with you are playing
- Rare Helmets removed (circlets are still there)
- Rare uneth Weapons removed
- Magic gloves removed
- Quivers: Only rare Arrows will be shown for all clases
- Expensive/worth some gold items with pricetag removed (RW bases with good +skills still there)
- Armor RW bases (body chests, helmets, shields) showing only when rolled with extra ED%
- Eth Body Chests only with 750+ defence
- Some common RW bases like spirit swords, phase blades w/o ED removed.
- Runes: Only Lem [20]+ will drop chat notify

## in-game settings:
![in-game settings](https://cdn.discordapp.com/attachments/733819970127003688/989897933296136192/LootfilterSettings.png "in-game settings")

# Donate/Support:
![Donate](https://panels-images.twitch.tv/panel-43229886-image-184ad605-0cff-419a-a0cc-665154478819 "Donation Image")  
### **You don't know what to do with your hard earnd money?**

I've got solution to your problem! Waste them by supporting me and my work! Every donations are more then welcome :)  
Link for donations: [PayPal - Click](https://www.paypal.com/donate?business=X7TTETKQ64W6G&item_name=Kryszard%27s+PD2+Loot-Filter&currency_code=USD)

### **Are you young, dumb and broke like I am?**

You can show your gratitude in a diffrent way:  
Follow me on my: [Twitch channel!](https://twitch.tv/kryszard)

### **Thank you!**
