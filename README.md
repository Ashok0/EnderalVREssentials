# ENDERAL VR ESSENTIALS (EVRE)

## Table of contents
* [Preamble](#preamble)
* [System Requirements](#system-requirements)
* [Requirements](#requirements)
* [Installation](#installation)
* [MCM Settings](#mcm-settings)
* [Noteworthy mods](#noteworthy-mods)
* [Known issues](#known-issues)
* [Scoped bows](#scoped-bows)
* [Supersampling](#supersampling)
* [Game capture](#game-capture)
* [Language packs](#language-packs)
* [Included Mods (Skyrim VR Installation Folder)](#Included-Mods-Skyrim-VR-Installation-Folder)
* [Included Mods (Mod Organizer 2)](#included-mods-mod-organizer-2)
* [Game Tweaks](#game-tweaks)

## Preamble
This guide describes how to configure Skyrim VR to play Enderal: Forgotten Stories SE in VR using Wabbajack.  Note that the ONLY version of Skyrim you need is Skyrim VR.  The Steam edition of Enderal SE is based off the Skyrim SE engine which does not support VR.  While it is NOT possible to add VR to Enderal SE, Skyrim VR can be "modded" with Enderal SE's files which will allow you to play through the entire game in VR!

Wabbajack simplifies the process of downloading all the required Skyrim VR mods and patches necessary to play Enderal SE in VR to a single click.  This guide uses a lightweight modlist designed to deliver an optimal VR experience with minimal performance loss.  This modlist was optimized for Virtual Desktop and Air Link and should perform extremely well when playing the game wirelessly.  Special thanks to the Enderal SE modding team and sasa2727 for the VR patch which made this guide possible!

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
* GPU: Nvidia GeForce GTX 1070 8GB or better
* STORAGE: 40GB
* ROUTER: 802.11ac or 802.11ax (for Virtual Desktop or Air Link; optional) 

## Requirements
* [The Elder Scrolls V: Skyrim VR](https://store.steampowered.com/app/611670/The_Elder_Scrolls_V_Skyrim_VR/)
* [Enderal: Forgotten Stories (Special Edition)](https://store.steampowered.com/app/976620/Enderal_Forgotten_Stories_Special_Edition)
* [Wabbajack](https://www.wabbajack.org/#/)
* [Enderal VR Essentials.wabbajack](https://drive.google.com/file/d/13sFAeS4tZOcpeus134k40jzaYedHQIaQ/view?usp=sharing)
* [Premium NexusMods account](https://www.nexusmods.com/)
	
## Installation
1.  Add Enderal SE to your Steam library from [HERE](https://store.steampowered.com/app/976620/Enderal_Forgotten_Stories_Special_Edition/). The game needs to be in your Steam library but does not need to be installed.
2.  Install a clean copy of Skyrim VR from [HERE](https://store.steampowered.com/app/611670/The_Elder_Scrolls_V_Skyrim_VR/).
	- If you already have a pre-modded Skyrim VR folder and do not wish to uninstall the vanilla game, you can rename your \SkyrimVR\ folder and then redownload a second clean copy of the game from Steam by reverifying the files.  You can then use one copy of the game to continue playing Skyrim VR along with a second copy of the game for playing Enderal VR.
3.  Run Skyrim VR one time from Steam and then exit the game.
4.  Download Wabbajack from [HERE](https://www.wabbajack.org/#/) and place "Wabbajack.exe" in a blank folder i.e. C:\Games\Wabbajack (Make sure the path has no spaces)
5.  Run Wabbajack one time and then exit the program.  
5.  Create a new folder where you wish to install Enderal VR i.e. C:\Games\EnderalVR (Make sure the path has no spaces)  
6.  Download "Enderal VR Modlist.wabbajack" from [HERE](https://drive.google.com/file/d/13sFAeS4tZOcpeus134k40jzaYedHQIaQ/view?usp=sharing) and place it anywhere outside of your Wabbajack folder.
7.  Launch Wabbajack by double-clicking "Enderal VR Essentials.wabbajack"
8.  Under "Installation Location", select the folder you created above under Step 6 and then click the green "PLAY" icon in the lower left. 
9.  Wait for Wabbajack to download all the mods and patches required to play Enderal VR.  This could take several hours depending on your Internet connection.
10.  Once Wabbajack is done downloading and configuring Enderal VR, navigate to your game folder from Step 6.
11. Copy the contents of \Game Folder Files\ to C:\Program Files (x86)\Steam\steamapps\common\SkyrimVR
12. Launch Mod Organizer 2.  Make sure "SKSE" is selected in the upper right dropdown bar and click "Run" to launch and play Enderal VR!  

## MCM Settings
Once you start a new game, you can configure your individual Enderal VR mods through the in-game Mod Configuration Menu (MCM) which is accessible under System > Mod Configuration.  Most MCM settings can be left as default but the following changes are recommended:
* VRIK MCM: 
1. Disable "Adjust Held Weapons Position". (Fixes scoped bows)
2. Select Body Holsters > Scroll down to Left Shoulder Holster > Untick "Visible" (Prevents your bow from clipping into the edge of your FOV when crouching in real life)  

* Spell Wheel VR MCM: 
1. Select Advanced > Set "Slow Time Scale" to 5.  (Enables slow motion when selecting items from the spell wheel)
 
# YOU'RE ALL DONE!  ENJOY ENDERAL: FORGOTTEN STORIES IN VR!  ALL STEPS BEYOND THIS POINT ARE OPTIONAL.





## Noteworthy mods
[**Enderal VR - Patch**](https://www.nexusmods.com/enderalspecialedition/mods/8?tab=files): This mod offers you the opportunity to play Enderal in VR. Supports special gestures when your Skyrim VR window is active in the forefront in Windows.  Raising your right controller above your head will bring up the Hero menu.  Repeating this gesture will close the Hero menu.  Raising your left controller above your head will teleport you to the Akropolis.   

[**Dear Diary VR - Paper SkyUI and Categorized Favorites**](https://www.nexusmods.com/skyrimspecialedition/mods/44874?tab=files): Replacer for Skyrim interface in a paper style.  Disable if you prefer the classic SkyUI interface.

[**Menu Mouse Fix**](https://www.nexusmods.com/skyrimspecialedition/mods/33414?tab=files): Enables mouse for SkyUI-VR. You can use your VR controllers to control the menu cursor like a laser pointer.

[**Smaller HUD for VR**](https://www.nexusmods.com/skyrimspecialedition/mods/30726?tab=files): A simple mod that reduces the size of the HUD elements and text by about 50% for added immmersion.  Disable if you prefer having a larger HUD or larger font size.

[**Flinching for VR Magic can trigger flinching**](https://www.nexusmods.com/skyrimspecialedition/mods/42550?tab=files): A little mod that allows NPCs to flinch when hit by your right fist or melee weapons in either hand.  Flinching animations do not work if you have ranged weapons such as a bow equipped.

[**VRIK**](https://www.nexusmods.com/skyrimspecialedition/mods/23416?tab=posts): VRIK will display the player character's body in SkyrimVR and animate it to match your movements. Weapons can be kept, drawn, and sheathed in up to 14 visible holsters on your body.  Be sure to untick the "Visible" setting for the Left Shoulder Holster in the VRIK MCM.  This prevents your bow from clipping into the edge of your FOV when crouching in real life.

[**VRIK Rift-Index-WMR Controller Bindings**](https://www.nexusmods.com/skyrimspecialedition/mods/23416?tab=files): These control bindings are an optional add-on for VRIK to make it easier to use holsters.  These bindings are disabled by default but MUST be enabled if you are using Index controllers.

[**HIGGS VR**](https://www.nexusmods.com/skyrimspecialedition/mods/43930?tab=files): Hand collision, physics object grabbing, and gravity gloves-style mechanics for Skyrim VR.

[**Spell Wheel VR**](https://www.nexusmods.com/skyrimspecialedition/mods/47630?tab=files): Selection wheel mod for Skyrim VR. It allows you to select spells, weapons, shields, arrows, potions, poisons, food, torch, armors and more without going into a menu very quickly by press of a button or button combinations to spawn the wheel and hold your hand over the item and letting go of the button. It's equipped automatically.  Be sure to set the "Slow Time Scale" to 5 in the Spell Wheel VR MCM if you want a nice slow motion effect when selecting items from the spell wheel.

[**NavigateVR**](https://www.nexusmods.com/skyrimspecialedition/mods/47174?tab=files): This mod brings immersive navigation to VR with a functional compass which is automatically added to your inventory.  While this mod does support equippable in-game maps, there are no available maps for Enderal locations. 

[**DragonbornSpeaksNaturally**](https://www.nexusmods.com/skyrimspecialedition/mods/16514?tab=files): Adds speech recognition to Skyrim VR or Skyrim SE so you can recite your dialogue lines to select them.  Requires no speech training!

[**Splashes of Skyrim - VR**](https://www.nexusmods.com/skyrimspecialedition/mods/47710?tab=files): SKSE plugin that adds projectile based water splashes and ripples, and underwater explosions.

[**HapticSkyrimVR - Spellcasting and Enhanced Bow and Melee Feedback SKSE Plugin**](https://www.nexusmods.com/skyrimspecialedition/mods/20364?tab=files): SKSEVR plugin to get spell casting and enhanced bow and melee haptic feedback on VR controllers.

[**Simple Realistic Archery VR**](https://www.nexusmods.com/skyrimspecialedition/mods/28524?tab=files): Automatically unequips your arrows after shooting them, then reequips the arrow after pressing the trigger (MCM configurable) over your shoulder. It also has options for binding different arrows to different buttons, for the position and size of the quiver, and options for attribute costs. Up to 25 arrow types can be bound at once.

[**Weapon Throw VR**](https://www.nexusmods.com/skyrimspecialedition/mods/31374?tab=files): Allows you to throw your equipped weapons in VR by holding a button, swinging your hand, and releasing it. All six melee weapon types, shields and torches are supported. Supports vanilla and mod added weapons. Includes Auto-Return and Auto-Aim features. Comes with an MCM to configure every setting.

[**Dual Wield Block VR**](https://www.nexusmods.com/skyrimspecialedition/mods/28456?tab=files): SKSE plugin to let the player block attacks while dual wielding (two weapons or weapon + spell) or unarmed.

[**LocationalDamageSKSE VR**](https://www.nexusmods.com/skyrimspecialedition/mods/26447?tab=files): Locational Damage for SKSE VR! Do extra damage depending on which body part you hit with your arrows or spells.

[**No Stagger Mod**](https://www.nexusmods.com/skyrimspecialedition/mods/16335?tab=files): This mod makes your character unstaggerable.  This prevents you from being stunned in combat and having a bright light flash across your vision.

[**Sprint Jump VR**](https://www.nexusmods.com/skyrimspecialedition/mods/28354?tab=files): An SKSE plugin to allow Sprint Jumping in SkyrimVR. Increase sprint jump height and distance with a multiplier in the config file.

[**Scoped Bows SE**](https://www.nexusmods.com/skyrimspecialedition/mods/912?tab=files): Scoped Bows is a huge weapons mod that adds scoped variants of all bows to the game, designed to be used without crosshair.  You MUST disable "Adjust Held Weapons Position" in the VRIK MCM or aiming through scopes will not work properly.

[**Dynamically Disable Eye Adaptation and Bloom**](https://www.nexusmods.com/skyrimspecialedition/mods/2135?tab=files): Disables Bloom to remove the "glow" effect around light sources.  Disable if you prefer having Bloom effects in VR.

[**R.A.S.S - Rain Ash And Snow Shader**](https://www.nexusmods.com/skyrimspecialedition/mods/22780?tab=files): "R.A.S.S." adds weather effects to the Player such as water droplet effects in your vision. Disable if you prefer having no weather effects.  You can alternatively disable select weather effects from the R.A.S.S. MCM. 

[**SkyVRaan - Shimmering VR Waters**](https://www.nexusmods.com/skyrimspecialedition/mods/30571?tab=files): Adds a fake reflection effect to Skyrim VR's outdoor water. It breaks up the distant LOD, shows wave movement on the distant water, and gives an illusion of water depth in the distance. Also has improved realism and clarity of near water.

[**Storm Lightning for SSE and VR**](https://www.nexusmods.com/skyrimspecialedition/mods/29243?tab=files): A remake of Minty's Lightning mod as an SKSE plugin. The purpose of this mod is stability and scalability. It can summon up to 50 sheet lightnings and 50 fork lightnings per second and up to 31 cells distance. This results in a more natural and enjoyable storm experience.

[**Bijin Skin CBBE 2k Based**](https://www.nexusmods.com/skyrimspecialedition/mods/20078?tab=files): Smoother skin for NPCs with less blemishes.  Disable if you prefer vanilla skin.

[**Replace spiders with wolfs and bears**](https://www.nexusmods.com/enderalspecialedition/mods/31?tab=files): Replaces spiders with wolves and bears.  Enable if you have arachnophobia! 

## Known issues
* Your headset and controllers must be active before launching the game or it will not start.
* The loading screens are broken and no artwork shows up unless TAA is enabled.  TAA should always be disabled, however, as enabling TAA will always cause in-game blur even when tweaked.
* Cutscenes do not work.  Audio always plays against the SteamVR backdrop.  This is a very minor issue as there are only 3 cutscenes in the entire game.  These can be easily viewed on YouTube and two of the videos are introduction videos which play at the beginning of the game.
* You have no avatar during the tutorial.  This is normal as you do not get an avatar until completing the character creation wizard.
* Interrupting and cancelling dialogue with NPCs prematurely with the triggers on your VR controllers may soft lock your game as you will be unable to continue quest related conversations.  A previous saved game must be loaded to continue.
* If you get stuck during quests from animations that do not trigger properly, press "~" with the game in focus on your monitor and type player.tai or enableplayercontrols in the console.
* Loading saved games during the opening tutorial may cause VRIK to glitch out.
* If you need to reset your height in-game, do not run "Floor Fix" thru Open VR Advanced Settings as this may causes problems with VRIK where you get stuck in "Sneak" mode.  Recalibrate your height through the VRIK Calibration Power.  You can do this by selecting the VRIK Calibration Power from the magic menu.
* If you are playing wirelessly on the Quest 2, you may see a subtle "rectangular box" around the edges of the view where the image becomes blurry outside of the rectangle.  This effect is normal and is caused by foveation used by Virtual Desktop when streaming Enderal VR wirelessly.
* If you have trouble selecting ingredients at alchemy benches, on your left controller be sure to tap the analog stick to the right which should allow you to select ingredients for crafting.
* If you have issues equipping arrows for your bow, you need to reach behind your back in real life to grab an arrow.  This is a feature from the included Simple Realistic Archery mod. 
* If the Hero menu doesn't pop up when raising one controller over your head, make sure the Enderal window is active and in focus on the Windows desktop.
* Note that with the exception of texture/mesh mods, mods cannot be safely removed mid-savegame.

## Scoped bows
* For scoped bow aiming to work, open VRIK MCM and disable "Adjust Held Weapons Position"
* You can add scoped bows to your inventory by pressing "~" with Enderal VR active on your Windows desktop and entering one of the following lines:

    * Player.AddItem 000CC392 1 (Angi's Bow)
    * Player.AddItem 000AB705 1 (Bow of the Hunt)
    * Player.AddItem 0006B9AD 1 (Dravin's Bow)
    * Player.AddItem 00017059 1 (Firiniel's End)
    * Player.AddItem 000C0186 1 (Froki's Bow)
    * Player.AddItem 000F5D22 1 (Gauldur Blackbow)
    * Player.AddItem 000F652C 1 (Nightingale Bow)

## Supersampling
* Supersampling can be done via in-game Supersampling and Contrast Adaptive Sharpening (CAS) via The Sharper Eye mod.  For optimal image fidelity and performance, in-game Supersampling should always disabled.  CAS should always be enabled via The Sharper Eye.  This Wabbajack install is pre-configured to supersample the game using The Sharper Eye.
* When using The Sharper Eye for supersampling, pressing the HOME key with Enderal VR active on your Windows desktop will open the built-in Reshade UI. Here you can adjust the parameters for CAS, Contrast, Brightness, and Color Saturation.  Default settings should be optimal for VR.
* In addition to improving visuals with The Sharper Eye, you can continue to supersample Enderal VR through SteamVR, Oculus Tray Tool, or Virtual Desktop.
    * If playing wired with an HTC/Valve/HP headset, increase your SteamVR resolution above 100% to the maximum resolution your GPU can handle.  
    * If playing wired on an Oculus headset, increase your supersampling as high as your GPU can handle via Oculus Tray Tool.  
    * If playing wirelessly with Air Link, lock your SteamVR resolution at 100% and increase your supersampling as high as your GPU can handle via Oculus Tray Tool.  
    * If playing wirelessly with Virtual Desktop, lock your SteamVR resolution at 100% and set your Virtual Desktop video settings to Low/Medium/High based on your GPU. For optimal Virtual Desktop performance, set your Streaming settings to 60fps @ 80Mbps bitrate with Sliced Encoding enabled.

## Game capture
* If you want to take screenshots or record footage while in VR, use [OBS Studio](https://obsproject.com) with the [OBS OpenVR Input Plugin v1.5](https://github.com/baffler/OBS-OpenVR-Input-Plugin/releases/tag/v1.5).  This will allow you to capture the game in widescreen at a higher resolution than what can be achieved when capturing the game from either the Virtual Desktop or SteamVR mirror window.

## Language packs
Enderal SE supports language packs which allow the game to be played in Chinese, French, German, Italian, Japanese, Korean, Russian, and Spanish.  You can download the packs [HERE](https://www.nexusmods.com/enderalspecialedition/mods/1?tab=files).  Install the language pack via Mod Organizer 2 with a unique name i.e. "Enderal SE - German Language Pack" and place it underneath "Enderal SE" and "Enderal SE - Update" in your mod loadout.  Finally, edit the following line "sLanguage=ENGLISH" with the preferred language in the following three files:
* C:\ (Your Game Folder)\mods\Enderal SE\Enderal - Forgotten Stories.ini
* C:\ (Your Game Folder)\mods\Enderal SE - Update\Enderal - Forgotten Stories.ini
* C:\ (Your Game Folder)\mods\Enderal VR - Patch\EnderalVRpatch.ini

## Included Mods (Skyrim VR Installation Folder)
[**SKSE VR v2.0.12**](https://skse.silverlock.org): A tool used by many Skyrim mods that expands scripting capabilities and adds additional functionality to the game.

[**EngineFixesVR v1.20**](https://github.com/rollingrock/EngineFixesVR/releases): SKSEVR plugin to fix various issues with the Skyrim Special Edition engine.

[**Binaural 3D Surround Sound for SKYRIM VR v2.3.01**](https://www.nexusmods.com/skyrimspecialedition/mods/26916?tab=files): This mod uses algorithms that can simulate HRTF, allowing for full 3D surround sound with just a normal pair of earphones or headphones. For 1st person use.

[**The Sharper Eye v1.0**](https://www.nexusmods.com/skyrimspecialedition/mods/46999/?tab=files): Get rid of the blur and grey mist in your headset which are clouding your vision. This VR-enabled ReShade build and preset provide the most performance-friendly sharpening filter for Skyrim VR bundled with a subtle touch of contrast, brightness and saturation. All configurable to your liking.

[**xSHADOWMANx's DLL Loader v1.0.0.4**](https://www.nexusmods.com/skyrimspecialedition/mods/3619?tab=files): DLL Loader for Dragonborn Speaks Naturally.


## Included Mods (Mod Organizer 2)
[**Enderal SE**](https://www.nexusmods.com/enderalspecialedition/mods/1?tab=files): Complete Enderal for Skyrim Special Edition.

[**Enderal SE Update**](https://www.nexusmods.com/enderalspecialedition/mods/1?tab=files): Update for Complete Enderal for Skyrim Special Edition. 

[**Enderal SE - Bug Fixes v1.26.2**](https://www.nexusmods.com/enderalspecialedition/mods/2?tab=files): This mod fixes several issues with the game and also includes some small gameplay/balance fixes.

[**SkyUI v1.0-beta.4**](https://github.com/Odie/skyui-vr): Elegant, PC-friendly interface mod with many advanced features.

[**JContainers VR v4.1.13**](https://www.nexusmods.com/skyrimspecialedition/mods/16495?tab=files): Extends Skyrim SE Papyrus scripts (or SKSE/C++ plugins) with JSON based serializable data structures like arrays and maps. Embedded Lua interpreter.

[**moreHUD VR v1.0.4**](https://www.nexusmods.com/skyrimspecialedition/mods/33215?tab=files): Adds more information to the HUD about the currently targeted object. Such as ingredients, weapon effects, potions, read books, v/w, enemy level, etc.

[**SkyrimVRTools v2.3-BETA**](https://www.nexusmods.com/skyrimspecialedition/mods/27782?tab=files): Providing OpenVR input information and control as a service to other Skyrim VR mods.

[**Enderal VR - Patch**](https://www.nexusmods.com/enderalspecialedition/mods/8?tab=files): Mod for playing Enderal in VR (with the SkyrimVR engine).

[**SKSEVR 2.0.12**](https://skse.silverlock.org): A tool used by many Skyrim mods that expands scripting capabilities and adds additional functionality to the game.

[**EngineFixesVR v1.20**](https://github.com/rollingrock/EngineFixesVR/releases): SKSEVR plugin to fix various issues with the Skyrim Special Edition engine.
- Open EngineFixesVR.ini and add the following lines: MemoryManager = false, SelectAllocator = 1.

[**Dear Diary VR - Paper SkyUI and Categorized Favorites v1.06**](https://www.nexusmods.com/skyrimspecialedition/mods/44874?tab=files): Replacer for Skyrim interface in a paper style.

[**Dear Diary - Enderal version v2.2.4**](https://www.nexusmods.com/enderal/mods/164?tab=files):  Updates Dear Diary for Enderal compatability.  Removes "Skills" option from the Tab Menu as this menu is not used by Enderal and will cause the game to crash when accessed if not removed.
- Install Tab Menu ONLY.

[**Menu Mouse Fix v1.1.1**](https://www.nexusmods.com/skyrimspecialedition/mods/33414?tab=files): Enables mouse for SkyUI-VR. You can use your controllers to control the cursor like a smart tv remote.

[**Smaller HUD for VR v1.0**](https://www.nexusmods.com/skyrimspecialedition/mods/30726?tab=files): A simple mod that reduces the size of the HUD elements by about 50%.

[**Dot Crosshair VR v0.8**](https://www.nexusmods.com/skyrimspecialedition/mods/17764?tab=files): Colors the target crosshairs as red and green and converts them to dots since the default grey target crosshairs are often difficult to see and you can not distinguish them in casting double magic.

[**Nemesis Unlimited Behavior Engine v0.84-beta**](https://github.com/ShikyoKira/Project-New-Reign---Nemesis-Main/releases): An animation framework that enables behavior mods like CGO, SkySA, Ultimate Combat and most FNIS dependent mods to work together

[**Spell Perk Item Distributor VR v4.4**](https://www.nexusmods.com/skyrimspecialedition/mods/36869?tab=files): An SKSE plugin that can be used to add spells/leveled spells/perks/items/leveled items/shouts/packages/outfits to every NPC in the game, using config files.

[**Ultimate Combat and Creatures Behaviour compatibility for Nemesis v1.12**](https://www.nexusmods.com/skyrimspecialedition/mods/45966?tab=files): This is just a VERY HACKY compatibility patch thing for creature behaviour edits, Nemesis and Ultimate combat, as more and more mods are coming out effecting creature's behaviours it just makes sense to have something like this instead of it being inside multiple mods

[**Simple Offence Suppression - VR v1.1**](https://www.nexusmods.com/skyrimspecialedition/mods/41764?tab=files): SKSE plugin that prevents neutral NPCs from turning hostile when you accidentally hit them.

[**Flinching for VR Magic can trigger flinching v1.361**](https://www.nexusmods.com/skyrimspecialedition/mods/42550?tab=files): A little mod that allows the player and NPCs to flinch when hit.
- Requires patching with Nemesis.

[**VRIK V0.8.1. In-Dev Build 28**](https://www.nexusmods.com/skyrimspecialedition/mods/23416?tab=posts): VRIK will display the player character's body in SkyrimVR and animate it to match your movements. Weapons can be kept, drawn, and sheathed in up to 14 visible holsters on your body. An input gesture system allows users to bind actions to gestures on each hand, reducing the need to open menus. An MCM menu allows full configuration of everything.

[**VRIK Rift-Index-WMR Controller Bindings V2.1.0**](https://www.nexusmods.com/skyrimspecialedition/mods/23416?tab=files): These control bindings are an optional add-on for VRIK to make it easier to use holsters.  The button for shout has been moved to Right A (or the right WMR touchpad), and interact is performed by squeezing the right grip.  Sprinting is now done by squeezing the left grip.  With these "safe" inputs on grips, players do not need to worry about shouting accidentally when grabbing holstered weapons.

[**HIGGS VR v1.1.0**](https://www.nexusmods.com/skyrimspecialedition/mods/43930?tab=files): Hand collision, physics object grabbing, and gravity gloves-style mechanics for Skyrim VR.

[**Spell Wheel VR v1.1.1**](https://www.nexusmods.com/skyrimspecialedition/mods/47630?tab=files): Selection wheel mod for Skyrim VR. It allows you to select spells, weapons, shields, arrows, potions, poisons, food, torch, armors and more without going into a menu very quickly by press of a button or button combinations to spawn the wheel and hold your hand over the item and letting go of the button. It's equipped automatically.

[**NavigateVR v1.4**](https://www.nexusmods.com/skyrimspecialedition/mods/47174?tab=files): This mod brings immersive navigation to VR with a functional compass

[**DragonbornSpeaksNaturally - Beta v0.21.0-beta**](https://www.nexusmods.com/skyrimspecialedition/mods/16514?tab=files): Adds speech recognition to Skyrim VR or Skyrim SE so you can recite your dialogue lines to select them.

[**Splashes of Skyrim - VR v1.2**](https://www.nexusmods.com/skyrimspecialedition/mods/47710?tab=files): SKSE plugin that adds projectile based water splashes and ripples, and underwater explosions.

[**HapticSkyrimVR - Spellcasting and Enhanced Bow and Melee Feedback SKSE Plugin v1.7.2**](https://www.nexusmods.com/skyrimspecialedition/mods/20364?tab=files): SKSEVR plugin to get spell casting and enhanced bow and melee haptic feedback on VR controllers.

[**Simple Realistic Archery VR v1.26**](https://www.nexusmods.com/skyrimspecialedition/mods/28524?tab=files): Automatically unequips your arrows after shooting them, then reequips the arrow after pressing the trigger (MCM configurable) over your shoulder. It also has options for binding different arrows to different buttons, for the position and size of the quiver, and options for attribute costs. Up to 25 arrow types can be bound at once.

[**Weapon Throw VR v1.3.3**](https://www.nexusmods.com/skyrimspecialedition/mods/31374?tab=files): Allows you to throw your equipped weapons in VR by holding a button, swinging your hand, and releasing it. All six melee weapon types, shields and torches are supported. Supports vanilla and mod added weapons. Includes Auto-Return and Auto-Aim features. Comes with an MCM to configure every setting.

[**Dual Wield Block VR v1.5.2**](https://www.nexusmods.com/skyrimspecialedition/mods/28456?tab=files): SKSE plugin to let the player block attacks while dual wielding (two weapons or weapon + spell) or unarmed.

[**LocationalDamageSKSE VR v0.7.1-BETA**](https://www.nexusmods.com/skyrimspecialedition/mods/26447?tab=files): Locational Damage for SKSE VR! Do extra damage depending on which body part you hit with your arrows or spells.

[**No Stagger Mod v1.0**](https://www.nexusmods.com/skyrimspecialedition/mods/16335?tab=files): This mod makes your character unstaggerable. 

[**Sprint Jump VR v1.01**](https://www.nexusmods.com/skyrimspecialedition/mods/28354?tab=files): An SKSE plugin to allow Sprint Jumping in SkyrimVR. Increase sprint jump height and distance with a multiplier in the config file.

[**Enhanced Ragdoll Accuracy Main File v1.02**](https://www.nexusmods.com/skyrimspecialedition/mods/45767?tab=files): Makes in-game humanoid corpses much more believable and immersive through meticulous changes in weight, joints, etc.

[**Scoped Bows SE v1.3.1**](https://www.nexusmods.com/skyrimspecialedition/mods/912?tab=files): Scoped Bows is a huge weapons mod that adds scoped variants of all bows to the game, designed to be used without crosshair.

[**Scoped VR-1-1-1 v1.1.1**](https://www.nexusmods.com/skyrimspecialedition/mods/16666?tab=files): Scoped Bows Remixed meshes designed for VR.

[**Dynamically Disable Eye Adaptation and Bloom v1.2.0**](https://www.nexusmods.com/skyrimspecialedition/mods/2135?tab=files): Disables the irritating eye adaptation and object blooming through scripting. Compatible with all image space lighting mods!

[**Pouring Rain v2.0**](https://www.nexusmods.com/skyrimspecialedition/mods/6077?tab=files): Increases rain particles density during raining weathers.

[**R.A.S.S - Rain Ash And Snow Shaders v3.2.2**](https://www.nexusmods.com/skyrimspecialedition/mods/22780?tab=files): "R.A.S.S." adds visual effects to the Player and NPCs during certain conditions.

[**SkyVRaan - Shimmering VR Waters v1.0.1**](https://www.nexusmods.com/skyrimspecialedition/mods/30571?tab=files): Adds a fake reflection effect to Skyrim VR's outdoor water. It breaks up the distant LOD, shows wave movement on the distant water, and gives an illusion of water depth in the distance. Also has improved realism and clarity of near water.
- Requires patching with Synthesis.

[**Storm Lightning for SSE and VR v1.4.9**](https://www.nexusmods.com/skyrimspecialedition/mods/29243?tab=files): A remake of Minty's Lightning mod as an SKSE plugin. The purpose of this mod is stability and scalability. It can summon up to 50 sheet lightnings and 50 fork lightnings per second and up to 31 cells distance. This results in a more natural and enjoyable storm experience.

[**Basic Dining Set Replacer 1k v1.0**](https://www.nexusmods.com/skyrimspecialedition/mods/30055?tab=files): A mod that replaces the dining set we often see in farmhouses or taverns in skyrim.

[**Noble Skyrim FULL PACK Performance Edition v5.5.0**](https://www.nexusmods.com/skyrimspecialedition/mods/21423?tab=files): Gives all of Skyrim's architecture a complete new look by changing its textures to custom ones. Beside the architecture, several other things, such as landscape, dungeons (ruins, mines, caves etc.), clutter stuff etc. have been re-textured as well, to match the rest of the mod.
- Recommend placing before other texture packs; Remove "whroughgroundmud.dds".

[**Real Mountains Rebuilt v1.2**](https://www.nexusmods.com/skyrimspecialedition/mods/3704?tab=files): Retexture that enhance the detail of mountains and rocks.

[**Tamrielic Textures SE 1 Landscapes 1K v1.4.0**](https://www.nexusmods.com/skyrimspecialedition/mods/32973?tab=files):  A fresh and complete replacement of all Skyrim landscape textures.

[**CC's HQ Caves - 2K v1.1**](https://www.nexusmods.com/skyrimspecialedition/mods/8448?tab=files): This is a retexture of the Cavewalls and the Cavefloor. All textures handmade using Substance Designer 6.

[**Pine Branches Redone 4K v2.0**](https://www.nexusmods.com/skyrimspecialedition/mods/45294?tab=files): Realistic pine branches replacer. All types covered.  Billboards included.

[**Embers XD v2.2.1**](https://www.nexusmods.com/skyrimspecialedition/mods/37085?tab=files): An overhaul of campfires and other fire sources.
- Delete ESP files.

[**STO - Stars 2K Only small stars v1.0**](https://www.nexusmods.com/skyrimspecialedition/mods/4931?tab=files): Overhauls the stars to 4K from 1K.  Uses small stars only to reduce SDE in nighttime scenes for added immersion.

[**Bijin Skin CBBE 2k Based v1.2.1**](https://www.nexusmods.com/skyrim/mods/91953?tab=files): One of the female skins.

[**Bijin skin Crotch fix CBBE v1.2.2**](https://www.nexusmods.com/skyrim/mods/91953?tab=files): Update for one of the female skins.

[**Myths and Legends VI - The Forgotten One v1.01**](https://www.nexusmods.com/enderalspecialedition/mods/25?tab=files): Adds a new Myths and Legends book, a new dungeon, and a completely new creature with unique mechanics.

[**EOP SE - Enderal SE Outposts v1.01**](https://www.nexusmods.com/enderalspecialedition/mods/18?tab=files): Adds order outposts, fortifies some camps with additional protection. 

[**Delectable Docks SE v1.2**](https://www.nexusmods.com/enderalspecialedition/mods/77?tab=files): Adds many details to the docks and harbors of Enderal focused on improving immersion.

[**Riverville Catacombs SE v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/80?tab=files): Forgotten Dungeons implements cut content, originally made by SureAI, with updates and fixes to fit seamlessly into the game.

[**Noble Quarter Player Home Redone v1.02**](https://www.nexusmods.com/enderalspecialedition/mods/66?tab=files): Overhauls player home in Nobles Quarter.

[**Enderal SE - Undercity Arena Fix v.1.0**](https://www.nexusmods.com/enderalspecialedition/mods/9?tab=files): Reworks the undercity arena to be less cheeseable, bigger and fixes an issue with shadows.

[**EAM SE - Enderal Apothecarii Monastery v1.02**](https://www.nexusmods.com/enderalspecialedition/mods/34?tab=files): Adds the Apothecarii Monastery including: Huge monastery area, over 10 interiors, 2 dungeons and much more.

[**Allow Fast Travel v1.1**](https://www.nexusmods.com/enderalspecialedition/mods/42?tab=files): Allows Fast Travel in Enderal.

[**Diverse Weather v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/70?tab=files): Diversifies the weather in Enderal and adds a few new ones.

[**Storeable Phasmalist Talismans v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/68?tab=files): Allows you to store away Phasmalist Talismans.

[**Unique Armor Sets Replacer Enderal SE v2.1**](https://www.nexusmods.com/enderalspecialedition/mods/27?tab=files): High-quality and lore friendly replacers for many of Enderal's unique armor sets! Converted with SSE nif optimizer.

[**Practical Armor Replacers v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/23?tab=files): Armor and weapons more fitting to the setting of Enderal. Converted to SE!

[**Dawnguard Heavy Armor (Shadowsteel Brigandine) - SE v2.0**](https://www.nexusmods.com/enderalspecialedition/mods/33?tab=files): A port of Dawnguard heavy armor set from Skyrim SE to Enderal SE.

[**Enderal SE - Crossbows v1.07**](https://www.nexusmods.com/enderalspecialedition/mods/4?tab=files): Adds Crossbows to Enderal SE.

[**Unique Enderal Uniques SE v2.0**](https://www.nexusmods.com/enderalspecialedition/mods/38?tab=files): Enderal SE conversion of Unique Enderal Uniques using SSE nif optimizer.

[**Craftsman Tools Replacer v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/28?tab=files): Replaces meshes and textures of the crafting tools seen throughout Enderal.

[**Ark Easserspeier - Ark Watersprouts (SE) v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/62?tab=files): Changes the waterspouts in the Foreign Quarter in Ark.

[**Celtic Endralean Penny v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/71?tab=files): A simple mod that replaces the default Endralean Penny Coin with InsanitySorrow's Celtic coin.

[**Cannons 2K v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/63?tab=files): Replaces the cannons and cannon balls with new 2K textures.

[**Enderal NPC Overhaul - SE version v2.2**](https://www.nexusmods.com/skyrim/mods/85455?tab=files): 75+ important NPCs are given a unique look, 500+ NPCs are given KS Hairdo's Hair. No esp. Can choose only unique, males or females.

[**Kids of Enderal - SE v1.7**](https://www.nexusmods.com/skyrim/mods/93432?tab=files): Remakes kids in Enderal to look like Skyrim's "The Kids are Alright".

[**Tharael as Follower and Housemate v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/45?tab=files): Adds an option to make Tharaêl your companion after completing Dark Chambers of Our Mind (providing that you sided with him and offered to help him).

[**Amanda v1.4.2**](https://www.nexusmods.com/enderalspecialedition/mods/15?tab=files): Adds female follower to The Drunken Bee tavern in Riverville.

[**Bears of the North v1.1**](https://www.nexusmods.com/skyrimspecialedition/mods/47541?tab=files): Visual overhaul of the bears of Skyrim. Bigger, badder bears fit for the harsh northern lands they roam.

[**Enderal SE - Bears of the North v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/30?tab=files): Enderal SE compatibility patch for Bears of the North.

[**Creature Replacer Pack v1.1**](https://www.nexusmods.com/enderalspecialedition/mods/74?tab=files): A collection of creature replacers for Enderal converted to SE.

[**Enderal - Arp v2.12**](https://www.nexusmods.com/enderalspecialedition/mods/36?tab=files): Completely redesigned 4K Arps for Enderal SE and VR.

[**Enderal - Vatyr v2.21**](https://www.nexusmods.com/enderalspecialedition/mods/41?tab=files): Completely redesigned Vatyr in 4K for Enderal SE and VR.

[**Boneripper Replacer (Clannfear) v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/59?tab=files): Replaces the models Bonerippers with high quality alternatives.

[**Pus Beetle Replacer v1.0**](https://www.nexusmods.com/enderalspecialedition/mods/48?tab=files): Replaces the models Pus Beetles with high quality alternatives.

[**Ancestral Spirit Replacer (Variant 2)**](https://www.nexusmods.com/enderalspecialedition/mods/60?tab=files): Replaces the models Ancestral Spirits with high quality alternatives.

[**Kolapon's Various Creatures Replacers v1.5v**](https://www.nexusmods.com/enderalspecialedition/mods/64?tab=files): Changes the appearance of some of the creatures so they are unique to Enderal.

[**Kolapon's Undead Creatures Replacer v1.2u**](https://www.nexusmods.com/enderalspecialedition/mods/64?tab=files): Changes the appearance of some of the creatures so they are unique to Enderal.

[**Replace spiders with wolfs and bears v1.0.1**](https://www.nexusmods.com/enderalspecialedition/mods/31?tab=files): Replaces spiders with wolves and bears.

## GAME TWEAKS 
Recommended game settings are listed below.  Note that the above Wabbajack install has already been pre-configured with the following tweaks which are merely listed for reference.

### INI Settings
* INI files are found in C:\ (Your Game Folder)\profiles\Default
* These INI files will override any vanilla INI files which are stored in: C:\Users\ (Username)\Documents\My Games\Skyrim VR\  
* Recommended INI settings: 
1. Open INI files and add this text somewhere under the [Launcher] section: bEnableFileSelection=1 (Enables mods)
2. Open INI files and add this text somewhere under the [Display] section: iTintTextureResolution=2048 (NPC Overhaul tweak)
3. Open INI files and add this text somewhere under the [VR] section: bAllowVRCheating=1 (Disable bumpback when too close to an object)
4. Open INI files and add this text somewhere under the [VR] section: fVrScale=72 (Tweaks world scale for VR; Typical values are between 72-78)
5. Open INI files and add this text somewhere under the [VRUI] section: fHUDCompassScale=0.5000 (Decrease compass size)
6. Open INI files and add this text somewhere under the [VRUI] section: bPlayVRMeleeWorldImpactSounds=0 (Disable impact sounds; Set to "1" if you like the effect.)
7. Open INI files and add this text somewhere under the [VRWand] section: fBowHoldOffsetY=-6.6 (Tweaks bows for VR)
8. Open INI files and add this text somewhere under the [Particles] section: iMaxDesired=1500 (Tweaks Embers XD)
9. Open INI files and add this text somewhere under the [VRUI] section to decrease text size: 

         fActivateRolloverSecondaryScale=10
	 
         fActivateRolloverSecondaryZ=0
	 
         fActivateRolloverSecondaryY=0
	 
         fActivateRolloverPrimaryScale=10
	 
         fActivateRolloverPrimaryZ=0
	 
         fActivateRolloverPrimaryY=0
	 
         fActivateRolloverWandScale=10.0000 
	 
         fActivateRolloverSecondaryScale=10.0000
	 
         fActivateRolloverPrimaryScale=10.0000
 
### In-Game Settings
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

### SkyVRaan Configuration 
SkyVRaan adds shimmering water effects to the game.  SkyVRaan has been pre-configured with Wabbajack but the configuration process has been documented below for reference. 
1. Close Mod Organizer 2 if open
2. Create a blank Skyrim.ini file in C:\Users\ (Username)\Documents\My Games\Skyrim VR\
3. Install .NET SDK 5.0 and remove any previously installed .NET runtimes.  You can confirm .NET SDK 5.0 is properly installed by running the following from your command prompt:  dotnet --info
4. Launch MO2 and select Tools > Executables > Add an executable ("+" icon in upper left) > Add from file > Navigate to C:\Program Files (x86)\Steam\steamapps\common\SkyrimVR\Data\Synthesis\ > Select Synthesis.exe > OK
5. Right click on "Overwrite" in the left window pane and select: Clean Overwrite > OK. (If applicable, this option may not be available if your overwrite folder is already clean)
6. Select Synthesis from upper right dropdown and click RUN
7. Select Skyrim VR
8. Select Git Repository (2nd icon in upper left) 
9. Search for SkyVRaan and select the "+" icon next to SkyVRaanAutoPatcher and SkyVRaanWeatherPatcher
10. Click RUN icon
11. Wait for the utility to report "Completed" and close Synthesis.  If Synthesis errors out when patching SkyVRaan, try the following:
	- Select SkyVRaanAutoPatcher and SkyVRaanWeatherPatcher in the left hand bar and set "Mutagen" and "Synthesis" to "Latest".
	- Click "Skyrim VR" in the top bar.  Under Data Folder Location, enter the following path: C:\Program Files (x86)\Steam\steamapps\common\SkyrimVR\Data
12. Right click on "Overwrite" and select "Create Mod".  Enter a custom name i.e. Synthesis output and click OK.
13. Tick "Synthesis output" in left window pane and make sure "Synthesis.esp" is near the bottom of your Plugin load order and ticked in the right window pane.  
14. Revert the upper right dropdown bar back to "SKSE".
15. You may need to re-run this process if you change your load order.

### Flinching Configuration 
Flinching adds flinching animations.  NPCs will react with an animation when attacked with the right fist or melee weapons in either hand.  Flinching has been pre-configured with Wabbajack but the configuration process has been documented below for reference. 
1. Launch MO2 and select Tools > Executables > Add an executable ("+" icon in upper left) > Add from file > Navigate to C:\Program Files (x86)\Steam\steamapps\common\SkyrimVR\Data\Nemesis_Engine > Select Nemesis Unlimited Behavior Engine.exe > OK
2. Right click on "Overwrite" in the left window pane and select: Clean Overwrite > OK.  (If applicable, this option may not be available if your overwrite folder is already clean)
3. Select Nemesis Unlimited Behavior Engine from upper right drop down and click RUN
4. Click OK for both Warning popups
5. Click "Update Engine"
6. Tick the "Flinching Animations" option and click "Launch Nemesis Behavior Engine"
7. Wait for the process to finish and then close the Nemesis Unlimited Behavior Engine.
8. Right click on "Overwrite" and select "Create Mod".  Enter a custom name i.e. Nemesis output and click OK.
9. Tick "Nemesis output" in left window pane. 
10. Revert the upper right dropdown bar back to "SKSE".
11. You may need to re-run this process if you change your load order.

### Mod Organizer 2 Settings
Required Mod Load Order (left side):
* Enderal SE
* Enderal SE - Update
* Enderal SE - Bug Fixes
* SkyUI
* JContainers VR
* moreHUD VR 
* SkyrimVRTools
* Enderal VR patch
* (everything else)

Required Mod Load Order (right side):
* Enderal Forgotten Stories.esm
* Enderal SE - Bug Fixes.esp
* SkyUI_SE.esp
* AHZmoreHUD.esp
* EnderalVRpatch.esp
* (everything else; Enderal SE specific mods should be placed near the bottom)
* Synthesis.esp (Generated with the Synthesis utility and should be placed near the bottom) 

When installing mods, if prompted to extract BSA files, select "No".
