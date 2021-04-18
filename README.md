## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
The following guide describes how to setup Enderal: Forgotten Stories SE for Skyrim VR using Wabbajack.  Wabbajack simplifies the process of downloading all the required mods and patches necessary to play Enderal VR to a single click.  This guide uses a lightweight modlist designed to deliver an optimal VR experience with minimal performance loss.  This modlist was optimized for Virtual Desktop and should perform extremely well when playing the game wirelessly.  Special thanks to the Enderal SE modding team and sasa2727 for the VR patch which makes this guide possible!
	
## Requirements
Project is created with:
* [Skyrim VR](https://store.steampowered.com/app/611670/The_Elder_Scrolls_V_Skyrim_VR/)
* [Enderal SE](https://store.steampowered.com/app/976620/Enderal_Forgotten_Stories_Special_Edition)
* [Wabbajack](https://www.wabbajack.org/#/)
* [Enderal VR Modlist.wabbajack](https://drive.google.com/file/d/13sFAeS4tZOcpeus134k40jzaYedHQIaQ/view?usp=sharing)
* [Premium NexusMods account](https://www.nexusmods.com/)
	
## Installation
1.  Add Enderal SE to your Steam library from [HERE](https://store.steampowered.com/app/611670/The_Elder_Scrolls_V_Skyrim_VR/). The game needs to be in your Steam library but does not need to be installed.
2.  Install a clean copy of Skyrim VR from [HERE](https://store.steampowered.com/app/611670/The_Elder_Scrolls_V_Skyrim_VR/).
3.  Run Skyrim VR one time from Steam and then exit the game.
4.  Download Wabbajack from [HERE](https://www.wabbajack.org/#/) and place "Wabbajack.exe" in a blank folder i.e. C:\Games\Wabbajack (Make sure the path contains no spaces)
5.  Run Wabbajack one time and then exit the program.  
5.  Create a new folder where you wish to install Enderal VR i.e. C:\Games\EnderalVR 
6.  Download "Enderal VR Modlist.wabbajack" from HERE and place it anywhere outside of your Wabbajack folder.
7.  Launch Wabbajack by double-clicking "Enderal VR Modlist.wabbajack"
8.  Under "Installation Location", select the folder you created above under Step \5 and then click the green "PLAY" icon in the lower left. 
9.  Once Wabbajack is done downloading and configuring Enderal VR, navigate to your game folder from Step 5.
10. Copy the contents of \Game Folder Files\ to C:\Program Files (x86)\Steam\steamapps\common\SkyrimVR
11. Launch Mod Organizer 2.  Make sure "SKSE" is selected in the upper left dropdown bar and click "Run" to launch and play Enderal VR!  

## MCM Settings
* Once you start a new game, you can configure your individual Enderal VR mods through the in-game Mod Configuration Menu (MCM).  Most MCM settings can be left as default but the following changes are required:
** VRIK MCM: 
1. Disable "Adjust Held Weapons Position". (Fixes scoped bows)
2. Select Body Holsters > (Scroll down to Left Shoulder Holster) > Untick "Visible" (Prevent your bow from clipping into the edge of your FOV when crouching in real life)  

****************************************************************************************************************
*                                                                                                              *   
*     YOU'RE ALL DONE!  ENJOY ENDERAL: FORGOTTEN STORIES IN VR!  ALL STEPS BEYOND THIS POINT ARE OPTIONAL.     * 
*                                                                                                              * 
****************************************************************************************************************


Noteworthy mods:
* Dear Diary VR and Dear Diary:  Custom paper skin for the SkyUI menu.  Disable to revert back to the classic SkyUI.
* Smaller HUD for VR:  Shrinks HUD and text size for added immersion.  Disable if you prefer having a larger HUD and larger font. 
* VRIK
* Dynamically Disable Eye Adaptation and Bloom: Eliminates "glowing" effects around light sources.  Disable if you prefer bloom effects in VR.
* R.A.S.S.: Enables weather effects in-game including a raindrop effect during storms.  Disable if you dislike these weather effects.
* Bijin skin UNP and CBBE: Smoother skin for NPCs with less blemishes.  Disable if you prefer vanilla skin.
* Replaces spiders with wolfs and bears.  Removes spiders from game for arachnophobic players.  Disable if you want spiders! 

Known issues:
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
* Enderal SE supports language packs which allow the game to be played in Chinese, French, German, Italian, Japanese, Korean, Russian, and Spanish.  You can download the packs here:  https://www.nexusmods.com/enderalspecialedition/mods/1?tab=files.  Install the language pack with Mod Organizer 2 and install it with a unique name i.e. "Enderal SE - German Language Pack" and place it underneath "Enderal SE" and "Enderal SE - Update" in your mod loadout.  Finally, edit the following line "sLanguage=ENGLISH" with the preferred language in the following three files:
** C:\Users\[Username]\AppData\Local\ModOrganizer\Skyrim VR\mods\Enderal SE\Enderal - Forgotten Stories.ini
** C:\Users\[Username]\AppData\Local\ModOrganizer\Skyrim VR\mods\Enderal SE - Update\Enderal - Forgotten Stories.ini
** C:\Users\[Username]\AppData\Local\ModOrganizer\Skyrim VR\mods\Enderal VR - Patch\EnderalVRpatch.ini

## MODS --- SKYRIM INSTALLATION FOLDER
* [The Elder Scrolls V - Skyrim VR](https://store.steampowered.com/app/611670/The_Elder_Scrolls_V_Skyrim_VR/)
* [SKSE VR v2.0.12](https://skse.silverlock.org/)
* [EngineFixesVR v1.20](https://github.com/rollingrock/EngineFixesVR/releases)
* [Binaural 3D Surround Sound for SKYRIM VR v2.3.01]: https://www.nexusmods.com/skyrimspecialedition/mods/26916?tab=files)
* [The Sharper Eye v1.0](https://www.nexusmods.com/skyrimspecialedition/mods/46999/?tab=files)
* [xSHADOWMANx's Dll Loader v1.0.0.4](https://www.nexusmods.com/skyrimspecialedition/mods/3619?tab=files)

## MODS --- MOD ORGANIZER 2
