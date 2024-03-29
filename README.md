Skyrim VR Minimalistic Overhaul

Get the best Mod Packs from AAA PCVR Discord: https://discord.gg/RwZvZG6qf3

Best way to show your appreciation is to endorse on Nexus and post images/videos of this mod list on Reddit/Youtube.  

This modlist is designed for 3070 and up.  Entry level hardware would be 11700 + 3070, Virtual Desktop Medium, 45 FPS reprojected to 90. 

For all crash issues, drop crash.dateTime.log from My Documents\Skyrim VR\SKSE in chat.  All other issues, specify GPU and headset.

- [Installation](#installation)
- [Starting The Game](#starting-the-game)
- [I Need Higher Image Quality](#i-need-higher-image-quality)
- [I Need More FPS](#i-need-more-fps)
- [Updating to New Version](#updating-to-new-version)
- [Add New Mods](#add-new-mods)
- [Controls](#controls)
- [Changing Language](#changing-language)
- [Changing Weather ENB and Community Shader](#changing-weather-enb-community-shader)
- [Changing NPC Body](#changing-npc-body)
- [NSFW](#nsfw)
- [Starting A Scene](#starting-a-scene)
- [Changing NPC Outfits](#changing-npc-outfits)

## **Installation**

- Installation Video: https://www.youtube.com/watch?v=b6npjiJMOss
- Do not waste time if you are using a pirated copy of the game, Steam VR version is required, you will have random problems with pirated cversion
- Download the zip file from Nexus, extract into .wabbajack file
- Download and run Wabbajack program itself from https://www.wabbajack.org/ and choose the install from disk option, install to a root folder not shared by Skyrim VR like  D:\SKYRIMVR_Overhaul, as MO2 needs full lock to the entire directory
- Antivirus will occasionally flag Wabbajack files or even textures from Nexus, it is safe to ignore, please see Wabbajack Discord for this well known issue.  You may need to whitelist the directory it installs to as well as the downloads
- You do not EVER need to delete and install a Wabbajack list from scratch, it is a 100% file sync
- Typical download errors are caused by Nexus server issues.  Quit Wabbajack, restart, overwrite to resume and you won't lose any progress
- If the error is about a file that should be part of standard Skyrim installation (i.e. INI file), set the game to English, do a Steam file validation

## **Starting The Game**

- Once installation is complete, open MO2 from the installed folder and run "Play Game (SKSE)" from upper right corner, everything is already included and ready to go out of box
- Disable Dynamic Resolution in Game!  Super sampling in game should be set to lowest in-game
- When starting new game, stand still wait for all the start-up scripts to run and finish if you are using NSFW version which takes a minute to install Sexlab animations 
- Mods/plugins are disabled for a reason, do not mass enable all or sort plugins with LOOT, if you did, restore mod order with back arrow on mod tab, restore plugin order with back arrow on plugin tab
- There are several ways to start the main quest, check out: https://www.nexusmods.com/skyrimspecialedition/mods/272

## **I Crashed**

For all crash issues, drop crash.dateTime.log from Documents\My Games\Skyrim VR\SKSE.

- Depend on your headset you may need to launch Steam VR ahead of the time before opening the game in MO2, if your game still crashes before Bethesda logo and you see "Unable to Initialize VR" in crash log, uninstall and reinstall Steam VR
- Leave everything in the modlist on default.  Don't EVER use Loot Sort or Enable All.  When in doubt, disable all the mods you added, restore original modlist then plugin order with back arrow top of each tab, then turn on your mods/changes one at a time to find the problem
- Clean install Skyrim VR and/or Fallout 4 VR: https://github.com/Kvitekvist/FUS/wiki/Prepare-PC-for-modlist#clean-skyrim
- Increase virtual memory to at least 20GB https://www.windowscentral.com/how-ensure-best-vr-performance-your-pc
- Whitelist antivirus/defender on MO2 folder/Skyrim VR folder, disable it just to be sure to test
- Reset/clean install your GPU drivers and Steam VR, set all settings to default, close as many background programs as possible
- Disable any overclock or undervolt on CPU/GPU
- Use Virtual Desktop and Steam VR for maximum stability and compatibility, do not mess with Open Composite until later
- Reboot your PC, things do get stuck in memory especially on GPU driver crashes

## **I Need Higher Image Quality**

- Disable dynamic resolution in game
- Make sure your encoding in Oculus, Virtual Desktop and/or Steam Link are set to manual bit rate
- Consider enabling DLAA if you are a Nvidia user as they provide better anti-aliasing than TAA, at the cost of 10% performance
- 16 - 24GB VRAM users can consider replace the major texture packs like SRP 4K, 202x with 4K version

## **I Need More FPS**

- Make sure Steam VR resolution is always set to 100%, for Meta/Pico only change device resolution through Oculus software or better yet, Virtual Desktop
- In game super sampling slider should be set to lowest
- AMD users: reduce resolution
- Nvidia users: Try DLAA + FSR balanced, or reduce resolution
- Disable everything under ENB and CS if you need even more FPS.  Enable Lux Brightness template in right panel plugins section and optionally Glamur Reshade to compensate
- I strongly recommend Virtual Desktop for all Quest and Pico users for the best balance between compatibility, reliability and performance
- For Open Composite https://www.reddit.com/r/skyrimvr_unrestricted/comments/17jjmbn/virtual_desktop_open_composite_xr_comparison/
- Please see the in-depth FPS article: https://www.reddit.com/r/skyrimvr_unrestricted/comments/17kccl5/skyrim_vr_2023_fps_stress_testing_cs_vs_enb/

## **Updating to New Version**

- With the exception of major version upgrades like 1.x to 2.x, indoor saves are 99% safe between versions
- It is however not possible to predict save stability if you added/removed mods, or test every iteration of every save game.  Review change log and make changes manually is always the safest way to update the list and keep the changes you made
- You can use [NoDelete] in front of installed mods like "[NoDelete] Conduit" to keep them from being removed, however you will still need to manually put them back into load order
- Alternatively check out https://github.com/matm-git/Reactivate-MO2-modlist for a script to re-enable mods automatically

## **Add New Mods**

- Always have a separate save game before adding new mods, in case you need to remove and revert
- In general any mod without specific requirement is safe to add to the end of the list
- Any mod that requires Address Library will need a VR specific DLL unless specifically stated by author.  For mods newer than Nov 2021, check to make sure you are installing SE version 1.5 version of the mod, AE or SE 1.6 DLL will instant crash
- Any mods that need to be in root folder will need to be put into the root folder of Essential Boot Files (back up existing files first).  This modlist uses Root Builder so your actual root folder is 100% clean, and you should never put files there directly

## **Controls**

- Enable VRIK binding in mods section for grip to interact.  Index users, check FUS controller guide for Index bindings: https://github.com/Kvitekvist/FUS/wiki/Controller-bindings-guide
- If you play seated, edit Auto Sneak mod's INI and change height percentage, see Nexus page for details.  Or disable them altogether
- Highly recommend checking out VRIK, HIGGS, and Spell Wheel pages on Nexus to learn all the options of these amazing mods

## **Changing Language**

- Change Steam language
- Right click on the mod "Essential Boot Files" and edit Skyrim.ini to language of your choice,

[General]

sLanguage=ENGLISH

[Fonts]

sFontConfigFile=Interface\FontConfig_pl.txt         

- Disable audio mod Voices EN part 1 and 2 and install one of the language packs: https://www.nexusmods.com/skyrimspecialedition/mods/18115

## **Changing Weather, ENB, Community Shader**
- Tutorial: https://www.reddit.com/r/skyrimvr_unrestricted/comments/17hoexy/minimalistic_overhaul_changing_weather_enb_and/
- Turn off current weather, CS and ENB in MO2 mods, enable new weather, CS and ENB and appropriate weather add-on's
- Click back arrow from top of plugins tab on ghe right to sort the plugins correctly
- Right click on Overwrite in MO2 mods bottom left section (last mod on the list), Clear Overwrite to remove exiting weather/CS/ENB files

## **Changing NPC Body**

- Reinstall included CBPC, CBBE 3BA, SOS, HIMBO and BNP skins, go through the FOMOD options, whether you want older skins, pubic hair, more bounce, less bounce, softer, harder, bigger or smaller . . . it is all there
- Search for "3BA Preset" from Nexus and install them, they will be auto-distributed to NPC's, you can remove my two 3BA preset packs and replace with more Kardashian or more Abercrombie Fitch presets.  If you only keep one 3BA preset then all of your NPC's will use that body.
- Edit the morphs.ini in AutoBody mod folder if you want more specific assignment than random distribution, please see AutoBody nexus page for more details.  You can assign by race, faction, specific NPC, and much more

## **NSFW**

- **NSFW** Showcase Video: https://www.naughtymachinima.com/video/77837/skyrim-vr-2023-nsfw-showcase-one-click-wabbjack-install-aaa-graphics-and-physics
- New games should auto-activate Sexlab, if you are using an old save follow the instructions below
  - In Mod Settings (MCM) - Enable Sex Lab and install it, this will take 30 second to 1 minute, do not do anything else during this time  
  - In MCM - Go to Sex Lab Animation Loader, click enable all the animations then register all the animations, I have included 100+ animations from Billly and Nibble,   - This will take 15 to 30 seconds, turn off anything you dislike
  - In MCM - Go to Sex Lab Tools and bind a button to the Tool key (on Oculus Quest 2 I use right joystick click), this allows you to activate animation selection during the action, so you can go from position to position, and more importantly, reset the camera as part of choosing a new animation
- I recommend you save the game here so you don't have to repeat the above
- In Sex Lab there are countless customization options, I personally use Loose First Person in VR, and set Hand to Hover so you can move your hands during scenes for Virtamate level interactions thanks to PLANCK.
- Strongly recommend different save games to indulge in your senses. SL especially with large groups of NPC's, coupled with PLANCK's physics is not healthy for your main progression saves.

## **Starting A Scene**

- You get new Mass Match Maker target/AOE spells automatically, they are self-explanatory.  Cast them on yourself and an NPC, wait a few seconds, and the scene starts.
- In MCM - Go to Sex Lab Tools and bind a button to the Tool key (on Oculus Quest 2 I use right joystick click), this allows you to activate animation selection during the action, so you can go from position to position, and more importantly, reset the camera as part of choosing a new animation
- Your grab needs to be within the context of the animation, i.e. pat head during BJ, grab arm during doggy, if you do something that is not intended within the animation or push the NPC too far in one direction it will go out of sync, you can use SL Tools to change scene and reset the animation
- In first person (default), use your hand to push back and hold NPC for best view and avoid clipping.  For hands free operation, use third person view from SL VR tab
- Read through the SL MCM, it is one of the best made mods in terms of quality and feature set, you can enable/disable just about anything you like or dislike

## **Changing NPC Outfits**

- In inventory open AddItem book to get the AddItem spell, this is an spell that allows you to get item from any installed mods, the three installed DX outfit packs have a lot of clothing to get started
- In your inventory there is a new "Ring of Fashion Designer", which when equipped, gives you ability to override an NPC's equipment
- You use Simple Item Spawner to get an outfit, then give it to any NPC of your choice
- In SexLab you can disable the stripping option so the NPC wears outfit of your choice during the act
- Any outfit mod for CBBE 3BA/3BBB is compatible, you will need to run BodySlide in MO2 dropdown and build the outfits for the body
