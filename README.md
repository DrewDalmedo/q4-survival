# Quake 4: Survival

A mod for Quake 4 that modifies all the weapons to be Titanfall weapons, along with adding a scoring system.

## Installation

First, download the zip file from the releases section.

After downloading the zip, create a new folder under the root of your Quake 4 installation named `survival`.
Enter into the folder, and extract all the files from the zip you downloaded into it.

### Creating a mod shortcut

By default, launching Quake via Steam or the executable will start vanilla Quake 4.
To start the mod directly, navigate to your Quake installation's root directory and create a new shortcut 
for the Quake4.exe executable.

After doing that, open the Properties of the shortcut. Navigate to the Shortcut tab, and add the following
to the end of the `Target` field:

```
+set fs_game survival
``` 

If you named the directory which contains the mod anything other than survival, make sure to replace the word survival at the end
with the name of the folder.

## List of Modifications

### Movement
The movement speed of the player has been increased from it's default. 

### Weapons
Each of the following weapons has been modified to match a close counterpart from the game Titanfall 2:

- Blaster -> RE-45 Auto
- Machinegun -> Alternator
- Shotgun -> EVA-8 Auto
- Hyperblaster -> EPG
- Grenade Launcher -> Softball Grenade Launcher
- Nailgun -> Spitfire
- Rocket Launcher -> SMR
- Railgun -> Kraber AP

### Scoring
Currently, every kill earned by the player will add 10 points to your total counter. This was not tested beyond the first level,
so your score may reset if / when the player is reinitialized.

