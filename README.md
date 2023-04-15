Skyrim VR Minimalistic Overhaul

Regular Version: https://www.nexusmods.com/skyrimspecialedition/mods/83995

NSFW Version: https://www.nexusmods.com/skyrimspecialedition/mods/86817/

Best way to show your appreciation is to endorse on Nexus and post images/videos of this mod list on Reddit/Youtube.  

This modlist is designed for 3060TI and up.  I am playing on 11700 + 3070, Virtual Desktop High (1.35x native Quest 2 resolution which shines with FSR upscaling), 45 FPS reprojected to 90.  For all crash issues, drop crash<dateTime stamp>.log from My Documents\Skyrim VR\SKSE in chat.  All other issues, specify GPU and headset.

- [Installation](#installation)
- [Starting The Game](#starting-the-game)
- [I have a much better GPU than 3070](#i-have-a-much-better-gpu-than-3070)
- [I need more FPS](#i-need-more-fps)
- [Open Composite XR](#open-composite-xr)
- [Updating to New Version](#updating-to-new-version)
- [Add New Mods](#add-new-mods)
- [Controls](#controls)
- [Changing Language](#changing-language)
- [Changing Weather ENB](#changing-weather-enb)
- [Changing NPC Body](#changing-npc-body)
- [NSFW](#nsfw)
- [Starting A Scene](#starting-a-scene)
- [Changing NPC outfits](#changing-npc-outfits)

## **Installation**

- Antivirus will occasionally flag Wabbajack files or even textures from Nexus, it is safe to ignore, please see Wabbajack Discord for this well known issue.  You may need to whitelist the directory it installs to as well as the downloads
- You do not EVER need to delete and install a Wabbajack list from scratch, it is a 100% file sync
- Typical download errors are caused by Nexus server issues.  Quit Wabbajack, restart, overwrite to resume and you won't lose any progress
- If the error is about a file that should be part of standard Skyrim installation, set the game to English, do a Steam file validation
- Do not sort plugins with LOOT, restore plugin order with back arrow on plugin tab if you messed it up.  

## **Starting The Game**
  
- AMD/GTX users disable DLAA and Nvidia Reflex in MO2 mods to avoid hard crash.  Enable TAA in game to compensate
- Always start the game with Play Game (SKSE) in MO2, do not open Steam VR ahead of the time.  If MO2 gets stuck before opening Steam VR, close MO2 and end all VR Server related processes in task manager
- Disable Dynamic Resolution in Game! 
- Steam resolution 100% for Oculus users, use VD or Oculus app resolution scaling instead.  Super sampling in game lowest on slider for all  
- When starting new game, stand still wait for all the start-up scripts to run and finish if you are using NSFW version
- Oculus/Pico users, I strongly recommend Virtual Desktop
- If you must use Oculus Link, Airlink, or use another headset, see section on Open Composite XR

## **I have a much better GPU than 3070**

- Use FSR quality in MO2 settings section of mods or in the case of 4080/4090, FSR ultra
- On 16GB cards consider upgrading textures to 4K.  202x, SRP and BNP Skin 4K make the biggest difference
- Re-run XLodgen, Texgen and Dyndolod with 4K settings, update Dyndolod Resource and Dyndolod 3 from Nexus: https://stepmodifications.org/wiki/SkyrimSE:2.0.0#xLODGen

## **I need more FPS**

- Enable FSR performance instead of balanced in MO2 mods
- For older hardware, consider disabling ENB from settings section in MO2 mods.  Azurite Weather looks best without ENB 
- Running out of VRAM is the easiest way to make the game unplayable.  On 8GB cards, disable additional TV/monitors if you are running multiple monitors, set primary monitor to 1080p

## **Open Composite XR** 

- Significantly better than Steam VR for Airlink/Quest Link users, also worth trying for other headsets
- Disable VR Performance Kit (must), enable Open Composite XR in MO2 mods section
- Install Open XR Toolkit for upscaling instead: https://mbucchia.github.io/OpenXR-Toolkit/
- Consider increase streaming bit rate via Oculus Debug tool if you use Airlink: https://www.reddit.com/r/OculusQuest/comments/1219cad/i_found_a_way_to_use_air_link_at_over_500mbps_lol/
- More Info: https://www.nexusmods.com/skyrimspecialedition/mods/85389

## **Updating to New Version**

- With the exception of major version upgrades like 2.0, I will never break a save intentionally
- It is however not possible to predict save stability if you added/removed mods, or test every iteration of every save game.  Review change log and make changes manually is always the safest way to update the list and keep the changes you made
- You can use [NoDelete] in front of installed mods like "[NoDelete] Conduit" to keep them from being removed, however you will still need to manually put them back into load order
- You will still lose sort order and personal FOMOD choices when you update, so consider making updates manually based on change logs

## **Add New Mods**

- Always have a separate save game before adding new mods, in case you need to remove and revert
- In general any mod without specific requirement is safe to add, place them in the right category on left side and right side.  For example new quests/locations should go after JK mods, new follower's should go after NPC mods.  Do not sort with LOOT
- Any mod that requires Address Library will need a VR specific DLL unless specifically stated by author.  For mods newer than Nov 2021, check to make sure you are installing SE version 1.5 version of the mod , AE or SE 1.6 DLL will instant crash
- Any mods that need to be in root folder will need to be put into the root folder of Essential Boot Files (back up existing files first).  This modlist uses Root Builder so your actual root folder is 100% clean

## **Controls**

- Enable VRIK binding in mods section for grip to interact.  Index users, check FUS controller guide for Index bindings: https://github.com/Kvitekvist/FUS/wiki/Controller-bindings-guide
- If you play seated, edit Auto Sneak mod's INI and change height percentage, see Nexus page for details.  Or disable them altogether
- Highly recommend checking out VRIK, HIGGS, and Spell Wheel pages on Nexus to learn all the options of these amazing mods

## **Changing Language**

- Change Steam language
- Right click on the mod "Essential Boot Files" and edit Skyrim.ini to language of your choice
- Disable audio mod Voices EN part 1 and 2 and install one of the language packs: https://www.nexusmods.com/skyrimspecialedition/mods/18115

## **Changing Weather ENB**
- Quick Video: https://youtu.be/MjZSNP_ToNI?t=625
- Go indoor and make a save, exit game
- Turn off current weather and ENB in MO2 mods, enable new weather/ENB and appropriate add-on's
- Click back arrow from plugins tab to sort the plugins correctly
- Right click on Overwrite in MO2 mods bottom section, Clear Overwrite to remove exiting ENB cache

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
- Your grab needs to be within the context of the animation, i.e. pat head during BJ, grab arm during doggy, if you do something that is not intended within the animation or push the NPC too far in one direction it will go out of sync, you can see SL Tools to change scene and reset the animation
- In first person (default), use your hand to push back and hold NPC for best view.  For hands free operation, use third person view from SL VR tab
- Read through the SL MCM, it is one of the best made mods in terms of quality and feature set, you can enable/disable just about anything you like or dislike

## **Changing NPC outfits**

- In MCM go to Simple Item Spawner and enable the spell, this is an alteration spell that allows you to get item from any installed mods, the three installed DX outfit packs have a lot of clothing to get started
- In your inventory there is a new "Ring of Fashion Designer", which when equipped, gives you ability to override an NPC's equipment
- You use Simple Item Spawner to get an outfit, then give it to any NPC of your choice
- In SexLab you can disable the stripping option so the NPC wears outfit of your choice during the act
- Any outfit mod for CBBE 3BA/3BBB is compatible, you will need to run BodySlide in MO2 dropdown and build the outfits for the body
