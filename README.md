# Aliens Eradication VR addon

![Aliens Eradication](https://i.imgur.com/HBsEsni.jpg)

A GZDoom VR addon mod for Doom/Doom2 by Ermac (https://www.reddit.com/user/iAmErmac)

This addon mod aims to enhance VR experience (in GZDoom VR) with the Aliens Eradication mod for Doom. The VR mod is compatible with both the [Aliens Eradication TC](https://www.moddb.com/mods/aliens-eradication-tc/downloads/aliens-eradication-tc) *(from Sep 18 2020)* and the [Aliens Eradication TC (new update)](https://www.moddb.com/mods/aliens-eradication-tc/downloads/aliens-eradication-tc-new-update) *(from Jan 4 2021)*.

To download the Aliens Eradication VR mod click the download button below:

[![Download Now](https://raster.shields.io/github/downloads/iAmErmac/Aliens-Eradication-VR-addon/total)](https://github.com/iAmErmac/Aliens-Eradication-VR-addon/releases/latest)

[<img src="https://cdn.ko-fi.com/cdn/kofi2.png?v=2" height="36" alt="Buy me a Cofee!">](https://ko-fi.com/ermac)

## Features
* 3D Weapon models
* Better weather system, heavy raining and thunderstorm in open areas (may impact VR performance)
* Enhanced bullet tracer and smoke effects on enhanced weapon mode
* HD SkyBox
* Optional Infrared Vision (to use when Dynamic Lights are off)
* Optional abilities to self-heal, dash, double jump, ledge climbing etc.
* A few performance options to remove some map effects (may help getting more fps)
* Various fixes to make the mod compatible with both the older and the latest Aliens Eradication mod (HUD fix, ammo capacity fix etc.)

## Installation

### GZDoom VR (PC-VR)

Latest GZDoom VR: https://github.com/hh79/gz3doom/releases

To install:

    Extract GZDoom-VR to a folder.
    Copy original doom wads into the folder.
    Copy this mod into the folder.
    Run with gzdoomvr.exe -iwad doom2.wad -file ALIENS_ERADICATION_BASE_MOD ALIENS_ERADICATION_MAPSET LATEST_MOD_FILE_NAME
  
OR use ZDL: https://github.com/lcferrum/qzdl/releases to load mods with GZDoom

### QuestZDoom (Oculus Quest)

To play on QuestZDoom it is advised to download this fork which contains a lot of performance improvements and options to optimize the gameplay for better performance: https://github.com/emawind84/QuestZDoom/releases/latest

You can then download Aliens Eradication mod from QuestZDoom Launcher or download the mod files and copy them into /sdcard/QuestZDoom/mods/

To optimize gameplay in QZD:

    Disable Sky Dome in Options > Display options > Opengl renderer
    Set a lower value for 'light cull distance' in Options > Display options > Dynamic lights options
    Set a lower value for 'max collected sub sectors' in Options > Display options > Dynamic lights options
    
    Make sure heavy raining is turned off in Weather fx settings. You can also bind a controller button
    to toggle rain and then use it to turn off raining completely (which will help increasing fps while outside)
    
    To get significant fps boost you can disable dynamic lights completely (flashlight will stop working)
    With dynamic lights off, turn on Infrared Vision from 'Aliens VR options' to see in the dark
    
    You can disable some environment elements from 'Aliens VR options' to have a little fps boost
    
Known issue: Flashlight may not work with the latest Aliens Eradication mod in QuestZDoom. In that case download the older version from QuestZDoom Launcher or use the Infrared Vision ability.

## Wad and mod support:

Aliens Eradication mod (https://www.moddb.com/mods/aliens-eradication-tc) should work with most of the Doom maps. Furthermore the VR addon includes a script to replace most of custom weapons from other mappacks with the Aliens Eradication Weapons.

## Credits

* Kontra Kommando, Payload4367 - for Aliens Eradication mod
* Sgt Mark IV (Brutal Doom) - for enhanced effect sprites and codes
* Apeirogon - zscript Simple Weather effects (modified by Ermac)
* Cherno - for SimSun shader
* Tim Barton - Space SkyBox image

## 3D Model credits

* M4A3 Pistol, M37A2 Shotgun, Power Loader - Aliens Colonial Marines
* M260B Flamethrower, M56B Smartgun - Aliens vs. Predator
* M41A PulseRifle - https://sketchfab.com/3d-models/aliens-m41a-pulse-rifle-b4aa3609a8474a5799f8487371ee7a64
* Combat Knife - https://sketchfab.com/3d-models/adrian-shephards-combat-knife-10325ec3b92848979e751637b746df5c
* Satchel Charge - https://gamebanana.com/mods/180574
* All 3D models and model textures edited and modified by Ermac
