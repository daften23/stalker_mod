S.H.O.O.T.E.R. v0.8 by Daften_23

1. The mod

The mod is a complete overhaul of STALKER: Shadow of Chernobyl's gunplay, in-game economy and progression system without adding radically new features to the game or altering the story in any way.
Shadow of Chernobyl plays a lot easier and a lot more like other shooter games with this mod installed. This mod was intended for anyone first jumping into the series or revisiting it.
The mods is dependent on two other mods, these are:
-	Original Weapons Renewal 3 for SOC by r_populik (see full credits on ModDB)
-	Repair Kits Revamped by barak1001
For S.H.O.O.T.E.R. to work you must install these two mods beforehand, see 3. Installation below.
	
		!EXPECT FURTHER DEVELOPMENT; THIS IS NOT A FINAL RELEASE!

2. Changes

	2.1 GUNPLAY:

		Weapon accuracy was raised across the board
		Uniform damage depending on caliber and round fired
		Weapons were balanced with a mixture of realism and sandbox roles
		Repair Kits Revamped integration allows for weapon repairing
		EXOTIC weapons are classified as such thanks to their real-life rarity, a new source of income for the player is to sell these weapons
		Decreasing weapon condition does not impact accuracy
		Pistols received uniform accuracy and were balanced by magazine size, caliber and rate of fire
		Common weapons are great all-rounders but exotic weapons fill certain niches better
		Low-crouch increases accuracy while moving decreases it. Handguns receive no such movement penalty to encourage their usage
		Enemy AI was modified to fire in semi-automatic at long range, at a maximum of three round burst at medium range and can do full-auto magazine dumps at closer ranges
		Bullet penetration of objects was removed due to inconsistencies with materials and AI
		Recoil system is introduced
		Fire modes were removed in favor of more defined sandbox roles and proper recoil patterns

	2.2 ARMOR & OUTFITS:

		Jackets now give no bulletproof resistance but offer increased carry weight and good protection against mutant attacks
		Environmental suits offer no bulletproof protection and can deteriorate easily but offer maximum radioactive resistance.
		Armors are classified into four categories: Light; Medium; Hazard (combination of environmental suits and light armor); Heavy (SKAT9-M); Exoskeleton
		Repair Kits Revamped integration allows for armor repairing
		Every armor offers 100% bulletproof resistance but depending on its sub-class it can deteriorate faster therefore it’s unable to protect reliably from a few rounds

	2.3 PLAYER:

		Running and sprinting speeds were greatly reduced
		Carry weight has a smaller impact on stamina
		Player is more resistant to gunfire than NPCs because of the increased rates of fire and damage output
		Default carry weight is reduced
		Bleeding now heals by itself at a really slow rate
		All difficulty levels were taken into account during balancing, pick the difficulty you feel the most comfortable at during gunfights as other variables are the same across the board
		The player will experience hunger after 4-5 hours of in-game time

	2.4 AI:

		AI hearing and vision is greatly nerfed to allow for some form of stealth
		AI accuracy was buffed, they now fire semi-automatically at long, semi-auto to three round bursts at medium and fully-automatically at close range; at close range they can fire until their magazine runs dry
		Headlamps were removed due to inconsistencies with stealth balance
		Can’t see trough objects and bushes unless alerted, use this to your advantage
		Pain and death sounds range were greatly reduced
		Player movement sounds were greatly reduced
		Suppressed weapon sounds were greatly reduced
		Mutant health buffed because of the increased firepower
		Human enemies are now very vulnerable to gunfire
		NPC loadouts and weapons carried were modified to fall in line with the Exotics system
		Weapons now can be “gifted” to NPCs; any weapon or ammo sold to them has a value of 0 RU making it easier to equip allies with better weapons

	2.5 ENVIRONMENTS & MISSIONS

		Some items and stashes were modified to introduce weapons, armor and artifacts at later stages of the game.
		Some mission rewards were modified

	2.6 TRADE & ECONOMY

		Traders are not try to rip you off (as much)
		Each trader in the game specializes in different gear; SIDOROVICH – Early game gear, mostly suitable for Rookie stalkers and loners; BARMAN – Generic dealer of everything but offers the worst price out of all traders; ECOLOGIST – The only artefact buyer, not interested in guns & ammo or armor; DUTY – Best source of Eastern Block weapons; FREEDOM – NATO gear dealer

	2.7 ARTEFACTS
		
		Artefacts now have uniform weaknesses, they make the player lose stamina and develop hunger faster
		Stacking artefacts speeds up the hunger and stamina loss, use them when the situation calls for them
		For the best effects try to stack artefacts from the same family (draining radiation, increasing bullet resistance)
		Reliance on them is completely optional and mostly became situational


3. Installation

	The mod was made with merging in mind and it will not work without the other two mods installed first

	First download Original Weapons Renewal 3 for SOC from the link below

	https://www.moddb.com/mods/original-weapons-renewal-3-for-soc/downloads/owr3-soc

	Install the mod by simply copy & paste it’s components into S.T.A.L.K.E.R. Shadow of Chernobyl\gamedata folder

	Now download -Repair Kits Revamped 1.04.2 from the link below

	https://www.moddb.com/mods/repair-kits-revamped/downloads/repair-kits-revamped-1042
	
	Install the mod by simply copy & paste the components from the Stalker – No Mods folder into S.T.A.L.K.E.R. Shadow of Chernobyl\gamedata folder and let everything overwrite

	Now navigate to S.H.O.O.T.E.R. and copy and paste all the files into the S.T.A.L.K.E.R. Shadow of Chernobyl\gamedata folder while again overwriting everything

	Now navigate to S.T.A.L.K.E.R. Shadow of Chernobyl\ and find the file named “fsgame.ltx” find the line starting with $game_data$ and change the two false variables to true

	$game_data$   		= false|		false|	$fs_root$|		gamedata\
	$game_data$   		= true|		true|	$fs_root$|		gamedata\

	The mod is now installed, it REQUIRES a NEW GAME to be started for the spawns to take effect.
