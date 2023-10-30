# Overkill RPG

## Welcome to Overkill RPG

In this RPG, we have crafted a fun idle game you can play with other members of the server.

We are still looking for suggestions and ideas, if you have ANY at all, PLEASE let us know in ⁠📨-game-suggestions

If you want to CHAT, Have questions, or anything along those lines, please go to ⁠🍻-the-tavern to communicate with others.

Whenever you see a command in this guide, you can type !help COMMANDNAME for more information about it.

To start an adventure, use `!adventure` or `!a`. Reaction will appear underneath the text of the adventure randomly selected for your group. Use 🗡Attack to attack the monster, 🗨Talk to talk with the monster, ✨Magic to use magic on the monster, 🙏Pray to pray to the god Akatosh, or 🏃Run to try to run from the fight. Along with your choice of attack style, you can also use a ⚛Special Action to use your special ability (Depending on your Character Class.) The more people helping the easier it is to defeat the monster and acquire its loot.


## Monsters, Adventures, and the Numbers

When an adventure is over, an output of the outcome is displayed. Sometimes the numbers won't seem to match up - why did that owlspider resist your 1,000 magic damage that you threw at it - and the output says 680 damage instead? Each monster has a resistance table where they could be resistant to magic like in this example, and it mitigated a good chunk of the attack. Having a balanced group across all classes is where adventure really shines - physical and magical damage is combined in adventures, and charisma stands alone in its persuading power to turn the fight around without fighting. Successful prayers by clerics over large groups augment damage of both damage types. If a group defeats an adventure on "both sides" of the damage (both physical+magical and diplomacy) the rewards are greater for the whole group.


## Items

Items can be looted from loot chests received from a successful adventure or bought from a Trader Cart that appears in chat. 

Going from least to most powerful, generally the progression is normal < rare < epic < Legendary < Ascended < Set.
Forged items are a Tinker's specialty.
Event items can be created by a bot owner as a special reward to hand out to specific users for bot events or other incentive-based rewards.

```ansi
{Event:''Event items look like this''}
{.:'Forged items look like this':.}
{Set:''Set items look like this''}
{Ascended:''Ascended items look like this''}
{Legendary:'Legendary items look like this'}
[epic items look like this]
.rare_items_look_like_this
normal items look like this
```


## Hero/Heroclass

Classes can be chosen at level 10 by using `!heroclass` in the #stats-inventory channel. Available classes are Tinkerer, Berserker, Wizard, Cleric, Ranger and Bard. A prestige class called Psychic is available at Rebirth level 30 (more on the rebirthing system below).  

Main Stats: Attack (ATT/ATK), Charisma/Diplomacy (CHA/DIPL), Intelligence (INT)  
Minor Stats: Dexterity (DEX), Luck (LUCK/LUK)  

While each class has a main stat that benefits them more than others, Dexterity and Luck benefit everchest!y class. Dexterity can lessen your repair bills after a failed adventure and help your hero get critical hits, while luck can benefit the outcome of special attacks, reduce cooldown times, augment critical strikes, affect loot chest outcomes, and reduce the price of items.

**Tinkerers** can forge two different items into a device bound to their very soul.  
Special ability: Use the `!forge` command. (Can forge items into new quality, causing them to increase in stats) 
* Forge together two items in your backpack to potentially make an incredibly powerful random item. 
 - Intelligence and Luck affects this class cooldown and forged items
Preferred stat: INT  
At 30 rebirths, Tinkerers can forge Ascended-level items.

**Berserkers** have the option to rage and add big bonuses to attacks, but fumbles hurt.  
Use the `!rage` command when attacking in an adventure. (Invokes RAGE during battle causing the player to go insane with strength!)
* Causes a large amount of ATK-based/Physical-based damage.
 - Attack, Luck and Dexterity directly affect this characters damage abilities
Preferred stat: ATK  
Rebirths provide not only a base bonus to attacks as Berserkers grow stronger, but they augment critical strike chance and attack value.  

**Clerics** can bless the entire group when praying.  
Use the `!bless` command when fighting in an adventure. (Supports the team with a blessing/prayer ability to create a higher chance of evading being injured in battle)
* Bless your groups' damage by invoking your deity. The more people that are participating, the harder the deity smites their foes... if they choose to help.
 - Intelligence and Luck affects this class cooldown and prayers
Preferred stat: INT  
Every 15 rebirths a Cleric recieves another +1 to their successful prayer damage multiplier.  

**Rangers** can gain a special pet, which can find items and give reward bonuses.  
Use the `!pet` command to try to catch a pet companion. Pet catching can be spammy, so `!pet` can be run in DMs.  
`!pet forage` sends a pet to search for items, and `!pet free` will free your companion in case you wish to try your hand at capturing something that brings in more gold and loot from fights.  
* Catch one of over 900 randomly-generated pets in search of the legendary beasts rumored to exist...
 - Pets can give varied bonuses such as increased currency drop and increased XP
Preferred stat: CHA for charming pet companions and enemies, or ATK for pure damage  

**Wizards** have the option to focus and add large bonuses to their magic, but their focus can sometimes go astray...  
Use the `!focus` command when attacking in an adventure. (focus the team to help in battle!)
* Causes a large amount of Int-based/Magic-based damage.
 - Intelligence and Luck affects this class cooldown and damage spells
Preferred stat: INT  

**Bards** can perform to aid their comrades in diplomacy.  
Use the `!music` command when being diplomatic in an adventure. (Plays music to cheer up the team and/or attempt to put the monsters to sleep!)
* Buffs other Charisma-using players when attacking.  
 - Intelligence and diplomacy directly affects this class cooldown and persuasion attempts
Preferred stat: CHA  
Rebirth levels can buff the base value of the bard's attack.  

**Psychics** can show the enemy's weaknesses to their group allowing them to target the monster's weak-points.  
Use the `!insight` command in an adventure. (This allows a Psychic to expose the current enemy's weakeness to the party) 
* A successful insight into an enemy's weak points during an adventure can turn the tide on difficult encounters.
 - Intelligence and Luck affects this class ability to reveal more information from an enemy.
Preferred stat: INT


### Rebirths
- Users have the ability to rebirth at max level.
- Can be used to reset a character back to level 1
- Upon rebirthing your character gains increase base points to all stats
- The number of points for rebirthing varies based on the number of total rebirths your character has
  - Between 1 - 9 rebirths you get 2 base stats per rebirth
  - Between 10 - 19 rebirths you get 1 extra base stats per rebirth
  - Between 20 - 29 rebirths you get 5 extra base stats per rebirth
  - After 30 rebirths you get 3 extra base stats per rebirth
- Characters are guaranteed some item chests after their rebirth
  - 1 common chest per 5 rebirths they have
  - 1 rare chest per 10 rebirths they have
  - 1 epic chest per 20 rebirths they have
  - 1 legendary test per 50 rebirths they have
#### Mechanics affect by rebirths
As your rebirths increases the following will change
- The amount of XP you gain for activities will also increase
- The amount of currency you gain for activities will also increase
- You will get better items from loot chests
- The amount you sell items for will be higher
- Characters with more rebirths will be more likely to encounter stronger monsters that will rebirth more XP
- Character with more rebirths will be able to convert lesser loot chest into higher quality loot chests
- Characters with more rebirths will have their skill cooldowns significantly reduced
- Characters can only trade items to other users with the same or higher number of rebirths.
#### How to rebirth
- When your character reach max level they can run `!rebirth`
- This will cost all their current currency
- This will remove all their items with the following exceptions
  - Set items will stay with you forever
  - Tinkerer items will stay with you as long as you are a tinkerer
  - Legendary items will stay with you for 3 rebirths after you get them
     - Say you get a legendary item with you on level 30 Rebirth 3, this item will stay with you until your 6th rebirth
  - Any loot chests or other items you has prior to rebirthing will be removed
  - You will keep your class upon rebirthing (Say Hello to level 1 Berserkers)
### Max Level
- New dynamic Max levels based on number of rebirths your character has.
  - For character with 0 rebirths the max level is 5
  - For character with 1 rebirth the Max level is 25
  - For character with 2 to 9 rebirths the max level increases by 5 per rebirth (25, 30, 35...)
  - For character with 10 to 19 rebirths the max level increases by 10 per rebirth (70, 80, 90...)
  - For character with 20 to 38 rebirths the max level increases by 5 per rebirth (170, 175, 180..)
  - For character with more than 38 rebirths the max level will always be 255-1000
- Characters will stop gaining XP once their character reach max level.


## Mechanics
- Saturday and Sundays users will gain 2x XP and currency (Subject to change)
- Wednesday and Friday users will gain 1.5x XP and currency (Subject to change)
- Monster Stats affect the number of XP/currency it drops if you manage to kill it
- A character with a higher number of rebirths has a chance of spawning stronger monster
- Adventure shows the total number XP the whole party gets
- Each user gets different XP amounts based on their rebirths and stats
- The repair cost at the end of failed adventure is a percentage of your total balance
- Character stats affect their skill cooldown
- The number of people taking part in an adventure directly increases the amount of XP/currency that adventure rewards
- You are unable to join an adventure without any currency and will require at least 250 of your local currency.
- Randomly, A Trader will show up in #adventuring with a cart full of items available for purchase!!!
- Trader will have a much more varied number of items in his inventory and on some lucky hauls he may even have several items for sale.

Sometimes a traveling merchant cart will roll past offering new items for adventurers to buy or loot chests to purchase. Carts have roughly a 3h return time, but can be anywhere from 3-24hours. The merchant can be found wandering around in the #adventure channel.


# The Negaverse

You can use the #negaverse channel to use the !negaverse command, which gives you the option to try to pay for experience, with a high risk/high reward factor involved.

Commands for the #treasury channel are as follows:
!apayday (Collect your daily payday with a 24hour cooldown)
!loot (Check the loot you have collected in your adventures)
!loot QUALITY (Replace QUALITY with the type of loot you want to open) Ex. !loot epic (will open 1 epic loot crate) (Another example - !loot quality # -- This will open # amount of specified quality loot crates)

Commands for the #character-growth channel are as follows:
!backpack or !ebackpack (Shows EQUIPABLE GEAR TO YOUR LEVEL)
!stats (Character stats)


## Commands for Players (Restricted to specified channels)

Below is a list of all the commands, including the channels they are limited to, and a small example of what each command does. For more information, type !help COMMANDNAME, ex. !help loot

# #stats-inventory commands
- !loadout - Set up gear sets or loadouts
- !loot [box_type=None] [number=1] - This opens one of your precious treasure chests.
- !mysets - Shows your sets.
- !rebirth - Resets your character level and increases your rebirths by 1.
- !setinfo - Shows set bonuses for the specified set.
- !skill - Allows you to spend skillpoints.
- !stats - This draws up a character sheet of you or an optionally specified member.
- !unequip - This stashes a specified equipped item into your backpack.
- !backpack - This shows the contents of your backpack.
- !cbackpack - Complex backpack management tools.
- !convert - Convert norm, rare, or epic chests to the next quality chest(s).
- !ebackpack - This shows the contents of your backpack that can be equipped. Give it a rarity and/or slot to filter what backpack items to show. Note: An item degrade level is how many rebirths it will last, before it is broken down.
- !equip - This equips an item from your backpack.
- !heroclass - Allows you to select a class if you are level 10 or above. For information on class use: !heroclass classname info.
- !forge (Tinkerer - Can forge items into new quality, causing them to increase in stats)

# #adventuring commands
- !adventure (alias - !a) - This will send you on an adventure in which others can participate in.
- !bless (Supports the team with a blessing/prayer ability to create a higher chance of evading being injured in battle))
- !focus (Wizard - Focuses the team to help their stats in battle!)
- !insight (Pyshic - This allows you to expose the current enemy's weakeness to the party)
- !music (Bard - Plays music to cheer up the team and/or attempt to put the monsters to sleep!)
- !pet (Ranger - Hunts for new pets, which automatically help in battle (Sub commands are !pet forage (To forage for items) and !pet free to release your pet to the wild))
- !rage (Berserker - Invokes RAGE during battle causing the player to go insane with strength!)

# #treasury commands
- !apayday - Get your free payday gold!
- !atransfer - Transfer currency between players!
- !forge (Tinkerer - Can forge items into new quality, causing them to increase in stats)
- !loot [box_type=None] [number=1] - This opens one of your precious treasure chests.

# #negaverse commands
- !negaverse <offering> (Alias !nv <offering>) - This will send you to the a nega-member!

# #leaderboards commands
- !nvsb - Show's the Negaverse scoreboard.
- !aleaderboard - Prints the OVERALL leaderboard.
- !scoreboard - Prints the scoreboard (Can be organized by Wins/Losses/Stats/Fumbles, etc.)
- !wscoreboard - Print the WEEKLY scoreboard.

## More Advanced Commands for Players

`[p]backpack disassemble` (Used in #stats-inventory channel.)
* Take apart an unused piece of gear to try to get something good out of it. This complex command also uses the same argparse-style command structure that `[p]cbackpack` does - I recommend reading https://github.com/BTNGaming/adventure/blob/main/docs/cbackpack.md for more information.