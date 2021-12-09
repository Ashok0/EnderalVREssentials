# Changelog

### v1.104:

Release date: December 8th, 2021

New Mods
- Enderal Missing Race Fix (For mods such as FEC) v1.0: Adds the missing player race-entries from Skyrim into Enderal (leaving Enderal's overwriting of the other races intact!) for any\all mods that requires their existence, such as Frozen Electrocuted Combustion.

Removed Mods
- Frozen Electrocuted Combustion - Enderal Fix v1.1: Does not work properly. Must be replaced with Enderal Missing Race Fix or the character creation wizard will fail to work properly.

### v1.103:

Release date: December 5th, 2021
- - -
Added support for Frozen Electrocuted Combustion. FEC is disabled by default.  Do not enable FEC until completing the tutorial mission as the FEC mods will break the character creation wizard.  To enable FEC, tick "Frozen Electrocuted Combustion", "Frozen Electrocuted Combustion VR", and "Frozen Electrocuted Combustion - Enderal Fix" in Mod Organizer 2.
- - -
Added two DynDOLOD mods for selecting LODs optimized for performance versus quality.  Use only one.
- For max performance, enable "DynDOLOD_Output_PERFORMANCE" in Mod Organizer 2.  This uses "billboard1" trees at LOD Level 4 for maximum performance. Enabled by default.**
- For max quality, enable "DynDOLOD_Output_QUALITY" in Mod Organizer 2. This uses "level0" trees at LOD Level 4 for greatly improved tree LODs. Results in -10fps in large open areas on an RTX 3070. Not recommended for wireless VR. Disabled by default.

- - -

Updated Tools 
- xLODGen Beta 85: Tool for generating terrain LOD.
- DynDOLOD Standalone 3.0 Alpha-56: DynDOLOD is a set of simple tools based on xEdit/xLODGen to automatically create a Skyrim mod based on the load order which adds distant LOD for objects and trees to Skyrim. By combining DynDOLOD with xLODGen users can create drastically enhanced static object LOD + tree LOD and the new, optional dynamic distant object LOD in a few simple steps.
- The Sharper Eye v1.0: MaxDelta setting in INI reverted to defaults.
- Synthesis v0.20.6: A framework and GUI to construct a single Bethesda game patch from many patcher sources. Designed to allow any program to work as a patcher as long as it conforms to the CLI API.
- SSEEdit v4.0.4: SSEEdit is the Skyrim: Special Edition version of xEdit. xEdit is an advanced graphical module viewer/editor and conflict detector.

New Mods
- VR Address Library for SKSEVR v0.15.0: VR Address Library database for end users. This is intended as a VR replacement for Address Library for SKSE for mods designed for it. Only download if the mod says this is a requirement. It is currently an alpha. This is not for SSE. This is different from Address Library for SKSE. Required by FEC.
- Papyrus Extender SSE - 4.5.5: SKSE64 plugin that extends Papyrus script functionality, with over 275 new Papyrus functions, and 29 events.  Required by FEC.
- Papyrus Extender VR v4.5.5: SKSEVR plugin that extends Papyrus script functionality, with over 275 new Papyrus functions, and 29 events. This requires the original Papyrus Extender and is built from po3's source. Required by FEC.
- More Informative Console VR beta v0.4.3: This mod edits the UI to show a great deal of additional information on npcs, items, and other objects when the console is opened, similar to the way MFG console worked for Oldrim.
- ElSopa - HD Grindstone Redone SE 1K v1.0: Grindstone Redone. New Mesh. New Textures. No ESP. Optional Texture Resolutions.
- Frozen Electrocuted Combustion - v4.9.6: Applies visual effects to NPCs and the player, when killed by air, ash, dragons, drain, fire, frost, fear, lightning, poison, soultrap, steam and sun damage status effects.
- Frozen Electrocuted Combustion VR v4.9.6: Applies visual effects to NPCs and the player, when killed by air, ash, dragons, drain, fire, frost, fear, lightning, poison, soultrap, steam and sun damage status effects. VR version that requires original FEC to run.
- Frozen Electrocuted Combustion - Enderal Fix v1.1: Loading Enderal with this ESP will allow you to use Frozen Electrocuted Combustion. If it still crashes change the load order.
- Skyland Imperial and Nordic Tents v1.2: Skyland Imperial and Nordic Tents introduces 4k tent textures for Nordic and imperial tents. Skyland tents offers a brand new mesh for the large Nordic fur tent for better visuals.
- Water in Wells - Mesh-only Animated Wells v0.6: Include SMIM texture for those who don't use SMIM.  Improved normal map on Ravenrock well grate.
- Clothing Iron - 4K v1.1: Remesh and 4K retexture of the clothing iron.
- R.A.S.S Cold Breath for Enderal v1.0: Modified the R.A.S.S plugin so the cold breath effect works in Enderal's colder regions.
- NPC Pathing Fixes (Suncoast) v1.0: Improved the NPC pathing and added new areas that are now path-able in the Sun Coast.
- Forgotten Dungeons - Palm Cove v1.01: Forgotten Dungeons implements cut content, originally made by SureAI, with updates and fixes to fit seamlessly into the game.
- Dust Pit Revised v1.0: Immersive rework of Dust Pit Arena.
- Weather Fixes v1.0: Fixes some issues with Enderal weathers which increases compatibility with some weather-related mods. (e.g. R.A.S.S., Storm Lightning)
- Intense Sandstorms v1.01: Increases the intensity of sandstorms in the Desert.
- Oorbaya Replacer v1.0: Replaces the models Oorbayas with high quality alternatives.

Updated Mods
- Enderal SE Update v2.0.9: Update for Complete Enderal for Skyrim Special Edition. 
- Enderal SE - Bug Fixes v1.29: This mod fixes several issues with the game and also includes some small gameplay/balance fixes.
- Enderal VR - Patch v3.0: Fixed pipe smoking: player is no more stuck after smoking.  Increased camera height in akropolis to ease the use of higher perks (triggering the lowest perks might require to crouch).  Slight improvements in mq03, scene 3.  Removed the dialoguemenu.swf check introduced in enderal se 2.09 (modification of _00e_questfunctions).
- SkyUI v1.2.0: Newly picked up items are now highlighted.  New SEARCH! feature.  Have lots of items in your inventory? Search! Don't scroll!  Bug Fixes. (The new Highlight and Search features do not work if using "Dear Diary")
- DynDOLOD Resources SE v3.00 Alpha-16: DynDOLOD is a set of simple tools based on xEdit/xLODGen to automatically create a Skyrim mod based on the load order which adds distant LOD for objects and trees to Skyrim. By combining DynDOLOD with xLODGen users can create drastically enhanced static object LOD + tree LOD and the new, optional dynamic distant object LOD in a few simple steps.
- Spell Perk Item Distributor VR v5.1.0: SKSEVR plugin that can be used to add spells/perks/items/shouts/packages/outfits/keywords/factions to every NPC in the game, using config files. This is the VR version built from po3's source.
- moreHUD VR v1.0.5: Fixes a rare random CTD due to a bad hook.
- LocationalDamageSKSE VR v0.7.2: Fix issue with missing impact VFX & improve stability. Big thanks to FlyingParticle for finding the issue!
- Flinching for VR Magic can trigger flinching v1.4: A little mod that allows the player and NPCs to flinch when hit.
- HIGGS VR v1.4.5: Hand/weapon collision, realistic object grabbing, and gravity gloves-style mechanics for Skyrim VR.  Detection of whether a hand is in a position to grab something now works properly when the palm is inside the collision geometry of the object.
- Spell Wheel VR v1.2.5: SOS armors are now correctly detected and not included in the wheel.  Wrist bars are now enabled by default. Added new wrist bar support for RealVirtualMagic (RVM) mod: Brainpower. 
- Sprint Jump VR v1.1.2: Fixed a bug that caused a momentary pause 1 second after landing from a sprint jump. Fixed a bug that can potentially cause a freeze/ctd, some other optimizations. Fixed a bug that caused super speed after landing from sprint jumping when weapons are sheathed.
- VR FPS Stabilizer v1.3.2: Please see Nexus changelog for updates.  Mod is disabled by default in this Wabbajack release and is only used for its console features to disable TAA FX.
- Embers XD v2.4.8: Ember fires are now smaller and of varying size.  Improved campsite shading.  Some clipping fixes.
- Animated Forge Water v0.4: Improve animation.
- MRP 2.6 Small Update v2.6.2: Added the misc sacks, dlc01 torture pole, dlc01 bucket bloody and the ice wraith teeth.
- High Poly Project v5.3: An on going process to improve the models of the game with more polygons, UV edits or just replace them all together. SMIM was the inspiration and the lack of similar mods led me to make this.
- Satchel Hotfix v1.0: Small hotfix for v5.0 purple satchel.
- WiZkiD Carriages v1.2: Added burntrubblecart01.nif
- Storm Lightning for SSE and VR v1.4.12: Separated thunder files in the fomod by No Delay (Immersive) and With Delay (Realistic) choices.  The mod now uses thunder files that are converted to XWM. Apparently WA files can cause CTDs for some people.  A few thunder chance adjustments for ultra realistic preset.
- CC's Enhanced Ore Veins SSE Edition v9.0.1: Redid all from scratch. Remade mined ore meshes in blender. All files are BC7. Iron is no longer red. Fixed cubemap issues. Adjusted mesh EM settings.
- Riverville Catacombs SE v1.01: A small improvement to a transparent wall.
- Diverse Weather v1.12: Reduced volumetric lightning in fog weathers.
- Enderal SE - True Storms v1.02: Fixed the volumetric lightning with the heavy fog weathers.
- Enderal - Donkey v2.4: Enderal replacer. This changes the textures of donkey.nif & donkey_barrel.nif, custom variations on every donk.
- Enderal SE - Undercity Arena Fix v.1.02: Improved NPC pathing in the arena.  Slightly repositioned Gur Hal Nan so he's further away at the start of the battle.
- Bank of Ark SE v1.01: Fixed some floating/clipping objects. Some optimization improvements. Removed custom vault doors (they caused crashes for some). Added an optional file that adds the custom vault doors.
- Craftable Bound Weapons v1.1: Added the mystic versions of each conjurable weapon, requiring double the black soul gems and 75 smithing or conjuration.  Added an unbound dagger and it's mystic variant from the DLC.

### v1.102:
Release date: October 2nd, 2021

New Mods
- Underground - A Dungeon Texture Overhaul v1.2: An ambitious dungeon retexturing project which starts with caves and Nordic dungeons.
- 1K Farmhouse Fences SE Version 2 v1.0: Two new fences for Skyrim farmhouse wovenfences available in 4k, 2k and 1k.
- Skyrim Textures Redone - High Hrothgar 2K v1.0: Complete texture overhaul for High Hrothgar, Offers studio quality baked normals and baked ambient occlusion maps with proper specular maps to correctly reflect the environments.
- The Halls of the Greybeards - A High Hrothgar Retexuring v1.01: A retexturing of High Hrothgar. There are 4 versions. A standard version with 4k diffuse and 2k normals, 4k diffuse and 4k normals and a dark version with 4k diffuse and 2k normals, 4k diffuse and 4k normals. This mod fixes a ton of texture layout issues within the meshes too.

Updated Mods
- Sprint Jump VR v1.1.1: Mission critical update. Fixes problem with previous version where game may crash when loading a saved game.
- Spell Perk Item Distributor VR v5.0.4: Tentative fix for VR bug where DLC formIDs failed upon lookup.
- Fluffworks (Fluffy Animals) v1.0: Removed the optional ESP plugin.

### v1.101:
Release date: October 1st, 2021

New Mods
- Magic Improvements for Skyrim VR v1.0.2: Vastly improved dual casting, spell effect size scales based on magicka percentage, and additional options for aiming spells in VR.
- 4K Stockade v1.0: 4K, 2K, or 1K retexture of the stockades seen around Skyrim.
- Fluffworks (Fluffy Animals) v1.0: Enhanced fur on animals using shell texturing.
- Meditation Area Fixes v1.0: Fixes some issues in the meditation area.

Updated Tools
- DynDOLOD Standalone 3.0 Alpha-44

Updated Mods
- Scoped Bows SE v1.3.1: "Cell" and "Worldspace" data removed from ScopedBows.esp with xEdit to resolve issue with Skyrim worldspace data being injected into Enderal.
- VRIK V0.8.1. In-Dev Build 28: INI updated. Spell casting feature set to "When Hand Closes + Opens" to allow casting of elemental spells by quickly squeezing your fist and then opening your hand when using Index controllers or Touch controllers with grips (Kiwi grips recommended).
- DynDOLOD Resources SE v3.00 Alpha-12
- NavigateVR v1.5: Renamed in-game map to "Map of Enderal" and removed broken "Map of Skyrim" map from plugin using xEdit.
- Sprint Jump VR v1.1: Added BeastModeMultiplier for Werewolf/Vampire Lord modes and KhajitMultiplier for Khajit Race. Added SpeedBoostMultiplier for increasing speed while jumping. This allows you to go further with sprint jump. Some code optimizations and fixes.
- Dirt and Blood - Dynamic Visual Effects v2.11: Removed broken "Wash and Rinse" spell from plugin using xEdit.
- Spell Perk Item Distributor VR v5.0.3: An SKSE plugin that can be used to add spells/leveled spells/perks/items/leveled items/shouts/packages/outfits to every NPC in the game, using config files.
- Terrain LOD for Septentrional Landscapes v1.1: All files removed aside from noise texture in \textures\ folder.
- Enhanced Vanilla Trees SE v2.2.1: Twice the branches as Basic. Updates/fixes all 3D LOD hybrid models using the latest DynDOLOD 3 tools. Includes large and RAT/SFO options. DynDOLOD 3+ required to generate object LOD.
- Embers XD v2.3.3: Improved giant campsite ground shading and added variants to cover more terrain types. Attempts at further optimization. Installer improvements.
- Dwemer Pipework Reworked v4.0: Made many optimizations, added new animated parts to the boilers, some new items.
- Flying Crows SSE v1.2: Updated to Form44. Fixed Oldrim waterflows, Checked for errors in SSEEdit. LOD's will require DynDolod 3.0 or higher.
- Misc Retexture Project v2.6.1: A small update, added the fox and wolf pelts and also the chicken.
- Armored Flesh v2.0: Fixed broken Nexus links.

Removed Mods
- Stockade Brown Timber 2K v1.1: Redundant with 4K Stockade.

### v1.10:
Release date: September 1st, 2021

New Mods
- VRIK Neardistance Fix Patch for Build: Sets fNearDistance to 13 to fix mountain flickering.
- Strike Obstruction Systems - Combat Blocking Overhaul v1.03: Blocking can now mitigate damage from blocked Spells, Shouts, Enchants, and Poisons. Timed Blocks can provide greater mitigation, redirect parried spells & arrows, and inflict various debuffs. All features configurable via MCM (Light Plugin).
- SMIM v2.08: A massive project to greatly improve the appearance of countless static 3D models in Skyrim. Basically, this is my attempt to make the Skyrim architecture, clutter, furniture, and landscaping much nicer.
- Septentrional Landscapes SE - 2K v1.3.2: Landscape textures made with 3D Scans. 8, 4 & 2K versions available.
- Inferno - Fire Effects Redux v4.1: Spiritual successor to the original Ultimate HD Fire Effects mod by rheadude with improved meshes and textures!
- 4K SMIM Whiterun Bench v1.1: Retextures the SMIM bench in Whiterun with darker and dirtier options available.
- 4K SMIM Furniture Improvement v1.2: A 4K retexture of SMIM furniture textures.
- 4K SMIM Furniture Chest v1.1: A retexture of the SMIM furniture chests, Upperclass, Weathered, Open and Snow. 4K or 2K.
- Misc Retexture Project v2.6: An ongoing project to find and retexture overlooked items throughout Skyrim.
- Rustic Clutter Collection - SE - 2K v1.0: This is a collection of my Rustic clutter item retextures. The mod includes RUSTIC DINNERWARE, RUSTIC POTTERY, and RUSTIC SILVERWARE. There are also a few other clutter items like mead bottles, wine bottles, the satchel, knapsack, coin purse, strongbox, safe, prisoner cage, and the dwemer lexicon cubes. 2K and 1K versions available. 
- Realistic HD Mods Remastered Collection - 2K v1.0: Collection of all Remastered Realistic HD Series Mods for SSE (All in One).  
- Better Wine Labels - Vanilla v1.0: HD wine label textures for the vanilla wine label and ones added by Legacy of the Dragonborn.
- Better Wine Labels - San's Spiced Wine  v1.1: 2x size and cleaner than vanilla but not that much of an improvement (the label is very small in-game). Can be used with either of the main files.
- Enhanced Blood Textures SE (LITE VERSION) v1.1: A blood overhaul mod.
- WiZkiD Carriages v1.1: A complete replacer for all carriages with high quality textures.
- HD Transparent Smaller Snowflakes 2K v1.0: This mod replaces the default Skyrim snowflakes with Ultra HD Ultra Realistic Transparent Crystal Snowflakes. 
- Rally's Mead Barrels v1.1: Replacer for mead barrels and spigots.
- WEBS v0.2: A complete set of 1k texture replacers for the default webs and cobwebs. 
- Snazzy Furniture and Clutter Overhaul SE v1.73: Comprehensive overhaul of furniture and clutter throughout Tamriel, including: - New HD noble chairs, beds, drapery, Imperial Banners, etc. - Several styles of weapon racks, plaques, and display cases - Many new wall art paintings - More...
- Jabber's 2K Archery Targets v1.0: Retextures the SMIM archery targets with high-quality 2K textures.
- Training Dummies Retexture 4K v1.0: Replaces vanilla training dummies. 2k and 4k Versions. This mod was requested by several people. So here it is! No esp needed. Just a texture replacer.
- Realistic Paper Parchment v1.0: Couldn't find a good texture so I've made one.
- Realistic Paper Scrolls v1.0: Couldn't find a good texture so I've made one.
- Pillows - My HD Version SE v1.0: HD replace for the pillows of all the beds. Adds missing pillows, like to the orcish beds. HD noble beds texture (4K). 
- 4K Bedroll v1.0: Simple texture replacer for the bedroll and an alt texture if you want it.  4K textures.
- Boreal Boats SE - 4K v1.3: A ship and Boat retexture in 8, 4 or 2K, with parallax enabled meshes. The roof now has its own texture with environment mapping, no more sharing textures with whiterun. Ships with optional closed roof version in 8-2K resolution.
- ElSopa - High Quality Buckets SE v1.1: High Quality Buckets. New Meshes And Textures. All Resolutions. No ESP.
- ElSopa - High Quality Buckets SE - HOTFIX v1.2: High Quality Buckets. New Meshes And Textures. All Resolutions. No ESP.
- Skyrim Posts Replacer v1.0: Replaces most of the posts in skyrim and i made it close to the original as possible because I don't want to completely change the original model.
- Tihzz's Lantern HD Replacer 4K v1.1: A simple model replacement for the candlelanternwithcandle01 and candlelantern01.
- Cinematic Light Sprite (Candles and Lanterns) v1.0: Replace candles and lantern lightsprite.
- Organic Riften Leaves 2K v1.02: Quality textures for the fallen leaves in Riften 4K, 2K, 1K.
- Dwemer Pipework Reworked v3.1: Rework of Dwemer pipes, including Dwemer boilers.
- Better Dwemer Spider Textures 4096 Pixel Standard v1.1: Get your Dwemer Spiders ready for their closeups with these brilliant and astounding new textures, built from the ground up with top-quality Dwarven Ingots and entirely too many Photoshop layers. Guaranteed to improve spider productivity by up to 42 percent.
- Stockade Brown Timber 2K: A 4k or 2k retexturing of all stockade wood textures. These are found at farms, in forts, and out the front of mines Three options are now available due to popular request: Old Grey, Painted and Brown!
- Nightingale Pride 4K SSE Edition - With Gems v1.0: High Resolution, Lore Friendly Retexture Of Nightingales Bow and Blade. Polished for SSE EDITION.
- Auriels Holy Bow - REDUX v4.0: I am proud to present a totally remade version of my Auriel's Holy bow mod for Skyrim Special Edition. This mod adds a really cool looking glow to the Auriel's Bow from the Dawnguard DLC.
- Terrain LOD for Septentrional Landscapes v1.1: New overhaul for Terrain LOD landscape textures that corresponds with the texture mods you have installed. Generated with xLODGen. Also contains Tree LOD.
- Sting of the Blue Islands Replacer v1.0: Replaces that Ugly Scimitar with something worthy of betraying the Golden Sickle for.
- Bowgasm SE - Nicos AIO Vanilla Bow Replacer SE v1.1: Optional file is a non-plug in replacer for nearly all Vanilla bows in game with higher poly models, more realistic shapes, and higher resolution textures.
- FusaFusa Project - Fluffy Animals SE v14.2: Increase Fur Volume of Animals. They become more fluffy.
- I Want Better Weapons Iron Dark and Dirty SE v1.0: This is a Dark and Dirty version of my IWBW Iron replacer mod because everyone will like different things. :) Reworked all textures, specular maps, and normal maps to provide a more used and rough appearance to the weapons for those that would like it.
- Dirt and Blood - Dynamic Visual Effects v2.11: Your character will accumulate dirt and blood dynamically, which you can clean by swimming, standing in the rain or taking a bath. The effects are mostly visual only and do not affect gameplay. NPCs will also get bloody as a result of battles. Mod is designed to be simple and lightweight.
- Enderal SE - Dirt and Blood v1.01: Compatibility patch for Dirt and Blood.
- Sighted Crossbows VR v1.2: Sights for Crossbows Skyrim VR.
- Simple Iron Sights for Sighted Crossbows VR v1.0: Changes the sights included in Sighted Crossbows VR into more of a simplistic, medieval style.
- Advanced Alloys Carbon Fiber Reinforced Dwarven Crossbow v1.0: Texture replacer for Dwemer crossbow.
- Jespar Has Steel SE v1.0: Jespar no longer uses toothpicks in battles of life and death.

Updated Tools
- DynDOLOD Standalone 3.0 Alpha-39

Updated Mods
- Enderal SE - Bug Fixes v1.28
- Enderal VR v2.9.2: Minor fix causing a CTD in the begining of the game (nif testing file) thanks to Bolzenschuss and Ashok0.
- VR FPS Stabilizer v1.2.2: Added LODcitychange and LODinteriorchange options to the ini to turn off LODs in cities and/or interiors. Disabled by default.
- DynDOLOD Resources SE v3.00 Alpha-11
- HIGGS v1.4.2: Fix the vrik body disappearing in certain cases while holding a weapon with two hands.  Vrik's head bobbing is now disabled when holding a weapon with two hands.
- NavigateVR v1.5: Updated with new custom Enderalean map.
- Dual Wield Block VR v1.6: No longer treat two-handed weapons as a one-handed weapon + unarmed. This made it so that your offhand while two-handing could trigger a block, and really this mod had no business affecting two-handed weapons at all.
- Enhanced Vanilla Trees v2.2.0: General updates. New 3D hybrid LOD models. 
- Caliente's Beautiful Bodies Enhancer - CBBE v1.6.2: Fixed some seams, fixed zaps and size sliders for bow ties, and added mage gloves from USSEP to the vanilla outfits.
- Stronger Souls v1.1: Fixed a bug where the ghost shader was missing.
- JS Instruments of Skrim SE: Removed ESP file due to FormID problem.
- Embers XD v2.3.0: Added Inferno compatible installation option provided by agentw.
- El Sopa - HD Medieval Anvil SE v1.0: Removed bad mesh from mod to fix visual glitches.
- SkyVRaan - Shimmering VR Waters v1.0.1: Removed Rocky Riverbeds due to massive FPS drops.

Removed Mods
- Deflection v1.8:  Redundant with Strike Obstruction Systems - Combat Blocking Overhaul.
- Pine Branches Redone 4K v2.0: Redundant with Enhanced Vanilla Trees.
- Yee: A New Snowflake Mod - Cathedral Concept v1.0: Redundant with Ultra HD Transparent Snowflakes.
- SC - Mature Skin Specs - CBBE - More Contrast v1.0: Vanilla Bijin skin arguably looks better visually in VR.
- Undercity Relit v1.0: Removed due to possible stability issues.
- Bathhouse Relit v1.0: Removed due to possible stability issues.
- Dal Mercer Relit v1.0: Removed due to possible stability issues.
- Agnod Lighter v1.0: Removed due to possible stability issues.
- Dwemer Automatons Glowmapped v2.2: Redundant with Better Dwemer Spider Textures by Naitrii.
- Enderal SE - Dwemer Automatons Glowmapped v1.0: Redundant with Better Dwemer Spider Textures by Naitrii. 
- Tamrielic Textures SE LOD v1.3.0: Redundant with Terrain LOD for Septentrional Landscapes.

INI Updates
- fMeleeLinearVelocityThreshold=3.0000: Slightly decreases melee sensitivity.

### v1.09:
Release date: July 26th, 2021

Updated Mods
- Spell Wheel VR v1.2.1: Minor fixes with secondary hand order, wrist bar, and "Show Hover Text" settings.
- Enderal VR v2.9.1: Minor fix for "Our Mark on this World" and tavern card games.

### v1.08:
Released: July 26th, 2021

Removed Mods
- ElSopa - Iron Weapons Redone SE v1.1: Removed due to mesh issues which impact the held position of iron arrows when using a bow.

### v1.07:
Released: July 24th, 2021

Updated Mods
- Spell Wheel VR v1.2:  Selection wheel mod for Skyrim VR. It allows you to select spells, weapons, shields, arrows, potions, poisons, food, torch, armors and more without going into a menu very quickly by press of a button or button combinations to spawn the wheel and hold your hand over the item and letting go of the button. It's equipped automatically.

### v1.06:
Released: July 23rd, 2021

New Mods
- Immersive Gathering (Woodchopping and Mining) SE - VR Friendly v1.7:  Chop wood and mine ore for real!
- Armored Flesh v2.0:  A small mod, offering improved visuals for each of the Alteration school's five armor spells.
- Deflection v1.8:  Deflection is a full featured, customizable, performance friendly, balanced, combat overhaul. Designed to work along side other popular combat mods, or as a standalone combat mod in vanilla Skyrim.
- Pretty Animated Potions - VR Edition v1.0:  Yet another animated potions mod. This time in small bottles! 1K retexture. Refracting bottles option available!
- Rally's Candlelight and Magelight Fix SE - VR v1.1:  Fix for the Candlelight Spell and Magelight Spell in SE/VR.
- ElSopa - HD Medieval Anvil SE v1.0:  New Model And Textures For The Anvil. The Hammer And Tongs. Performance Friendly. Ultra Immersive. All Resolutions. No ESP.
- Animated Forge Water v0.3.1:  A mesh only animated forge water replacer with refraction. No ESP. Includes patches for Elsopa and Embers.
- Better Dirt Cliffs and Alphas v4.0:  Overhaul of the meshes & alpha channels involved in blending the top of the dirt cliff with the roots, and the roots with the wall. Covers SMIM meshes too.
- HD Dead Trees and Driftwoods v1.1:  Combine "4K Parallax Treebark" and "Spooknik's - Tundra Trees HD" to achieve HD dead trees and driftwoods. Contains original mods port.
- CC's Enhanced Ore Veins SSE Edition v8.0:  A texture replacement for the ore veins found in mines and around skyrim. This mod also retextures the mined ores and the ingots.
- CC's Enhanced Ore Veins SSE Edition - Patch v8.0.1:  Install this to resolve the issue where all mines revert to vanilla textures when depleted.
- Rustic Alchemy and Enchanting Tables v1.0:  A rustic overhaul of the alchemy and enchanting tables of Skyrim. The aim was to bring real antiquity to these arcane crafting tables as is fitting of their ancient origin.
- El Sopa - Iron Weapons Redone SE v1.1:  Every Iron Weapon Redone. New Meshes. New Textures. No ESP. Performance Friendly. All Resolutions.
- Deadly Spell Impacts v1.7:  Fire, lightning, frost, and spit (Spider/Chaurus) spell impacts now have their own unique textures. This mod also increases the variation in impact size, increases the size of dragon breath impacts, and adds melted snow impacts for fire and lightning spells.
- Visual Animated Enchants v0.2:  A replacer for the visual and animation of the enchantments on weapons to make them more magical and immersive.
- Qwinn's Refined Visual Animated Enchants v1.0:  With L3stat's kind permission, a refinement and fix for various issues with Visual Animated Enchants.
- Adjusted Visual Animated Enchants (No ENB Complex Particle Lights) v1.1:  Tweaks the appearance of enchantments from Visual Animated Enchants. Reduces size and brightness to work better when using ENB, alters flame mesh shapes on unique weapons to fit more closely, and adjusts some colours.
- True Storms Special Edition - Thunder Rain and Weather Redone v1.0.2:  True Storms Special Edition is a complete overhaul of the storm systems in Skyrim SE, including new heavy and unique weathers, loads of new intense sound effects, interior sounds, particle effects, new rain, snow, and dust textures, heavy fogs, new weathers for Solstheim including dust storms, and much more!
- Enderal SE - True Storms v1.0:  Compatibility patch for True Storms.
- Stronger Summons v1.0:  Makes your summoned creatures stronger.
- Seagulls of Skyrim v1.4:  This mod adds seagulls along the coasts of Skyrim and Solstheim, with animated models and sounds from Mr. Siika Seagulls for Skyrim SE!
- Enderal SE - Seagulls of Skyrim v1.0:  Compatibility patch for Seagulls of Skyrim which adds them to the world of Vyn.
- Flying Crows SSE v1.1:  Adds flying crows to various locations around Tamriel to create a more nordic atmosphere in your Skyrim.
- Enderal SE - Flying Crows v1.0:  Compatibility patch for Flying Crows which adds them to the world of Vyn.

Updated Mods
- HIGGS VR v1.3:  Hand collision, physics object grabbing, and gravity gloves-style mechanics for Skyrim VR.
- JS Purses and Septims SE v1.2:  A complete re-creation of Septims, Coin Purses and Coin Piles.
- DUST x2048 By Ramccoid v6.1:  This mod retextures the ambient dust particles which float in the air and also the falling dust effect in dungeons and such places.
- Seaview Lodge SE v1.01:  Seaview Lodge adds a player home in the scenic area of the sea near Ark.
- Diverse Weather v1.1:  Diversifies the weather in Enderal and adds a few new ones.

Removed Mods
- Dragon Replacer (Variant 3-6) v1.01:  Removed to fix invisible dragon glitch.

### v1.05:
Released: July 10th, 2021

New Mods
- WiZkiD Parallax Farmhouses 2k No Parallax v1.4: A complete overhaul of all farmhouses related models with high quality textures. This overhaul includes exteriors, interiors, basement and stonewalls.
- Rallys City Roofs 2K - AIO v1.1: This mod retextures the roofs of houses and market stalls in Whiterun, Riften and Solitude.
- Renthal's Workbench v1.4: New high poly mesh and texture for the workbench.
- Center of the Earth v1.0: Follow Yaronth of Aran's ill-fated expedition to the center of the earth.
- Craftable Bound Weapons v1.0: Allows the player to craft and temper fully functional permanent bound weapons and arrows. Can be crafted at any smithy for 2 filled grand soul gems and tempered for 1 grand soul gem at any grindstone. Fully compatible.

Updated Mods
- Embers XD v2.2.3: Reinstalled with Vanilla Flames for improved fire FX.
- Kolapon's Undead Creatures Replacer v1.2u: Removed ESP file to fix crash during "Old Wounds" quest.
- DynDOLOD: Updated with better tree LODs.

Removed Mods
- R's Windmill v1.0: Removed due to clipping issues with terrain.
- Farmhouse Stonewalls 4K 2K by CleverCharff v1.3:  Duplicate functionality with WiZkiD Parallax Farmhouses 2k No Parallax.

### v1.04:
Released: July 9th, 2021

New Mods
- Enhanced Vanilla Trees SE v2.1.0: Better Vanilla Trees? Sign me up! All-In-One tree overhaul package with enhanced Vanilla trees. Supports RAT, SFO Branches, SFO Snowy Pines, and more!

Updated Mods
- Equippable Tattoo Skins UNP + CBBE: Fixed broken Nexus links.

### v1.03:
Released: July 8th, 2021

New Mods
- JS Purses and Septims SE v1.1: A complete re-creation of Septims, Coin Purses and Coin Piles.
- VR Refit - JS Purses and Septims Resized v1.0.1: A VR mod for smaller coins, coin purses, and coin piles from JS Purses and Septims. It also patches the invisible coin purse drop sound bug.
- JS Instruments of Skyrim SE v1.1: A complete remake of the Lute, Flute & Drum. Comes in 2k and 4k versions.
- Seaview Lodge SE v1.0: Seaview Lodge adds a player home in the scenic area of the sea near Ark.

Updated Mods
- Tharael's Afterlife v2.0: The mod adds an option to make Tharaêl your companion after completing Dark Chambers of Our Mind.  It also changes the side room in the house in the Nobles Quarter.

Removed Mods
- Celtic Endralean Penny v1.0:  Incompatible with JS Purses and Septims SE.

### v1.02:  
Released: July 3rd, 2021

New Mods
- Destructible Bottles Extended v1.5:  Hit the bottle and smash it in pieces! Latest version 1.5 includes also some glazed pottery items such as pots, jugs, plates and bowls.  Converted to Form 44.

Updated Mods
- HIGGS VR v1.2.2:  New INI options configured to allow grabbing/pulling/etc. with the arrow hand while a bow is out but no arrows are equipped, as well as with the offhand while having a two-handed weapon in the main hand.

### v1.01:  
Released: June 26th, 2021

New Mods
- Instant Equip v1.0: SKSE plugin that essentially skips weapon drawing and sheathing animations.
- Immersive Draw Sheathe Sounds v1.0: This improves the Draw/Sheathe sounds for use in VR.
- Smaller Insects v1.1: This mod aims to resize the scale of animals in Skyrim to give a better immersive feelig in VR / First person.
- Riverville Jail SE v1.0: Expands upon the Riverville Jail by adding a watchtower, a secret exit and more.
- Bank of Ark SE v1.0: Adds new models for corridors, vault doors/vault door numbers and makes some changes to the interior of the Ark Bank.

Updated Tools
- Synthesis v0.19.2: A framework and GUI to construct a single Bethesda game patch from many patcher sources. Designed to allow any program to work as a patcher as long as it conforms to the CLI API.
- xLODGen Beta 83: Tool for generating terrain LOD.

Updated Mods
- Dear Diary - Paper UI Replacer for Enderal SE v3.0.5: Updates Dear Diary for Enderal compatibility.
- VR Menu Mouse Fix v1.3: Enables mouse for SkyUI-VR. You can use your controllers to control the cursor like a smart tv remote.
- HIGGS VR v1.2.0: Hand/weapon collision, realistic object grabbing, and gravity gloves-style mechanics for Skyrim VR.
- Golden Mare Mill SE v1.01: Golden Mare Mill provides a quaint player home in the scenic area of Riverville which is rewarded for the completion of the quest "Secrets from the Can".
- The Notice Board Redefined for Enderal v1.1: Replaces low quality notes on bounty boards with notes from The Notice Board Redefined.

### v1.0:  Initial Wabbajack release.
Released: June 12th, 2021
