TOTAL ANNIHILATION v3.1 PATCH READ ME   

****************************************************************************************
* Version 3.1 adds many new features to Total Annihilation.  Due to the nature of these *
* enhancements, saved games from versions prior to 3.0 will not be compatible with v3.1 *   
* The v3.1 patch will update any previous version to v3.1.				          *
****************************************************************************************

v3.x NEW FEATURES:

**This patch will only update the newest TotalA.exe file in your Total Annihilation game 
directory or subdirectories.  If you have a newer TotalA.exe file in a backup subdirectory, 
the patch will apply to that file, not your default older TotalA.exe file.  This can happen 
if you have upgraded to version 3.0 and then installed TA: Core Contingency.

1) SHORTCUT KEYS
	CTRL + P	Select all aircraft with weapons
	CTRL + R	Select all radar, radar jammers, sonar and sonar jammers
	CTRL + W	Select all mobile units with weapons except Commander

2) MULTIPLAYER SHARING
Control the resources you share with your teammates and allies using the following 
commands.  These commands can be used in multiplayer by hitting ENTER to bring up 
the message bar on the Main Battle Screen and typing in any of the following phrases 
(toggles on/off):

	+shareenergy		Shares energy
	+sharemetal		Shares metal
	+sharemapping		Shares map information

You can also control the amount of metal and energy shared to your teammates and 
allies by modifying these commands slightly with a numerical value.  X indicates 
the amount of resource left in your reserve.  For example, +setsharemetal 5000 will 
only share metal if you have at least 5,000 in reserve. You cannot set the 
amount of resources you want to keep/reserve any higher than your current storage 
capacity.  Make sure you leave a space between the command and the numerical value.  

	+setshareenergy X	Shares energy while keeping X amount for yourself
	+setsharemetal X	Shares metal while keeping X amount for yourself

3) SHIFT & CONSTRUCTION UNITS
While placing your cursor over any construction unit and then holding down the SHIFT 
key, square outlines may appear on the map.  Green squares represent the build orders 
for the unit currently selected.  Blue squares represent the build orders for all 
other construction units.  These squares can be used as a guideline when queuing up 
build orders for a construction unit.

4) SHIFT & CLOAKABLE UNITS
Placing your cursor over a cloaked unit and then holding down the SHIFT key will display 
a white circle.  This circle represents that unit's minimum cloaking radius.  When an 
enemy unit moves into that radius, the cloaked unit becomes visible.

5) FACTORIES & SQUADS
Select a factory and assign it a squad number.  This can be done by pressing CTRL+1 
through 9.  All units produced by that factory will automatically be assigned to that 
same squad.

6) SELECT ANY MISSION
In version 3.1 the previous "drdeath" cheat has been enabled permanently but the bone 
has been removed.  This function has been added to the New Campaign button.  When the 
New Campaign button is pushed a player can now select any campaign and play any mission 
within that campaign.

7) FEATURE VANISHING
The disappearing of features with some user made maps when games are saved then loaded
back up has been fixed.

8) PHALANX 
The reload time for the Arm PHALANX has been properly set.  

9) AI PATHFINDING

AI pathfinding in Total Annihilation has been modified for the new environments and 
situations people are experiencing since the release of Core Contingency. The problem 
is a combination of four factors. 
 
1. Average map size has increased since the original Total Annihilation was released.  
2. Maze type maps have been added. 
3. Maps with more complex and in general more surface features have been added.  
4. The unit number limit has been increased from the original 200 units.  

All of these factors by themselves do not cause a performance issue, but combined they 
will cause unit pathfinding to become a problem.  We have instituted different pathfinding 
filters that will be run as the demand for pathfinding increases.  The more units that need 
paths, the less complex the filter.  What this really means is that the more units you try 
to move the more varied the path will be that they try to take.  In most situations this 
will increase performance and keep units from acting the way they have in the past.  This 
will not solve the problem for ALL situations.  If you are experiencing problems with AI 
and pathfinding after applying this patch try modifying some of the four variables listed 
above.  Sector 410b and Steel Jungle, both Core Contingency maps, are examples of maps 
where this fix will not improve gameplay unless the unit number limit is lowered.


VERSION 3.x FIXES:

1) Version 3.x includes miscellaneous fixes.

If you encounter any bugs while using this patch, please enter all the 
important information into the bug entry section of
http://www.totalannihilation.com.


***********************************************************************
* Version 3.1 incorporates all fixes and features added in previous   *
* patches.               	                                        *
***********************************************************************

*** Version History ***

V2.0b1 ADDED FEATURES:

1) Multi-player AI - Total Annihilation now offers an AI opponent 
feature in multi-player. In the Battle Room, click on any PLAYER 
button to toggle between UNUSED, BLOCKED and AI player slots. The 
AI player name will reflect the name of the player who added the AI 
opponent.  Each player may add only one AI player. There is no AI option 
in Deathmatch.

NOTE: Depending on the units restricted, the AI may not perform 
optimally when build restrictions are imposed in multi-player.  
 
2) The Battle Room has an added TEAM column. If you want to ally with 
an AI player, you must use the buttons in the TEAM column to form this 
alliance. TEAMs work just like alliances, with the exception that 
TEAMs cannot be broken once the game has started.  When forming a TEAM, 
allied victory is automatically set.

3) The AI will build any new units you have downloaded and installed on 
your machine.  

4) Holding shift while queuing up units to be built from a factory will 
now add 5 units per mouse click.

5) There is a new option to have your units shoot all enemy units and 
structures.  Type +shootall in the chat box to toggle this command on 
and off.

6) The AI has been further enhanced for Skirmish mode.   


V2.0b1 FIXES:

1) The ability for construction units to swap build menus has 
been eliminated.

2) Loading a unit in the process of self-destructing will no 
longer cancel the self-destruct order.

V1.2 ADDED FEATURES:

1) Downloadable Units - Version 1.2 BETA 1 patch is required
to add downloadable units to your game.  Install this patch
before installing a downloaded unit.

2) Taerrors.txt - If a crash occurs, the game will output a 
text file called "Taerrors.txt" into your Total Annihilation 
directory.  Cavedog can use this to help isolate the crash 
bug.  This text can be entered into the bug entry 
section of http://www.totalannihilation.com.


V1.2 FIXES:

1) Standing Order Maneuver Bug - When a unit's standing 
orders are set to maneuver, the unit will now attack its 
target until the target is destroyed. Before this fix, the
unit would return back to its starting location after firing 
once if its target was farther then one screen away.

2) Deathmatch Scorecard - While playing a multi-player
Deathmatch game, the Scorecard kill count now reflects the 
number of enemy Commanders you have killed.  The loss count 
tracks how many times your Commander has been killed.

3) Miscellaneous fixes.



V1.1 ADDED FEATURES:

1) Shortcut keys for sending messages in multi-player:
	During a multi-player game, you can preface a chat 
	messages with an 'a' or an 'e' and your message 
	will only be seen by certain players.

	a	sends message to allies only
	e	sends message to enemies only
	
	Type "," or ";" or ":" in between the shortcut and 
	the message.

	Example:  e:this is the end of you! 
	(This message will only be seen by your enemies.)

2) F4 or spacebar will now bring up the Scorecard in 
Skirmish as well as in multi-player.

3) Type "+switchalt" in the message bar to change the 
squad select from alt(#1-9) to (#1-9).  This changes the 
unit menu call from (#1-9) to alt(#1-9).


V1.1 FIXES:

1) A fix for the invisible unit bug.

2) Two modifications can be made to remedy sound problems 
or crashes relating to old or non-DirectX compatible sound 
card drivers. Download Totala.ini from the Total 
Annihilation website, www.totalannihilation.com, to make 
either of the following modifications:

	*UseWindowsSound  (or -w on the command line)  	
	Use the standard Windows multimedia interface for 
	playing sounds instead of DirectSound.  Set this to 
	1 to use Windows sound, and 0 to use DirectSound. 
	NOTE:  Setting this value to 1 will allow you to 
	play the game if DirectSound does not work properly 
	on your system.  However, the audio quality will be 
	greatly decreased, especially during heavy battles.
	Also, you will not get any audio narration with your 
	mission briefings or any sound in the movies.

	*NoDirectSound  (or -s on the command line)
	Disable the use of DirectSound.  Set this to 1 to 
	disable sound in the game.  Set it to 0 to use sound 
	normally.  Disable the sound if you do not have a 
	sound card or the game crashes while trying to play 
	sounds.

	Copy Totala.ini to the folder containing Totala.exe 
	and set the option you need equal to one.  

	You can also add a switch on the command line to 
	activate these options.

3) A fix that allows different languages to play multi-
player against each other.  Players using a non-English 
version of Total Annihilation should upgrade to the v1.1 
patch before playing a multi-player game against 
another language version.

4) An AI tweak so the enemy Commander is less likely to 
rush your base, unless provoked.

5) The difficulty settings for skirmish mode have been 
adjusted so that the differences between easy, medium and 
hard are more distinct.

6) A fix for the NT sound bug.

7) Miscellaneous improvements.




Copyright*1997-1998 Humongous Entertainment.
