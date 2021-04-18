## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## Preamble
This guide describes how to configure Skyrim VR to play Enderal: Forgotten Stories SE in VR using Wabbajack.  Note that the ONLY game you need installed on Steam is Skyrim VR.  The new Steam edition of Enderal SE is for flatscreen gaming only.  While VR cannot be added to the Steam edition of Enderal SE, Skyrim VR can be "modded" to successfully load Enderal SE in VR!

Wabbajack simplifies the process of downloading all the required Skyrim VR mods and patches necessary to play Enderal SE in VR to a single click.  This guide uses a lightweight modlist designed to deliver an optimal VR experience with minimal performance loss.  This modlist was optimized for Virtual Desktop and should perform extremely well when playing the game wirelessly.  Special thanks to the Enderal SE modding team and sasa2727 for the VR patch which made this guide possible!

## System Requirements
Minimum:
* CPU: Intel Core i5-6600K or AMD Ryzen 5 1400 or better
* RAM: 8 GB
* OS: Windows 7/8.1/10 (64-bit versions)
* GPU: Nvidia GeForce GTX 970 / AMD RX 480 8GB or better
* STORAGE: 40GB

Recommended:
* CPU: Intel Core i7-4790 or AMD Ryzen 5 1500X or better
* RAM: 8 GB
* OS: Windows 10 (64-bit versions)
* GPU: Nvidia GeForce GTX 3070 or better
* STORAGE: 40GB

## Requirements
* [The Elder Scrolls V: Skyrim VR](https://store.steampowered.com/app/611670/The_Elder_Scrolls_V_Skyrim_VR/)
* [Enderal: Forgotten Stories (Special Edition)](https://store.steampowered.com/app/976620/Enderal_Forgotten_Stories_Special_Edition)
* [Wabbajack](https://www.wabbajack.org/#/)
* [Enderal VR Modlist.wabbajack](https://drive.google.com/file/d/13sFAeS4tZOcpeus134k40jzaYedHQIaQ/view?usp=sharing)
* [Premium NexusMods account](https://www.nexusmods.com/)
	
## Installation
1.  Add Enderal SE to your Steam library from [HERE](https://store.steampowered.com/app/976620/Enderal_Forgotten_Stories_Special_Edition/). The game needs to be in your Steam library but does not need to be installed.
2.  Install a clean copy of Skyrim VR from [HERE](https://store.steampowered.com/app/611670/The_Elder_Scrolls_V_Skyrim_VR/).
3.  Run Skyrim VR one time from Steam and then exit the game.
4.  Download Wabbajack from [HERE](https://www.wabbajack.org/#/) and place "Wabbajack.exe" in a blank folder i.e. C:\Games\Wabbajack (Make sure the path contains no spaces)
5.  Run Wabbajack one time and then exit the program.  
5.  Create a new folder where you wish to install Enderal VR i.e. C:\Games\EnderalVR (Make sure the path contains no spaces)  
6.  Download "Enderal VR Modlist.wabbajack" from [HERE](https://drive.google.com/file/d/13sFAeS4tZOcpeus134k40jzaYedHQIaQ/view?usp=sharing) and place it anywhere outside of your Wabbajack folder.
7.  Launch Wabbajack by double-clicking "Enderal VR Modlist.wabbajack"
8.  Under "Installation Location", select the folder you created above under Step \5 and then click the green "PLAY" icon in the lower left. 
9.  Once Wabbajack is done downloading and configuring Enderal VR, navigate to your game folder from Step 5.
10. Copy the contents of \Game Folder Files\ to C:\Program Files (x86)\Steam\steamapps\common\SkyrimVR
11. Launch Mod Organizer 2.  Make sure "SKSE" is selected in the upper left dropdown bar and click "Run" to launch and play Enderal VR!  

## MCM Settings
Once you start a new game, you can configure your individual Enderal VR mods through the in-game Mod Configuration Menu (MCM).  Most MCM settings can be left as default but the following changes are required:
* VRIK MCM: 
1. Disable "Adjust Held Weapons Position". (Fixes scoped bows)
2. Select Body Holsters > Scroll down to Left Shoulder Holster > Untick "Visible" (Prevents your bow from clipping into the edge of your FOV when crouching in real life)  

# YOU'RE ALL DONE!  ENJOY ENDERAL: FORGOTTEN STORIES IN VR!  ALL STEPS BEYOND THIS POINT ARE OPTIONAL.



## Noteworthy mods:
* Dear Diary VR and Dear Diary:  Custom paper skin for the SkyUI menu.  Disable to revert back to the classic SkyUI.
* Smaller HUD for VR:  Shrinks HUD and text size for added immersion.  Disable if you prefer having a larger HUD and larger font. 
* VRIK
* Dynamically Disable Eye Adaptation and Bloom: Eliminates "glowing" effects around light sources.  Disable if you prefer bloom effects in VR.
* R.A.S.S.: Enables weather effects in-game including a raindrop effect during storms.  Disable if you dislike these weather effects.
* Bijin skin UNP and CBBE: Smoother skin for NPCs with less blemishes.  Disable if you prefer vanilla skin.
* Replaces spiders with wolfs and bears.  Removes spiders from game for arachnophobic players.  Disable if you want spiders! 

## Known issues:
* Your headset and controllers must be active before launching the game or it will not start.
* Cutscenes do not work.  Audio always plays against the SteamVR backdrop.
* No body during tutorial.  This is normal as you do not get an avatar until completing the character creation wizard.
* If the Hero menu doesn't pop up when raising one controller over your head, make sure the Enderal window is active and in focus on the Windows desktop.
* Interrupting and cancelling dialogue with the triggers on your VR controllers may soft lock your game.  A previous saved game must be loaded to continue.
* If you get stuck during quests from animations that do not trigger properly, press "~" with the game in focus on your monitor and type player.tai or enableplayercontrols in the console.
* Loading saved games during the opening tutorial may cause VRIK to glitch out.
* If you need to reset your height in-game, do not run "Floor Fix" thru Open VR Advanced Settings as this may causes problems with VRIK where you get stuck in "Sneak" mode.  Recalibrate your height through the VRIK Calibration Power.  You can do this by selecting the VRIK Calibration Power from the magic menu.
* If melee attacks do not work, delete any references to "fShieldLinearVelocityThreshold" and "fMeleeLinearVelocityThreshold" from the INIs at this location:  C:\Users\[Username]\AppData\Local\ModOrganizer\Skyrim VR\profiles\Default
* If you are playing wirelessly on the Quest 2, you may see a subtle "rectangular box" around the edges of the view where the image becomes blurry outside of the rectangle.  This effect is normal and is caused by foveation used by Virtual Desktop when streaming Enderal VR wirelessly.
* If you have trouble selecting ingredients at alchemy benches, on your left controller be sure to tap the analog stick to the right which should allow you to select ingredients for crafting.
* If you have issues equipping arrows for your bow, you need to reach behind your back in real life to grab an arrow.  This is a feature from the included Simple Realistic Archery mod.
* Note that with the exception of texture mods, mods cannot be safely removed mid-savegame.

## Scoped bows
* For scoped bows, open VRIK MCM and disable "Adjust Held Weapons Position"
* Open INI files and add this text somewhere under the [VRWand] section: fBowHoldOffsetY=-6.6 (Tweaks bows for VR)
* Press "~" with Enderal VR active on your Windows desktop and enter:  Player.AddItem ######## 1

i.e.

Player.AddItem 000CC392 1 (Angi's Bow)
Player.AddItem 000AB705 1 (Bow of the Hunt)
Player.AddItem 0006B9AD 1 (Dravin's Bow)
Player.AddItem 00017059 1 (Firiniel's End)
Player.AddItem 000C0186 1 (Froki's Bow)
Player.AddItem 000F5D22 1 (Gauldur Blackbow)
Player.AddItem 000F652C 1 (Nightingale Bow)

## Supersampling: 
* Supersampling can be done via in-game Supersampling and Contrast Adaptive Sharpening via The Sharper Eye.  Optimal VR settings = In-game Supersampling disabled.  CAS enabled via The Sharper Eye mod. 
* If using The Sharper Eye for supersampling, pressing the HOME key with Enderal VR active on your Windows desktop will open the built-in Reshade UI. Here you can adjust the parameters for Contrast Adaptive Sharpening, Contrast, Brightness, and Color Saturation.  Default settings should be optimal for VR.
* In addition to improving visuals with The Sharper Eye mod, you can continue to supersample Enderal VR through SteamVR, Oculus Tray Tool, or Virtual Desktop.  If playing wired with an HTC/Valve/HP headset, increase your SteamVR resolution above 100% to the maximum resolution your GPU can handle.  If playing wired on an Oculus headset, increase your supersampling as high as your GPU can handle via Oculus Tray Tool.  If playing wirelessly in Virtual Desktop, lock your SteamVR resolution at 100% and set your Virtual Desktop video settings to Low/Medium/High based on your GPU. For optimal Virtual Desktop performance, set your Streaming settings to 60fps @ 80Mbps bitrate with Sliced Encoding enabled.

## Game capture:
* If you want to take screenshots or record footage while in VR, use OBS Studio (https://obsproject.com) with the OBS OpenVR Input Plugin v1.5 (https://github.com/baffler/OBS-OpenVR-Input-Plugin/releases/tag/v1.5).  This will allow you to capture the game in 16:9 at a much higher resolution than what is possible whne capturing the game from either Virtual Desktop or your VR mirror window.

## Language Packs:
Enderal SE supports language packs which allow the game to be played in Chinese, French, German, Italian, Japanese, Korean, Russian, and Spanish.  You can download the packs here:  https://www.nexusmods.com/enderalspecialedition/mods/1?tab=files.  Install the language pack with Mod Organizer 2 and install it with a unique name i.e. "Enderal SE - German Language Pack" and place it underneath "Enderal SE" and "Enderal SE - Update" in your mod loadout.  Finally, edit the following line "sLanguage=ENGLISH" with the preferred language in the following three files:
* C:\Users\[Username]\AppData\Local\ModOrganizer\Skyrim VR\mods\Enderal SE\Enderal - Forgotten Stories.ini
* C:\Users\[Username]\AppData\Local\ModOrganizer\Skyrim VR\mods\Enderal SE - Update\Enderal - Forgotten Stories.ini
* C:\Users\[Username]\AppData\Local\ModOrganizer\Skyrim VR\mods\Enderal VR - Patch\EnderalVRpatch.ini

## MODS --- SKYRIM INSTALLATION FOLDER
* [SKSE VR v2.0.12](https://skse.silverlock.org/)
* [EngineFixesVR v1.20](https://github.com/rollingrock/EngineFixesVR/releases)
* [Binaural 3D Surround Sound for SKYRIM VR v2.3.01](https://www.nexusmods.com/skyrimspecialedition/mods/26916?tab=files)
* [The Sharper Eye v1.0](https://www.nexusmods.com/skyrimspecialedition/mods/46999/?tab=files)
* [xSHADOWMANx's Dll Loader v1.0.0.4](https://www.nexusmods.com/skyrimspecialedition/mods/3619?tab=files)

## MODS --- MOD ORGANIZER 2
[Enderal SE](https://www.nexusmods.com/enderalspecialedition/mods/1?tab=files)

[Enderal SE Update](https://www.nexusmods.com/enderalspecialedition/mods/1?tab=files)

[Enderal SE - Bug Fixes v1.26.2](https://www.nexusmods.com/enderalspecialedition/mods/2?tab=files)

[SkyUI v1.0-beta.4](https://github.com/Odie/skyui-vr)

[JContainers VR v4.1.13](https://www.nexusmods.com/skyrimspecialedition/mods/16495?tab=files)

[moreHUD VR v1.0.4](https://www.nexusmods.com/skyrimspecialedition/mods/33215?tab=files)

[SkyrimVRTools v2.3-BETA](https://www.nexusmods.com/skyrimspecialedition/mods/27782?tab=files)

[Enderal VR - Patch](https://www.nexusmods.com/enderalspecialedition/mods/8?tab=files)

[SKSEVR 2.0.12](https://skse.silverlock.org)

[Dear Diary VR - Paper SkyUI and Categorized Favorites v1.06](https://www.nexusmods.com/skyrimspecialedition/mods/44874?tab=files)

[Dear Diary - Enderal version v2.2.4 (Optionally skip installation for Tab Menu ONLY and extract 'tweenmenu.swf' and overwrite file with same name in above Dear Diary VR mod)](https://www.nexusmods.com/enderal/mods/164?tab=files)

[Menu Mouse Fix v1.1.1](https://www.nexusmods.com/skyrimspecialedition/mods/33414?tab=files)

[Smaller HUD for VR v1.0](https://www.nexusmods.com/skyrimspecialedition/mods/30726?tab=files)

[Dot Crosshair VR v0.8](https://www.nexusmods.com/skyrimspecialedition/mods/17764?tab=files)

[Nemesis Unlimited Behavior Engine v0.84-beta](https://github.com/ShikyoKira/Project-New-Reign---Nemesis-Main/releases)

[Ultimate Combat and Creatures Behaviour compatibility for Nemesis v1.12](https://www.nexusmods.com/skyrimspecialedition/mods/45966?tab=files)

[Spell Perk Item Distributor VR v4.4](https://www.nexusmods.com/skyrimspecialedition/mods/36869?tab=files)

[Simple Offence Suppression - VR v1.1](https://www.nexusmods.com/skyrimspecialedition/mods/41764?tab=files)

[Flinching for VR Magic can trigger flinching v1.361 (Requires Nemesis)](https://www.nexusmods.com/skyrimspecialedition/mods/42550?tab=files)

[VRIK V0.8.1. In-Dev Build 28](https://www.nexusmods.com/skyrimspecialedition/mods/23416?tab=posts)

[VRIK Rift-Index-WMR Controller Bindings V2.1.0 (optional)](https://www.nexusmods.com/skyrimspecialedition/mods/23416?tab=files)

[HIGGS VR v1.1.0](https://www.nexusmods.com/skyrimspecialedition/mods/43930?tab=files)

[Spell Wheel VR v1.1.1](https://www.nexusmods.com/skyrimspecialedition/mods/47630?tab=files)

[EngineFixesVR v1.20 (MemoryManager = false, SelectAllocator = 1 in EngineFixesVR.ini)](https://github.com/rollingrock/EngineFixesVR/releases)

[HapticSkyrimVR - Spellcasting and Enhanced Bow and Melee Feedback SKSE Plugin v1.7.2](https://www.nexusmods.com/skyrimspecialedition/mods/20364?tab=files)

[Simple Realistic Archery VR v1.26](https://www.nexusmods.com/skyrimspecialedition/mods/28524?tab=files)

[Weapon Throw VR v1.3.3](https://www.nexusmods.com/skyrimspecialedition/mods/31374?tab=files)

[Dual Wield Block VR v1.5.2](https://www.nexusmods.com/skyrimspecialedition/mods/28456?tab=files)

[LocationalDamageSKSE VR v0.7.1-BETA](https://www.nexusmods.com/skyrimspecialedition/mods/26447?tab=files)

[No Stagger Mod v1.0](https://www.nexusmods.com/skyrimspecialedition/mods/16335?tab=files)

[Enhanced Ragdoll Accuracy Main File v1.02](https://www.nexusmods.com/skyrimspecialedition/mods/45767?tab=files)

[Scoped Bows SE v1.3.1](https://www.nexusmods.com/skyrimspecialedition/mods/912?tab=files)

[Scoped VR-1-1-1 v1.1.1](https://www.nexusmods.com/skyrimspecialedition/mods/16666?tab=files)

[NavigateVR v1.4](https://www.nexusmods.com/skyrimspecialedition/mods/47174?tab=files)

[Dynamically Disable Eye Adaptation and Bloom v1.2.0](https://www.nexusmods.com/skyrimspecialedition/mods/2135?tab=files)

[DragonbornSpeaksNaturally - Beta v0.21.0-beta](https://www.nexusmods.com/skyrimspecialedition/mods/16514?tab=files)

[Splashes of Skyrim - VR v1.2](https://www.nexusmods.com/skyrimspecialedition/mods/47710?tab=files)

[Pouring Rain v2.0](https://www.nexusmods.com/skyrimspecialedition/mods/6077?tab=files)

[R.A.S.S - Rain Ash And Snow Shaders v3.2.2](https://www.nexusmods.com/skyrimspecialedition/mods/22780?tab=files)

[SkyVRaan - Shimmering VR Waters v1.0.1 (requires .NET 5.0 SDK + Synthesis)](https://www.nexusmods.com/skyrimspecialedition/mods/30571?tab=files)

[Storm Lightning for SSE and VR v1.4.9](https://www.nexusmods.com/skyrimspecialedition/mods/29243?tab=files)

[Basic Dining Set Replacer 1k v1.0](https://www.nexusmods.com/skyrimspecialedition/mods/30055?tab=files)

[Noble Skyrim FULL PACK Performance Edition v5.5.0 (Recommend placing before other texture packs; Remove "whroughgroundmud.dds")](https://www.nexusmods.com/skyrimspecialedition/mods/21423?tab=files)

[Real Mountains Rebuilt v1.2](https://www.nexusmods.com/skyrimspecialedition/mods/3704?tab=files)

[Tamrielic Textures SE 1 Landscapes 1K v1.4.0](https://www.nexusmods.com/skyrimspecialedition/mods/32973?tab=files)

[CC's HQ Caves - 2K v1.1](https://www.nexusmods.com/skyrimspecialedition/mods/8448?tab=files)

[Pine Branches Redone 4K v2.0](https://www.nexusmods.com/skyrimspecialedition/mods/45294?tab=files)

[Embers XD v2.2.1 (delete ESP files)](https://www.nexusmods.com/skyrimspecialedition/mods/37085?tab=files)

[STO - Stars 2K Only small stars v1.0](https://www.nexusmods.com/skyrimspecialedition/mods/4931?tab=files)

[Bijin Skin CBBE 2k Based v1.2.1](https://www.nexusmods.com/skyrim/mods/91953?tab=files)

[Bijin skin Crotch fix CBBE v1.2.2](https://www.nexusmods.com/skyrim/mods/91953?tab=files)

[Myths and Legends VI - The Forgotten One v1.01](https://www.nexusmods.com/enderalspecialedition/mods/25?tab=files)

[EOP SE - Enderal SE Outposts v1.01](https://www.nexusmods.com/enderalspecialedition/mods/18?tab=files)

[Delectable Docks SE v1.2](https://www.nexusmods.com/enderalspecialedition/mods/77?tab=files)

[Riverville Catacombs SE v1.0](https://www.nexusmods.com/enderalspecialedition/mods/80?tab=files)

[EAM SE - Enderal Apothecarii Monastery v1.02](https://www.nexusmods.com/enderalspecialedition/mods/34?tab=files)

[Kolapon's Undead Creatures Replacer v1.2u](https://www.nexusmods.com/enderalspecialedition/mods/64?tab=files)

[Kolapon's Various Creatures Replacers v1.5v](https://www.nexusmods.com/enderalspecialedition/mods/64?tab=files)

[Allow Fast Travel v1.1](https://www.nexusmods.com/enderalspecialedition/mods/42?tab=files)

[Diverse Weather v1.0](https://www.nexusmods.com/enderalspecialedition/mods/70?tab=files)

[Bears of the North v1.1](https://www.nexusmods.com/skyrimspecialedition/mods/47541?tab=files)

[Enderal SE - Bears of the North v1.0](https://www.nexusmods.com/enderalspecialedition/mods/30?tab=files)

[Enderal - Arp v2.12](https://www.nexusmods.com/enderalspecialedition/mods/36?tab=files)

[Creature Replacer Pack v1.1](https://www.nexusmods.com/enderalspecialedition/mods/74?tab=files)

[Enderal - Vatyr v2.21](https://www.nexusmods.com/enderalspecialedition/mods/41?tab=files)

[Boneripper Replacer (Clannfear) v1.0](https://www.nexusmods.com/enderalspecialedition/mods/59?tab=files)

[Pus Beetle Replacer v1.0](https://www.nexusmods.com/enderalspecialedition/mods/48?tab=files)

[Ancestral Spirit Replacer (Variant 2)](https://www.nexusmods.com/enderalspecialedition/mods/60?tab=files)

[Ark Easserspeier - Ark Watersprouts (SE) v1.0](https://www.nexusmods.com/enderalspecialedition/mods/62?tab=files)

[Storeable Phasmalist Talismans v1.0](https://www.nexusmods.com/enderalspecialedition/mods/68?tab=files)

[Celtic Endralean Penny v1.0](https://www.nexusmods.com/enderalspecialedition/mods/71?tab=files)

[Cannons 2K v1.0](https://www.nexusmods.com/enderalspecialedition/mods/63?tab=files)

[Noble Quarter Player Home Redone v1.02](https://www.nexusmods.com/enderalspecialedition/mods/66?tab=files)

[Enderal SE - Crossbows v1.07](https://www.nexusmods.com/enderalspecialedition/mods/4?tab=files)

[Enderal SE - Undercity Arena Fix v.1.0](https://www.nexusmods.com/enderalspecialedition/mods/9?tab=files)

[Craftsman Tools Replacer v1.0](https://www.nexusmods.com/enderalspecialedition/mods/28?tab=files)

[[Unique Armor Sets Replacer Enderal SE v2.1](https://www.nexusmods.com/enderalspecialedition/mods/27?tab=files)

[Practical Armor Replacers v1.0](https://www.nexusmods.com/enderalspecialedition/mods/23?tab=files)

[Dawnguard Heavy Armor (Shadowsteel Brigandine) - SE v2.0](https://www.nexusmods.com/enderalspecialedition/mods/33?tab=files)

[Unique Enderal Uniques SE v2.0](https://www.nexusmods.com/enderalspecialedition/mods/38?tab=files)

[Tharael as Follower and Housemate v1.0](https://www.nexusmods.com/enderalspecialedition/mods/45?tab=files)

[Amanda v1.4.2](https://www.nexusmods.com/enderalspecialedition/mods/15?tab=files)

[Enderal NPC Overhaul - SE version v2.2](https://www.nexusmods.com/skyrim/mods/85455?tab=files)

[Kids of Enderal - SE v1.7](https://www.nexusmods.com/skyrim/mods/93432?tab=files)

[Replace spiders with wolfs and bears v1.0.1](https://www.nexusmods.com/enderalspecialedition/mods/31?tab=files)

### GAME TWEAKS 
* Recommended game settings are listed below.  Note that the above Wabbajack install has already been pre-configured with the following tweaks which are merely listed for reference.

##INI Settings
* INI files are found in C:\Users\[Username]\AppData\Local\ModOrganizer\Skyrim VR\profiles\Default
* These INI files will override any vanilla INI files which are stored in: C:\Users\[Username]\Documents\My Games\Skyrim VR\  
* Recommended INI settings: 
1. Open INI files and add this text somewhere under the [Launcher] section: bEnableFileSelection=1 (Enables mods)
2. Open INI files and add this text somewhere under the [Display] section: iTintTextureResolution=2048 (NPC Overhaul tweak)
3. Open INI files and add this text somewhere under the [VR] section: bAllowVRCheating=1 (Disable bumpback when too close to an object)
4. Open INI files and add this text somewhere under the [VR] section: fVrScale=72 (Tweaks world scale for VR; Typical values are between 72-78)
5. Open INI files and add this text somewhere under the [VRUI] section: fHUDCompassScale=0.5000 (Decrease compass size)
6. Open INI files and add this text somewhere under the [VRUI] section: bPlayVRMeleeWorldImpactSounds=0 (Disable impact sounds; Set to "1" if you like the effect.)
7. Open INI files and add this text somewhere under the [VRUI] section to decrease text size: 
         fActivateRolloverSecondaryScale=10
	 
         fActivateRolloverSecondaryZ=0
	 
         fActivateRolloverSecondaryY=0
	 
         fActivateRolloverPrimaryScale=10
	 
         fActivateRolloverPrimaryZ=0
	 
         fActivateRolloverPrimaryY=0
	 
         fActivateRolloverWandScale=10.0000 
	 
         fActivateRolloverSecondaryScale=10.0000
	 
         fActivateRolloverPrimaryScale=10.0000 
	 
8. Open INI files and add this text somewhere under the [VRWand] section: fBowHoldOffsetY=-6.6 (Tweaks bows for VR)
9. Open INI files and add this text somewhere under the [Particles] section: iMaxDesired=1500 (Tweaks bows for Embers XD)

## In-Game Settings
1. Set Movement speed to 50%
2. Activate "Physical Sneaking" and "Realistic Bow Aiming"
3. Disable "FOV Filter when Moving"
4. Set Super sampling slider to minimum (all the way left)
5. Disable Dynamic Resolution
6. Disable Temporal AA
7. Disable Foliage Shadows
8. Untick “Disable LOD” options and set the Tree Lod slider to max
9. Enable "Skinned trees"
10. Enable "Animated trees"
11. Distance sliders are set to: Item 20%, Actor 20%, Objects 40%, Grass 100%

## SkyVRaan Configuration 
* SkyVRaan adds shimmering water effects to the game.  SkyVRaan has been pre-configured with Wabbajack but the configuration process has been documented below for reference. 
1. Close Mod Organizer 2 if open
2. Create a blank Skyrim.ini file in C:\Users\[Username]\Documents\My Games\Skyrim VR\ (Not sure if this is necessary)
3. Install .NET SDK 5.0 and remove any previously installed .NET runtimes.  You can confirm .NET SDK 5.0 is properly installed by running the following from your command prompt:  dotnet --info
4. Launch MO2 and select Tools > Executables > Add an executable ("+" icon in upper left) > Add from file > Navigate to C:\Program Files (x86)\Steam\steamapps\common\SkyrimVR\Data\Synthesis\ > Select Synthesis.exe > OK
5. Right click on "Overwrite" in the left window pane and select: Clean Overwrite > OK. (If applicable, this option may not be available if your overwrite folder is already clean)
6. Select Synthesis from upper right drop down and click RUN
7. Select Skyrim VR
8. Select Git Repository (2nd icon in upper left) 
9. Search for SkyVRaan and select the "+" icon next to SkyVRaanAutoPatcher and SkyVRaanWeatherPatcher
10. Click RUN icon
11. Wait for the utility to report "Completed" and close Synthesis
    --If Synthesis errors out when patching SkyVRaan, try the following:
    --Select SkyVRaanAutoPatcher and SkyVRaanWeatherPatcher in the left hand bar and set "Mutagen" and "Synthesis" to "Latest".
    --Click "Skyrim VR" in the top bar.  Under Data Folder Location, enter the following path: C:\Program Files (x86)\Steam\steamapps\common\SkyrimVR\Data
12. Right click on "Overwrite" and select "Create Mod".  Enter a custom name i.e. Synthesis output and click OK.
13. Tick "Synthesis output" in left window pane and make sure "Synthesis.esp" is at the bottom of your Plugin load order and ticked in the right window pane.
14. Select SKSE in the upper right drop down bar
15. Click RUN to launch and play Enderal VR with SkyVRaan activated!
16. You may need to re-run this process if you change your load order.

## Flinching installation
* Flinching adds flinching animations to NPCs.  SkyVRaan has been pre-configured with Flinching but the configuration process has been documented below for reference. 
1. Launch MO2 and select Tools > Executables > Add an executable ("+" icon in upper left) > Add from file > Navigate to C:\Program Files (x86)\Steam\steamapps\common\SkyrimVR\Data\Nemesis_Engine > Select Nemesis Unlimited Behavior Engine.exe > OK
2. Right click on "Overwrite" in the left window pane and select: Clean Overwrite > OK.  (If applicable, this option may not be available if your overwrite folder is already clean)
3. Select Nemesis Unlimited Behavior Engine from upper right drop down and click RUN
4. Click OK for both Warning popups
5. Click "Update Engine"
6. Tick the "Flinching Animations" option and click "Launch Nemesis Behavior Engine"
7. Wait for the process to finish and then close the Nemesis Unlimited Behavior Engine.
8. Right click on "Overwrite" and select "Create Mod".  Enter a custom name i.e. Nemesis output and click OK.
9. Tick "Nemesis output" in left window pane 
10. Click RUN to launch and play Enderal VR with Flinching activated!  NPCs will now react with an animation when attacked with your right fist or melee weapons in either hand.
11. You may need to re-run this process if you change your load order.

## Mod Organizer 2 Settings
Required Mod Load Order (left side):
* Enderal SE
* Enderal SE - Update
* Enderal SE - Bug Fixes
* SkyUI
* JContainers VR
* moreHUD VR 
* SkyrimVRTools
* Enderal VR patch

Required Mod Load Order (right side):
* Enderal Forgotten Stories.esm
* Enderal SE - Bug Fixes.esp
* SkyUI_SE.esp
* AHZmoreHUD.esp
* EnderalVRpatch.esp
* (everything else; Enderal SE specific mods should be placed near the bottom)
* Synthesis.esp (Generated with the Synthesis utility and should be placed near the bottom) 

When installing mods, if prompted to extract BSA files, select "No".

   ---If using EngineFixesVR, add the following lines to EngineFixesVR.ini: MemoryManager = false, SelectAllocator = 1
   ---If using EmbersXD, SMIM or USSEP patches, delete any .esp files.
   ---If using Noble Skyrim, remove "whroughgroundmud.dds"
   ---If using Dear Diary, install the VR version and replace "tweenmenu.swf" with the file from the Enderal version of the mod.
   ---If using SkyVRaan, this mod requires the .NET 5.0 SDK and will not be active until Synthesis is run (as described at the beginning of this guide).
   ---If using Flinching, this mod will not be active until Nemesis is run (as described at the beginning of this guide).
