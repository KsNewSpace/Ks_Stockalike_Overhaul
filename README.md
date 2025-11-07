KSP Stockalike Overhaul
=======================
***A list of mods to overhaul Kerbal Space Program without changing the core gameplay too much***

*by Lukas K. aka KsNewSpace*

![image](screenshots/bonkers.jpg)

*<div align="center">This could be your KSP</div>*

# Caution: Work in Progress

***Please check every mod for dependencies in case I forget to list them***

To download a mod on Github check the right side for "Releases". There you can download the latest mod as a zip file. I like to help but I can't give you full support on everything! If it doesn't work or Module Manager / Kopernicus complain during boot of the game, you forgot something. 

# Motivation

My goal is to bring KSP to 2025 without changing the core gameplay loop too much. The 2.7x rescale makes it a bit more difficult to get around but it works perfectly fine with stock parts. In fact, I think the stock parts are designed for this particular size. They are just OP on 1x, especially the bigger tanks and engines. For the number people: Getting to orbit around Kerbin requires just shy of 4000 m/s DeltaV. Mostly payloads will become smaller and more realistic looking. If you want giant rovers and colonies better prepare for some orbital construction and fuel depots :)

## Common Folder Structure

> SteamLibrary\steamapps\common\Kerbal Space Program\GameData\Parallax_MaskKSC (or any other mod folder name)

# Official Channels

- Tip Jar: [KsNewSpace.shop](https://ksnewspace.shop/) <3
- YouTube: [@KsNewSpace](https://www.youtube.com/@KsNewSpace) (KSP, Coding, Space Stuff)
- Twi..X: [@KsNewSpace](https://x.com/KsNewSpace) (I'm not a Nazi)
- Twitch: [KsNewSpace](https://www.twitch.tv/ksnewspace) (placeholder, I don't really stream but who knows..)
- Business Contact: KsN■wSp■ce@outl■ok.com (replace ■ with sensical vowels)
  - Mails with attachments are sorted out. I will forward your mail to the authorities if it contains illegal or disturbing things.

# My Complate Mod List

## Audio - Visual (mostly)

- [Restock & Restock+](https://github.com/PorktoberRevolution/ReStocked) (Complete revamp of the stock parts plus stock-ish parts that Squad forgot)
  - [RestockPBR](https://github.com/PorktoberRevolution/ReStockPBR) (New PBR materials + re-color for Restock parts)
- [Volumetric Cloud v3](https://www.patreon.com/posts/true-volumetric-87982960) (I use v5 but that one is paywalled.)
- [ParallaxContinued](https://github.com/Gameslinx/Parallax-Continued/) (Greatly improved ground scatter and parallax effects for all planets)
  - [Parallax Mask KSC](https://github.com/KsNewSpace/Parallax_MaskKSC) (Optional configs to properly mask out your custom KSC from ground scatters for 2.7x scale)
- [Firefly](https://github.com/M1rageDev/Firefly/) (Revamped reentry effects)
- [Waterfall](https://github.com/post-kerbin-mining-corporation/Waterfall) (Framework for new engine effects that expand with atmospheric pressure)
  - [Restock Waterfall](https://spacedock.info/mod/3149/Restock%20Waterfall%20Expansion) (Waterfall Configs for Restock, contains its dependencies)
  - [RSMP](https://github.com/dangaffa/RSMP) (Configs for SRBs)
- [TUFX](https://github.com/KSPModStewards/TUFX/) (Post processing effects for KSP to make it look nicer)
  - I provide my config file as optional addon. Put it in the GameData folder directly. You have to apply it ingame.
- [Deferred](https://github.com/LGhassen/Deferred/) (Rendering upgrade for KSP + Screenspace Reflections)
- [Resurfaced](https://github.com/Tantares/Resurfaced) (Shader upgrade for KSP)
- [VaporCones](https://spacedock.info/mod/3805/VaporCones) (Adds vapor cones at transonic speeds. Can be annoying if you fly that speed constantly)
- [RocketSoundEnhancement](https://github.com/KSPModStewards/RocketSoundEnhancement) (Framework to make better sounds)
  - [RSEDefault](https://github.com/KSPModStewards/RocketSoundEnhancementDefault) (Default configs for RSE. Also adds sonic booms, wheel squeek, propeller sounds and more)
- ...

## Functional

- [Sigma Dimensions](https://github.com/Sigma88/Sigma-Dimensions) (Scaling Kerbin and the Kerbol system to a new size)
  - [Parallax Mask KSC](https://github.com/KsNewSpace/Parallax_MaskKSC) (Optional 2.7x scale configs. 2.7x for me is the perfect size to use the stock overpowered parts.)
- [Persistant Rotation](https://github.com/linuxgurugamer/PersistentRotation) (allows crafts to maintain their rotation / aim during time warp)
- [Kerbal Konstructs](https://github.com/KSP-RO/Kerbal-Konstructs/) (Allows you to place structures on planets. For example new runways and buildings)
  - [KSCEnhanced](https://spacedock.info/mod/3654/KSC%20Enhanced%20-%20JNSQ) (Expands KSC with more runways, launch pads and overall fuller design)
- [Community Tech Tree](https://github.com/post-kerbin-mining-corporation/CommunityTechTree) (Integrates parts added by many mods into the Tech Tree)
- [CameraTools](https://github.com/BrettRyland/CameraTools) (Move the ingame camera freely for epic shots. I also use it for the smooth following camera on planes (Dogfight))
- [Distant Object Enhancement](https://github.com/net-lisias-ksp/DistantObject) (Puts real stars into the sky you can hover over to check their names and more)
- [Physics Hold](https://github.com/gotmachine/PhysicsHold) (Allows you to turn off physics of large craft for better performance (stations and colonies). Docking still works!)
- [kRPC](https://github.com/krpc/krpc) (Allows you to start a server within KSP to connect and play KSP from the outside using code. [Documentation](https://krpc.github.io/krpc/))
- [Kronometer](https://github.com/linuxgurugamer/Kronometer/) (Allows you to manipulate the clock in KSP)
- ...

## Quality of Life

- [VAB Organizer](https://github.com/post-kerbin-mining-corporation/VABOrganizer) (Organizes parts and gives them colored icons based on size similar to KSP2)
- [ClickthroughBlocker](https://github.com/linuxgurugamer/ClickThroughBlocker) (Annoyed by clicking on a popup window but suddenly you grab a part of your rocket...?)
- [Community Fixes](https://github.com/KSPModdingLibs/KSPCommunityFixes) (A big patch for KSP that fixes a lot of bugs. Most notably improved loading times.)
- ...

## Mod Dependencies

- [Module Manager](https://github.com/KSP-ModularManagement/ModuleManager) (Loads mods into KSP in a somewhat ordered manner using configs - something_MM.cfg)
- [Sigma Replacements](https://github.com/Sigma88/Sigma-Replacements) (Helps to replace things like the skybox, menus, etc)
- [Omega Structures](https://spacedock.info/mod/2061/Omega%27s%20Stockalike%20Structures:%20No%20Textures%20Required) (KSC parts that can be used by Kerbal Konstructs)
- [Tundra's Space Center](https://spacedock.info/mod/1831/Tundra's%20Space%20Center) Launch Pads that can be used by Kerbal Konstrukts
- [Toolbar Control](https://github.com/linuxgurugamer/ToolbarControl) (Helps mods to manage toolbar icons)
- [Shabby](https://github.com/KSPModdingLibs/Shabby) (Shader assets bundle loader)
- [Harmony](https://github.com/KSPModdingLibs/HarmonyKSP) (Tools for modders)
- [KSP Burst](https://github.com/KSPModdingLibs/KSPBurst/) (Burst compiler to make mods run better & cross platform)
- [SpaceTuxLibrary](https://github.com/linuxgurugamer/SpaceTuxLibrary) (useful functions for mods like color pickers)
- Technicolor - bundles with RestockPBR
- ...

## To Be Continued...
  
![image](screenshots/modlist_110625.jpg)

# Photo Album

![image](screenshots/ksc_01.jpg)
![image](screenshots/fighter_jet_01.jpg)
![image](screenshots/parachute.jpg)
![image](screenshots/shiny_01.jpg)
![image](screenshots/black_hawk_01.jpg)
![image](screenshots/black_hawk_02.jpg)
![image](screenshots/soyuz6x.jpg)
![image](screenshots/sph_01.jpg)
![image](screenshots/orbit_01.jpg)
