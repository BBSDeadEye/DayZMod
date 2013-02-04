FIX DUE : 2013

	Community Notes: 
		* DayZ 1.7.5.1
		
	Affected addons:
		* dayz_code  
		* dayz_anim		


	Community Change log:
	
	* [UPDATED]	- STR_ITEMWATERBOTTLEBOILED_CODE_DESC - German (Eine Flasche mit abgekochten Wasser)
	* [UPDATED]	- STR_ITEMWATERBOTTLEBOILED_CODE_DESC - French (Une bouteille a �t� remplie d'eau bouillie qui peut �tre consomm�e.)
	* [UPDATED] - HMMWV Cargo space. (transportMaxWeapons = 4;, transportMaxMagazines = 12;, transportmaxbackpacks = 4;)
	
	* [FIXED] - HMMWV Should now be able to be repaired fully.
	* [FIXED] - Gut object should be working without errors.
	* [FIXED] - Repair option should now only work on vehicles.
	* [FIXED] - AS50 was mistable banned now unbanned.
	

FIX DUE : 2013

	Community Notes: 
		* DayZ 1.7.5
		
	Affected addons:
		* dayz_code   
		* dayz_anim
		* dayz_server (server admins only)
		* mission (server admins only)
		

	Community Change log:
		Client:
			* [Prerequisites]	beta-patch ((Newest)).
			* [Prerequisites]	Microsoft Visual C++ 2010 SP1 x86 Redistributable (http://www.microsoft.com/en-us/download/details.aspx?id=8328)
			* [Prerequisites]	New Mission File Downloaded from (http://www.silentspy.net/utility/dayz/mission-generator/)
			
			* [NEW]	Weapon - Sa58P_EP1. (Military)
			* [NEW]	Weapon - Sa58V_EP1. (Military)
			* [NEW]	Weapon - Sa58V_RCO_EP1. (MilitaryS)
			* [NEW]	Weapon - Sa58V_CCO_EP1. (MilitaryS)
			* [NEW]	Weapon - G36C. (HeliCrash)
			* [NEW]	Weapon - G36C_camo. (HeliCrash)
			* [NEW]	Weapon - G36A_camo. (HeliCrash)
			* [NEW]	Weapon - G36K_camo. (HeliCrash)
			* [NEW]	Weapon - M40A3 (MilitaryS)
			* [NEW] Vehicle - HMMWV_DZ.
			* [NEW] Vehicle - MH6J_DZ.
			* [NEW] - Ability to flip ATV's.
			* [NEW] - Zeds spawn while in vehicles.
			* [NEW] - Zeds now have the ability to damage vehicles. This is limited to glass only once glass is destroyed players within will be damaged.
			* [NEW] - Zeds now have the ability to pull you from open vehicles.
			* [NEW] - New Load screens added.
			* [NEW] - Chopper weapons can now be reloaded.
			* [NEW] - UH60Wreck added
			* [NEW] - New zed & loot spawn systems rewrote Phase 1.
			* [NEW] - Revamped GUI icons to now empty as you lose the relevent item (blood,food,water) Thanks Des
			* [NEW] - Infection changes when eating food and drinking water. (tin and canned items don't count)
			* [NEW] - Epeen monitor added to display player stats. (Zombies Killed, Headshots, Murders, Bandits Killed, Humanity) - Press Scroll Lock to use
			* [NEW] - Toolbox is now needed to build Wire,tanktrap.
			* [NEW] - Etool is now needed to build Sandbags.
			* [NEW] - 5 New types of food ("FoodmuttonCooked","FoodchickenCooked","FoodBaconCooked","HIDDEN","FooedRabbitCooked").
			* [NEW] - 4 New Raw food. ("FoodbaconRaw","FoodchickenRaw","FoodmuttonRaw","foodrabbitRaw")
			* [NEW] - Bloodbags can now give an infection.
			* [NEW] - Added moving combat roll (KK's Volt).
			* [NEW] - Survived Dayz added to Epeen monitor.
			
			* [NEW] - Cutting down trees now attracts zeds.
			* [NEW] - After you have eatern a canned product you now get an empty tincan back.
			* [NEW] - Added definition of arrays for meatraw / meatcooked
			* [NEW] - You can now eat raw meat (low hp add + possible infection), and Coocked meat (high hp add w/o infection)
			
			* [NEW] - RawMeat blood values (beef-100,rabbit-400,bacon-150,chicken-100,mutton-100).
			* [NEW] - Cookedmeat blood values (beef-600,rabbit-1600,bacon-400,chicken-400,mutton-400).
			
			* [NEW] - You can now boil water using a fire,TrashTinCan or ItemSodaEmpty and fullwaterbottle
			* [NEW] - Water (possible infection), and Boiled Water (w/o infection)
			

		
			* [UPDATED] - BAF_L85A2_RIS_CWS replaced with BAF_L85A2_RIS_Holo. (HeliCrash)
			* [UPDATED] - Added a much faster login process. (Advantages: Login Speed up)
			* [UPDATED] - Limted amount of ammo found with weapons.
			* [UPDATED] - Gender selection images updated thanks Des.
			* [UPDATED] - Updated infection chance during zed attacks from 1/1000 to 1/500.
			* [UPDATED] - Changed Loot tables to increase the supply of Antibiotic drops.
			* [UPDATED] - Combat Mode is now affected by everything you do and everything done to you (example any kind of damage).			
			* [UPDATED] - Updated Mi17_DZ and UH1H_DZ to max ammo Max 100 rounds per gun.
			* [UPDATED] - UH1 Crash sites no longer all spawn on server start but throughout the game.
			* [UPDATED] - Damage processing for zombieattacks with prebuilded weighted arrays. (Advantages: speedup and saves a lot of cpu cycles)
			* [UPDATED] - Much faster fn_instring.
			* [UPDATED] - Cargo space redo.
							MI17_DZ ( transportMaxWeapons = 10;, transportMaxMagazines = 50;, transportmaxbackpacks = 10; )
							UH1H_DZ ( transportMaxWeapons = 5;, transportMaxMagazines = 25;, transportmaxbackpacks = 4; )
							AH6_DZ ( transportMaxWeapons = 3;, transportMaxMagazines = 10;, transportmaxbackpacks = 2; )
							Mh6J_DZ ( transportMaxWeapons = 3;, transportMaxMagazines = 20;, transportmaxbackpacks = 0; )
							AN2_DZ ( transportMaxWeapons = 10;, transportMaxMagazines = 80;, transportmaxbackpacks = 15; )
			* [UPDATED] - CZ_VestPouch_EP1 to be more useful 12 slots 0 weapon slots.
			* [UPDATED] - Zeds will talk to other zeds within 80 meter.
			* [UPDATED] - Combat Logging is now active during Zombie chase.
			* [UPDATED] - Backpacks updated. (https://github.com/R4Z0R49/DayZMod/wiki/Backpacks)
			* [UPDATED] - Animal Meat reset. 6(cow),4(goat),4(sheep),4(boar),2(Hen),1(Rabbit)
			* [UPDATED] - Epeen monitor moved to scroll lock key and work started on moving to diary
			* [UDDATED] - Massive cleanup remove all useless files.
			* [UPDATED] - Redone all public EH's
			* [UPDTAED] - Combat/zombie logout + anti-duping overhall - (https://github.com/R4Z0R49/DayZMod/commit/44321a6856f5fd2d5544d1293c2450f9b2df6fbd)
			* [UPDATED] - String tables to include = English, German, Russian, Spanish, Dutch, French
			* [UPDATED] - All base class's have been updated to match the dayz removal proc's (weapons)

			* [Fixed] - Zeds hearing should now be fixed.
			* [Fixed] - Temperature icon color now ranges from iceblue (cold) to red (hot)
			* [Fixed] - German Tranlations updated.
			* [Fixed] - mi17 gunner seat is now fixed (you no longer stand outside)
			* [Fixed] - Bloodbag glitch fixed.
			* [Fixed] - UH1Y_DZ animation issues.
			* [Fixed] - Infection is now fixed loss of blood 3 per sec (will not drop below 3k blood)
			* [FIXED] - Epeen monitor animation should now work correct without the fps drop.
			* [FIXED] - DZ_Czech_Vest_Puch backpack class config. (Warning Message: No entry 'bin\config.bin/CfgMagazines.DZ_Czech_Vest_Puch'.)
			* [FIXED] - Variable spelling mistakes hsould be corrected now.
			* [FIXED] - Moved all new foods to stringtable.
			* [FIXED] - Fixed infection chance when giving blood.(No longer applys to player giving blood) :-(
			* [FIXED] - ALT F4 Sync issue now fixed
			* [FIXED] - Pause menu can no longer be assigned to mouse keys to bypass respawn.

			
			* [REMOVED]	- BAF_L85A2_RIS_CWS (Based on poll)
			* [REMOVED]	- Banned m136 as it never really worked and served no real purpose.
			* [REMOVED] - In Combat bot removed while we work on speed improvements.
			* [REMOVED] - Peripheral Vision. (Peripheral Dots)
			* [REMOVED] - MPTable Removed.
Removed from dev branch during devlopment.
			* [REMOVED] - Axes now have a small chance to fail due to them being blunt (others later) 9% Chance. ** Can still be used as weapon **
			* [REMOVED] - Matches can now run out (others later) 9% Chance. (at this time this is a random chance)
			* [REMOVED] - Knife will now have a chance to go blunt causing it to give less food from gutting animals 9% chance(Blunt), 50% less food(Guting)
			* [REMOVED] - You can now longer apply more then one bloodbag per 10 mins per player
			* [REMOVED] - You can no longer regain blood from cooked food for 1 hour after eating. (ie spamming cooked meat to regain hp)
			* [REMOVED] - No longer need tool box to place bear traps.
			* [REMOVED] - You can no longer consume food while your not hungry (within 3 mins of eating)
			* [REMOVED] - You can no longer drink while your not thirsty (within 3 mins of drinking)
			* [REMOVED] - 6 New items added to loot tables. (Inplace of item lockup or braking)
			* [REMOVED] - Food models removed
			
		Hive:
			* [Prerequisites]	beta-patch 99806 - Pending updated to newest version.
			* [Prerequisites]	Microsoft Visual C++ 2010 SP1 x86 Redistributable (http://www.microsoft.com/en-us/download/details.aspx?id=8328)
			
			* [NEW] - Added new constraint to block non Dayz items from being wrote to the db

			* [UPDATED] - Publish Object will now only publish items allowed. (tents, other deployables)
			* [UPDATED] - Updated Basic SQL Procs.

			* [Fixed] - Crash issue on stale child calls

			* [REMOVED]	



    Upstream hive (public hive):

______________________

FIX : 21 NOVEMBER 2012

	Community Notes: 
		* V1.7.4.4

	Community Change log:

		* [Prerequisites]	beta-patch 98866.
		* [Prerequisites]	Microsoft Visual C++ 2010 SP1 x86 Redistributable (http://www.microsoft.com/en-us/download/details.aspx?id=8328)
		* [Prerequisites]	New Mission File Downloaded from (http://www.silentspy.net/utility/dayz/mission-generator/)
		
		* [NEW]	class Mi17_TK_EP1 Now Unbanned. (Mi17_DZ)
		* [NEW]	An2_TK_EP1 Now Unbanned.(AN2_DZ)
		* [NEW]	AH6X Now Unbanned. (AH6X_DZ)
		* [NEW]	BAF_Offroad_D Now Unbanned.
		* [NEW]	BAF_Offroad_W Now Added.
		* [NEW]	Fully Removed Save button from action menu.
		* [NEW]	New combat mode icon (G17) thanks Alexander.
		* [NEW]	Gender section screen thanks F0rt.
		* [NEW]	You can no longer place tents in ponds.
		* [NEW]	Disabled greeting menu .
		* [NEW]	Disabled radio messages to be heard and shown in the left lower corner of the screen.
		* [NEW]	General speed up of the login process.
		* [NEW] (*.2 Hotfix)Added some Anti-cheat.
		* [NEW] (*.3 Hotfix)Added local copy of cert if it cant get one online, version checks.


        * [UPDATED] Combat Logging "Fired Near" checks are now limited to 8 metre radius.
		* [UPDATED] Combat Logging "Projectile Near" Have now been removed while we look for a less intensive way to track projectiles.
		* [UPDATED] Combat Logging is now removed on death.
        * [UPDATED] Corrected legs and hands fractures they must be set with actual value.
		* [UPDATED] (*.1 Hotfix)Updated hive .dlls to fix a reconnect issue with prepared statements.
		* [UPDATED] (*.1 Hotfix)Increased m107 loot chance to 0.02. 
		* [UPDATED] (*.1 Hotfix)Lowered As50 loot chance to 0.01
		
		* [Fixed]	Adding checks for female skin humanity/login.
        * [Fixed]   Adding female skin to variables.
        * [Fixed]   Fixed Parachute so jumping out of choppers won?t kill you.
        * [Fixed]   Event Handle for wrecked choppers this should allow the smoke on wrecks to work all the time.
        * [Fixed]   Event Handle for Vehicles this fix's problems with local vehilce damage calls..
        * [Fixed]   Remove objects from DB by objectID and objectUID only. (Should fix Deployable problems)
        * [Fixed]   Debug menu options are no longer editable.
        * [Fixed]   Locked Singleplayer Menu
		* [Fixed]   (*.1 Hotfix) Players with high CharacterID weren't dying properly.
		* [Fixed]   (*.2 Hotfix) Fixed 2nd Parachute removal issue.
		
        * [REMOVED]	Damaged logging to .rpt removed all traces of dmg to a player.
        * [REMOVED]	An2_1_TK_CIV_EP1 Got removed during testing devs felt it lacked purpose in the game.
        * [REMOVED]	An2_2_TK_CIV_EP1 Got removed during testing devs felt it lacked purpose	in the game.
        * [REMOVED]	MV22 Got removed during testing devs felt it lacked perpose in the game.
        * [REMOVED]	S1203_ambulance_EP1 Got replaced during testing to a hmmv class vehicle.
		* [REMOVED]	BAF_L85A2_RIS_CWS From Loot table.
		* [REMOVED]	UH60_wreck_EP1.
		* [REMOVED] HMMWV_Ambulance_CZ_DES_EP1 Removed due to its heal abilty.
		* [REMOVED] Dogs Removed while we rewrite the hud and correct a few other issues. (attak, Getin/out of vehicles)
		* [REMOVED] UH60M_MEV_EP1 Removed due to its heal abilty.
		* [REMOVED]	(*.4 Hotfix) Street Lights Removed.


    Upstream hive (public hive):
        Adjusted the respawn rates of vehicles. Previously all vehicles had pretty long respawn time making them a bit too rare.
        Still requires a server restart for vehicles to show up in-game.
        * [UPDATED] Destroyed low-end (boats, bicycles) vehicles now respawn after 3h.
        * [UPDATED] Destroyed medium-end (normal cars, motorcycle, quads) vehicles respawn after 12h.
        * [UPDATED] Destroyed high-end ( aircraft, all-terrain) vehicles respawn after 24h.
        Note: Respawn rates are our recommended rule set, they may differ on some private hive servers.

______________________

### UPDATE : 31th OCTOBER 2012

	Affected addons:
		* dayz_code		1.7.3
		* dayz_server 	(server admins only)
	

	Community Changelog:
		Client:
		* [NEW]		Tents can no longer be placed on concrete.
		* [FIXED]	Building checks for tent placement (No longer place tents in buildings).
		* [FIXED]	Tents now are one click place.
		* [FIXED]	Fixed function for checking if in buildings.
		* [UPDATED]	Vehicle repair menus now all replaced.
		* [NEW]		Vehicle menus now list all damaged parts no matter if you have the item or not.
		* [NEW]		Vehicle repair menus will now let you know the exact item you need to repair on failed repair attempts.
		* [FIXED]	Vehicle Damage is now fully working.
		* [FIXED]	Vehicle Killed is now in effect fully destroyed vehicles will now set correct in db.
		* [FIXED]	Tents Now add and remove from db.
		* [FIXED]	Food can no longer be consumed if the player does not have in inventory.
		* [FIXED]	water can no longer be consumed if the player does not have in inventory.
		* [UPDATED]	Updated UI control bug.
		* [NEW]		Toolbox is now needed for all repairs.
		* [NEW]		Alt-f4 is now locked and will only open your status menu.
		* [Fixed]	No longer possible to drink/eat/pitch a tent/put on clothes/build sand bags/cat wire/hedgehogs/consume medical supplies/free filled water without consuming the item.
		* [FIXED]	No longer possible to create axes out of thin air if you already have one
		* [FIXED]	Switching skins no longer repairs pain shakes/broken legs/resets/dupes/screws/resets ammo
		* [FIXED]	Duping no longer possible through zombie corpses/etc
		* [FIXED]	It should now be impossible for a new players spawns to spawn unconscious.
		* [FIXED]	You can no longer cook infinite free meat from camp fires
		* [FIXED]	Survivors should no longer pickup a single item at the same time and both receive it.
		* [FIXED]	You can no longer generate multiple tents while packing up a deployed tent.
		* [FIXED]	You can no longer change clothes/eat/drink/etc. while in a vehicle
		* [NEW]		combat 30 sec timer on all combat actions.
		* [UPDATED]	ItemWire reduced from 0.06 to 0.01
		* [UPDATED]	PartEngine updated from 0.01 to 0.06
		* [UPDATED]	Version info is now displayed correct
		* [NEW]		New Combat System If you fire a weapon, then you go into combat.  During combat, "ABORT" is disabled. (Need to look at the effects with high player counts)
		* [NEW]		Combat 30 sec timer on all combat actions.
		* [FIXED]  Zombie death animation is delayed (now it plays instantly)

		Server:
		* [NEW]		HiveEXT.dll updated with new optimized version that supports both private and public hive.
		* [NEW]		Official public Hive login is now hard coded into the .dll (Outgoing TCP port 80 and 3306 has to be allowed to use public hive)
		* [NEW]		New Hive can now set ingame time to custom, local(local server time), static
		* [FIXED]	Object Gear syncs happen based on radius not just on menu.
		* [FIXED]	Vehicle Position is now updated with client position.
		* [FIXED]	Vehicles save fuel properly
_____________________________________

### HOTFIX : 6 SEPTEMBER 2012

	Affected addons:
		* dayz 			1.something.somethingelse
		* dayz_code		1.7.2.6
		* dayz_server 	(server admins only)
	
	Developer's Note: 
		* To change your DayZ UI options, go to OPTIONS > GAME OPTIONS > DayZ UI. This will only affect the DayZ UI elements, unfortunately it is not saving to the config file so each time you restart ArmA2 you will need to change this setting.
		* DayZ UI Debug option might not always work properly. deal-with-it.jpg

	Changelog:
		* [NEW] 	Bear trap has chance to spawn on infected hunters
		* [FIXED] 	Graphical glitches with dead bodies (Bodies should now not display graphical glitches)
		* [NEW]		Three UI options available: Default (indicators only), Debug (indicators + debug window), None (only base ArmA2 UI)
		* [FIXED] 	Converting between magazine types resets ammo count (Now only contains previous number of rounds)
_____________________________________

### HOTFIX : 8 AUGUST 2012

	Affected addons:
		* dayz_code		1.7.2.5
		* dayz_server 	(server admins only)
	
	Developer's Note: 
		* 

	Changelog:
		* [FIXED] 	Ammunition amounts not loaded in properly (Now records used ammunition correctly)
		* [FIXED] 	Graphical glitches with barbed wire (Rebinarized file should no longer produce graphical artifacts)
		* [NEW] 	Additional optimizations to login process (further use of publicVariableClient to reduce network transmission)
		* [FIXED] 	Respawn button not enabled when legs fractured (Now enables for fractured legs https://dev-heaven.net/issues/39161 )
		* [FIXED] 	Excessive logging of player data in server logs (Disabled https://dev-heaven.net/issues/38784 )
		* [FIXED] 	Graphical glitches with dead bodies (Rebinarized file should no longer produce graphical artifacts)
_____________________________________

### HOTFIX : 26 JULY 2012

	Affected addons:
		* dayz_code		1.7.2.4
		* dayz			1.3.2
		* dayz_anim		0.5
		* dayz_server 	(server admins only)
	
	Developer's Note: 
		* Should be used with Build 95310 and above on 1.62
		* 5 second timeout on disconnect is NOT implemented, as the engine is preventing it currently

	Changelog:
		* [NEW]		Respawn button is disabled during DayZ play
		* [NEW]		Optimized authentication process on login
		* [NEW]		Singleplayer mode disabled when DayZ is loaded
		* [NEW]		DayZ Logo and Version Number appear in game when DayZ is loaded
		* [NEW]		Hive now tracks login/logout (to assist in analysis for an ALT+F4 solution)
		* [FIXED]	Infected cannot hear weapon firing (now they actually hear again)
		* [FIXED]	Clothing no longer spawning (now it spawns as it used too)
		* [FIXED]	Tents and items with ID's above 1 million don't syncronize (now it should syncronize, players to confirm)
		* [NEW]		Respawn button is enabled if the player has a fracture
		* [FIXED]	Players switched to non-player skins (by hackers) sync to database (updates no longer saved for objects non-authorized skins)
		* [NEW]		Players spawning in debug area or "water world" will spawn on beach on next login (with their gear)
		* [NEW]		Client will automatically spawn player out of debug and waterworld to last known position
		* [NEW]		Radar removed from helicopter (UH1H will be added back to vehicle spawns)
______________________________________

### UPDATE : 13 JULY 2012

	Affected addons:
		* dayz_code		1.7.2.2
		* dayz_anim		0.4
		* dayz_server 	(server admins only)
	
	Developer's Note: 
		* Make sure you run ArmA2 Beta build 94759 or above

	Changelog:
		* [FIXED]	Ghillie and skin removal on login ( https://dev-heaven.net/issues/36666 )
		* [FIXED]	Arma X stuck on loading screen ( https://dev-heaven.net/issues/36647 )
		* [FIXED] 	AKS_74_kobra classname incorrectly named ( https://dev-heaven.net/issues/36680 )
		* [NEW]		Server side performance tweaks and improvments
		* [FIXED]	Infected detect players from too far away (reduced by about 20%)
		* [FIXED]	Disconnect updates not being correctly applied (caused inventory issues)
		* [FIXED]	Bear traps not appearing for spawn (low spawn)
______________________________________

### HOTFIX : 10 JULY 2012

	Affected addons:
		* dayz_code		1.7.2.1
		* dayz_anim		0.3.1
		* dayz_server	(only for servers)
	
	Developer's Note:
		
	Changelog:
		* [FIXED]	Infected attack those they cannot see ( https://dev-heaven.net/issues/36375 )
		* [FIXED]	Wearing clothes makes you invisible ( https://dev-heaven.net/issues/36371 )
		* [FIXED]	New authentication method causing lockups on full servers (Reverted use of publicVariableServer)
		* [FIXED]	Pressing ALT key caused spamming of server sync ( No longer spams for sync'ing a character )
______________________________________

### UPDATE : 9 JULY 2012

	Affected addons:
		* dayz_code		1.7.2
		* dayz			1.3.1
		* dayz_equip	1.3.4
		* dayz_anim		0.3
		
	Developer's Note:
		
	Changelog:
		* [FIXED]	Infected hear perfectly through objects (noise reduced by 50% through an object)
		* [FIXED]	Animal bodies despawn way too fast (now despawn automatically after 2 minutes)
		* [FIXED]	Corrupted update data causes people to spawn in debug forest (now will not save corrupted position data)
		* [FIXED]	States where animal might stop walking around (now should walk around more)
		* [FIXED]	Animal AI routines consuming large amounts of FPS (now in line with Infected AI routines, reduced FPS usage)
		* [NEW]		Player Syncing system replaced (increased performance and ammo quantity tracking)
		* [FIXED]	Error reports are almost invisible (has now been fixed)
		* [FIXED]	Daylight calculations causing slight FPS issue
		* [NEW]		Visibility now smoothly alters based on sun, moon, cloud, rain, and fog state
		* [NEW]		Aubility now dampened in rain and increased by fog
		* [FIXED]	Object cleanup causing significant (huge) performance issue on servers (reduced by up to 50%, means more players + zombies possible)
		* [FIXED]	Use of "allMissionObjects" causing performance issue on clients (new engine command "entities" used to improve FPS on clients)
		* [FIXED]	Too easy to break legs due to infected (reduced probability of leg damage, reduced amount of leg damage)
		* [FIXED]	Inspection of dead bodies does not work (fix only applies with ArmA2 Beta 94033 and above)
		* [NEW] 	Exponent driven probability introduced into visibility calculation
		* [FIXED]	Hatchet/Crowbar requires reloading ( https://dev-heaven.net/issues/34903 )
		* [FIXED]	Unlimited Wire fence/Sandbag/Tank Trap Bug ( https://dev-heaven.net/issues/34283 )
		* [FIXED]	Duplication Exploit on object pickup ( https://dev-heaven.net/issues/34031 )
		* [FIXED]	Not full magazines disappear when you reconnect ( https://dev-heaven.net/issues/33998 )
		* [FIXED]	Dead bodies still have the heart beat for low humanity ( https://dev-heaven.net/issues/35050 )
		* [NEW]		Set Bear Traps that break player and infected legs, kills animals, when activated
		* [NEW]		Authentication process streamlined with new ArmA2 Beta commands (publicVariableServer and publicVariableClient)
		* [NEW] 	Authentication for duplicate IDs supportive of the new beta patch (ArmAX users)
	
______________________________________

### HOTFIX : 20 JUNE 2012

	Affected addons:
		* dayz_code		1.7.1.5
		* dayz_equip	1.3.3
		* dayz_weapons	1.3.2
	
	Developer's Note:
		* A designation of [NEW] doesn't necessarily mean a new feature, 4chan, it means a change in operation not directly related to a bug. Could be for better performance or rebalancing.
		
	Changelog:
		* [NEW]		Infected raycast for line-of-sight less often (improves performance)
		* [FIXED]	Infected can see through terrain ( https://dev-heaven.net/issues/33787 )
		* [FIXED]	Raycasting being taken from wrong body position (ensured it is from eye level)
		* [FIXED]	Infected sometimes spawn close to a player (previous check once, now up to ten times)
		* [NEW]		Infected bodies will despawn after 5 minutes of their death (improves performance)
		* [FIXED]	Sometimes infected will stand still after loosing line-of-sight ( https://dev-heaven.net/issues/33715 )
		* [FIXED]	Can dupe tent's by right clicking (forgot to close the window)
		* [FIXED]	Poor performance caused by infected search behavior (MAJOR performance increase during closed testing)
		* [FIXED]	Audibility is far to high (completely rebalanced, in line with how it was in previous updates)
		* [FIXED]	Can dupe food during cooking if click really fast (now you cannot)
		* [FIXED]	Trying to pick up a hatchet would create fake ammo (now will not)
		* [FIXED]	Hatchet takes up too much room (can now be transferred between toolbelt and primary slot through gear action)
		* [REVERT]	Hatchet now collected as an Item (toolbelt) and can be equipped to primary (gear action)
		* [NEW]		Flashlights can now be packed to toolbelt also (gear action)
		* [NEW]		New players will spawn with flashlight added to their toolbelt not backpack
		* [FIXED]	Infected sometimes not inspecting thrown items (they will walk to the location of a noise, 20-40m away)
		* [FIXED]	Unlimited Infected spawning (now has a cooldown enabled so it won't spawn too many at once)
		* [FIXED]	Melee weapon sounds non-existent/terrible (now has placeholder sounds)
______________________________________

### HOTFIX : 19 JUNE 2012

	Affected addons:
		* dayz_code		1.7.1.4
		* dayz_equip	1.3.2
		
	Changelog:
		* [FIXED]	Performance issue with equipment proxies (improves FPS)
______________________________________

### HOTFIX : 19 JUNE 2012

	Affected addons:
		* dayz_code		1.7.1.3
		* dayz_weapons	1.3.1
		* dayz_server 	(server admins only)
	
	Developer's Note:
		* Requires ArmA2 Beta.
		* Big thanks to JoeKurtz for his excellent bug reports
	
	Changelog:
		* [FIXED]	Melee items causing magazine glitching and eventual server death (fixed)
		* [FIXED]	Unconscious UI Image displays incorrectly
		* [FIXED]	Bleeding never stops unless bandaged (chance of spontanious bleeding stopping now works)
		* [FIXED]	Interior infected spawning inside of building walls etc... (interior infected now spawn inside correctly)
		* [FIXED]	Speed not correctly utilized for checking stealth levels ( https://dev-heaven.net/issues/33630 )
		* [FIXED]	Posture error can occur on stealth check ( https://dev-heaven.net/issues/33628 )
		* [FIXED]	Config error messages on popup (Caused by legacy classnames, error handling implemented to prevent this)
		* [FIXED]	Unable to repair helicopter fuel leak (repair all parts to 95% or above and fuel leak will stop)
		* [FIXED]	Massive lag and desync on some servers (mostly caused by the invisible replicating magazines)
		* [REVERT]	Nerf of sickness damage (now will reduce your blood to 6000 rather than 10000)
		* [FIXED]	Losing blood from starvation/dehydration cannot receive transfusion ( https://dev-heaven.net/issues/33677 )
		* [FIXED]	Hunger and Thirst no longer continue to drop while you are offline (only ingame time counts)
		* [NEW]		Once infected lose line-of-sight they will try investigate where you are
		* [FIXED]	Flies still heard around removed/hidden bodies ( https://dev-heaven.net/issues/33472 )
		* [NEW]		Significant loot rebalancing
		* [FIXED]	"Fus ro dah" melee (now should be the correct release files)
______________________________________

### HOTFIX : 19 JUNE 2012

	Affected addons:
		* dayz_code		1.7.1.2
		* dayz_weapons	1.3
		* dayz_equip	1.3.1
		* dayz_server 	(server admins only)
	
	Developer's Note:
		* YES: I know this hotfix has content in it. It was content that didn't make it into the last update, and some of the fixes are bundled with this content, so it was easier to release the content than try to remove it.
		* Requires ArmA2 Beta.
		* NOTE: VERY IMPORTANT: MELEE WEAPONS ARE QUITE UNDER POWERED CURRENTLY. THEY WILL BE ADJUSTED UPWARDS OVER THE NEXT FEW WEEKS. EACH HAVE DIFFERENT DAMAGE VALUES.
		* ALSO NOTE: Melee is just in testing. They may not stay, they are just being tested to see how they perform. They are missing their sound effects, and tweaking of effects also.
	
	Changelog:
		* [NEW]		Tone Mapping to enhance nightlighting conditions
		* [FIXED]	Generic Loot not spawning (such as food etc...)
		* [FIXED]	Animals stand still and HURR DURRR (they now walk around)
		* [FIXED]	New blood values not being saved when a player eats (they do now)
		* [FIXED]	Duplicate players not being removed (should now be removed on login)
		* [NEW]		Melee Weapon introduced: Hatchet (can only drop through right click in gear menu)
		* [NEW]		Maximum animals increased
		* [NEW]		Melee Weapon introduced: Crowbar (can only drop through right click in gear menu)
		* [NEW]		Double Barrelled shotgun sound
		* [FIXED]	Gender assignment broken (working correctly)
______________________________________

### HOTFIX : 17 JUNE 2012

	Affected addons:
		* dayz_code		1.7.1.1
		* dayz_server	(only for server admins)
	
	Developer's Note:
		* Performance issues were associated with loot cleanup not working. This has been fixed.
		* Each time you start a new character, you will get the gender selection dialog.
		* INFECTED AND LOOT RESPAWN IS STILL QUITE BUGGED. NEEDS ALOT OF WORK. BUT IT SHOULD BE MANAGEABLE NOW.
	
	Changelog:
		* [FIXED]	Server item cleanup error (thanks Dwarden for identifying)
		* [FIXED]	Server weighted random object error (thanks Dwarden for identifying)
		* [REVERT] 	5 second delay for disconnecting (will need to wait till new method developed)
		* [REVERT] 	Disabling of interior raycasting (will mean some buildings you will be invisible/can't be hit in for the moment as they don't have view LODs)
		* [REVERT]	Infected sight based on head not body direction (infected glace around alot, this meant that they had super view directions. Now locked at body direction)
		* [FIXED]	Area not checked for existing infected before spawning new ones ("blind faith" that it had not made a mistake didn't work)
		* [FIXED]	Crippling performance issues caused by loot items never being cleaned up (loot now cleaned up)
		* [FIXED]	Tent pitching (Who the hell codes tent location checks TWICE before pitching? Oh apparently I do)
		* [NEW]		Marakov spawn rate increased
		* [NEW]		Small chance Mararov ammo will spawn on an infected
		* [FIXED]	Converting magazines didn't work if you had MORE than one of that magazine type (now works as intended)
		* [NEW]		Tweaked audibility and visibility values for kneel walking
		* [REVERT] 	Secret nerf of prone (you noticed)
		* [NEW]		Can select gender for each new character
		* [FIXED]	Toolboxes aren't spawning (classname error in loot table)
		* [NEW]		Small tweaks to AI zombie routines to improve performance
		* [REVERT] 	New spawn timer mechanism (back to the old one for now)
		* [FIXED]	Infected will stay in one place after losing line-of-sight (now will loiter)
______________________________________

### UPDATE : 17 JUNE 2012

	Community Shout-out this update:
		www.armaholic.com
		One of the community websites hosting anything and everything ArmA2. You thought DayZ was good? Well, it is just the tip of the iceberg.
		You can download missions, vehicles, addons, even other total conversions. And it's all FREE!
		Run by foxhound who also happens to be a cool guy

	Affected addons:
		* dayz_code		1.7.1
		* dayz_sfx		1.2
		* dayz			1.3
		* dayz_equip	1.3
		* dayz_weapons	1.2
		* dayz_anim		0.2
		
	Developer's Note:
		* Requires ArmA2 Beta.
		* Raytracing doesn't work so well inside some buildings at the moment so interiors will ignore raytracing
		* Infected sprinting animation not included yet
		* On respawn, your flashlight spawns in your BACKPACK. I did this because nothing would have said NOOB more than all the new players running around in the day with torches with no idea what the fuck to do.
		
	Changelog:
		* [FIXED]	Wire Spools, Toolboxes, hedgehog (tank trap) kits not spawning
		* [FIXED]	Bodies still being deleted too quickly sometimes
		* [FIXED]	No backpacks or medical boxes spawning
		* [FIXED]	"No Speaker..." debug report spam
		* [FIXED]	Infected spawning too close to players (minimum 30m now)
		* [FIXED]	Infected not spawning inside buildings any more
		* [FIXED]	General Server Script Errors (big thanks to Dwarden for fixing these!)
		* [FIXED]	Loot/Infected spawning time delay desync'ing with server
		* [NEW]		Infected can't attack through walls
		* [NEW]		Infected can't see through objects any more
		* [NEW]		Infected visibility increased (but limited by LOS)
		* [NEW]		Infected attack range increased (but limited by LOS)
		* [NEW]		Infected can cause greater damage when they hit you
		* [NEW]		You can hide from an infected chasing you
		* [NEW]		Optimized server cleanup routine
		* [NEW]		Player body exists for five seconds after disconnect (UNCONFIRMED IF WORKING)
		* [NEW]		Infected see based on eye direction, not on body direction as before
		* [NEW]		30Rnd_545x39_AK added to loot table
		* [NEW]		More infected attack animations
		* [NEW]		More infected feeding animations
		* [NEW]		Replaced monkey infected crawing run animation
		* [NEW]		Heartbeat when cursor on a player with very low humanity (heart beats faster the lower it is)
		* [NEW]		Humanity GUI indicator removed
		* [NEW]		New Infected and Action sound effects (more AWESOME stuff by Michael Manning)
		* [NEW]		Initial version of double-barreled shotgun added (by Artyom)
		* [FIXED]	CZ550 spawning far too often in farms
		* [FIXED]	Winchester decreased spawnrate (% given to double barrel shotty)
		* [NEW]		Recombine shotgun rounds between 2 and 8 rounds
		* [NEW]		Recombine 45ACP rounds between M1911 and Revolver rounds
		* [FIXED]	Tent placement is completely screwed (now can place anywhere except in building)
		* [FIXED]	Items for Eating and Drinking not removed instantly (allowed some duping)
		* [NEW]		DayZ: Now with additional cruelty! Spawn with only a bandage, painkillers, and a torch.
______________________________________

### UPDATE : 27 MAY 2012

	Affected addons:
		* dayz_code		1.7.0
		
	Changelog:
		* [FIXED]	Long (sometimes infinite) loading times
		* [FIXED]	Saving sometimes will not happen
		* [FIXED]	Vehicles not initialized reliably on servers running multiple instances
		* [FIXED]	Very poor framerate on servers after some time (dead bodies causing it)
		* [NEW]	 	Server Side Architecture completely rewritten
______________________________________

### HOTFIX : 24 MAY 2012

	Affected addons:
		* dayz_code		1.5.8.4
		
	Changelog:
		* [NEW]	 	Support for more than 1,000,000 characters
______________________________________

### UPDATE : 27 MAY 2012

	Affected addons:
		* dayz_code		1.6
		* dayz_equip	1.2.5
		* dayz_weapons	1.1.2
		* dayz			1.2.6
		* dayz_sfx		1.1.2
		
	Developer's Note:
		* To collect firewood, you can either find it in loot piles, or go into a forest and use the hatchet (gear > Right Click). I will expand this mechanic but its enough for now.
		* You get a ONE TIME OFFER to change your player gender!
		* Only two types of new skins are available in this update, "Camo" and "Ghillie Suit" in addition to normal survivor
		* Skins a player is wearing are NOT lootable.
		* When you change skin (right click on clothing package in inventory) your old skin will appear in inventory
		* If you want a players skin, you will need to make them take it off first
		
	Changelog:
		* [FIXED]	Bodies being deleted immediately (now will stay around for 15 minutes)
		* [FIXED]	Player profiles sometimes corrupting and causing stuck in loading issues (error handling by engine)
		* [FIXED]	Temperature listed in percent and not degrees (now displayed in degrees)
		* [FIXED]	Loosing temperature inside vehicles (now will slowly gain or be static in vehicles)
		* [FIXED]	ItemPainkillers popup error (no longer happens: thanks Norbert!)
		* [FIXED]	Spawning in Ocean when switching models (player morphing optimized by TeeTime)
		* [FIXED]	Loosing gear when switching models (player morphing optimized by TeeTime)
		* [FIXED]	Wrong M107 is spawning on occasion (Correct one spawns)
		* [FIXED]	Crashed heli uber-loot not spawning (does now thanks to GhostBear!)
		* [FIXED]	Wire Fencing Kit caused graphical glitches (new model)
		* [FIXED]	Tank Trap Kit caused graphical glitches (new model)
		* [FIXED]	Invisible character models occuring (No longer invisible models)
		* [FIXED]	Panic not being activated (Your character will sometimes panic)
		* [FIXED]	Blood washout sometimes not being displayed (now will always wash out color depending on blood level)
		* [NEW]		Hatchet for chopping wood in forests
		* [NEW]		Wire Fencing kit model by Artyom Troshin
		* [NEW]		Tank Trap kit model by Artyom Troshin
		* [NEW]		Construction options moved to items in gear menu (right click wire fencing kit to use etc...)
		* [NEW]		Hospital Loot Spawn probabilities changed
		* [NEW]		Players can choose to be a female survivor (once only per CD-Key)
		* [NEW]		Heat packs for increasing temperature in an emergency
		* [NEW]		Bandit Skin transition for low humanity is removed
		* [NEW]		Players will receive an error message if the server they are on is running an incorrect HIVE version
