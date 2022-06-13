# Silent Hill 2 Enhancements

Project designed to enhance Silent Hill 2 (SH2) graphics and audio for the PC. It also includes scripts to build or modify SH2 audio files (SFX, BGM and Dialog).

Features
Below is a list of features:

Anisotropic Filtering 
- Enable or disable anisotropic filtering.
Apartment Clock Fix 
- Fixes flashlight rendering on the apartment grandfather clock after a failed attempt to push it.
Audio Script Builder 
- Allows you to create or update the SH2 audio files.
Audio Clip Detection 
- Detects when the audio is stopped prematurely and fades out to avoid pops in the sound.
AutoUpdater 
- Automatically updates the module when new versions comes out.
ASI Loader 
- Loads custom libraries with the file extension .asi into the game using Ultimate ASI Loader.
Black Pillar Box Fix 
- Forces all dynamically made letterboxing and pillarboxing to be black in color.
Borderless Windowed Mode 
- Enable or disable windows border. Requires Windowed Mode to be enabled (WndMode = 1).
Catacomb's Meat Cold Room Fix 
- Updates the color and lighting of the catacomb's meat cold rooms to be more like the PS2 version of the game.
Cemetery Lighting Fix 
-Fixes an issue where wrong data is used when saving the game in the cemetery, which can corrupt fog effects.
Chainsaw Spawn Fix 
- Prevents the chainsaw from spawning on a first playthrough, which is a developer-intended design choice.
Closet Cutscene Fix 
- Adjusts visuals during the apartment closet cutscene to resemble the PS2 version.
Creature Vehicle Spawn Fix 
- Fixes an issue where creatures would incorrectly exit from underneath a vehicle.
Custom Hi-Res Font 
- Loads custom font texture font000.tga and fontwdata.bin as width data for the first 224 chars.
Custom Mod Folder Support 
- Enables a custom mod folder sh2e to store modified game files so as to not overwrite native Silent Hill 2 files.
d3d8to9 
- Converts Silent Hill 2 to use Direct3D9 (d3d9.dll) rather than Direct3D8.
Disable High DPI 
- Disables High DPI to prevent issues on systems with high DPI enabled.
Disable Red Cross 
- Disables the low health (red cross) indicator completely. This option is recommended only if you are using a controller with vibration enabled.
Disable Red Cross In Cutscenes 
- Hides the low health (red cross) indicator during in-game cutscenes.
Disable Screensaver 
- Disables the screensaver during gameplay.
DisableGameUX 
- Disables the Microsoft Game Explorer (GameUX) to prevent rundll32.exe high CPU.
DPad Movement Fix 
- Allows movement with D-pad on DirectInput and XInput gamepads.
Effects Flicker Fix 
- Removes the black flicker that appears at the beginning of post-processing effects.
Flashlight Brightness 
- Adjusts flashlight brightness to resemble the PS2 version. Reduces flashlight intensity for environments, but keeps enemies and NPCs bright.
Flashlight Flicker Fix 
- Fixes a bug that would make James' body flash with light if exiting the pause menu while the flashlight is off.
Fog 2D Fix - Fixes an issue on Nvidia graphics cards where the 2D fog is missing.
Fog Fix - Makes the game's fog closer resemble the PlayStation 2's version which is considered the best. Based on Nemesis2000 Fog Fix.
Fog Parameter Fix 
- Adjusts the fog-of-war boundaries for specific areas to fix visual errors.
Fullscreen Windowed Mode 
- Enables fullscreen windowed mode. Requires Windowed Mode to be enabled (WndMode = 1).
Game Load Fix 
- Disables free-saving in a few rooms that would cause game issues upon file loading back into the rooms.
Halogen Light Fix 
- Fixes the prison hallway halogen lights
Hang On Pause Fix 
- Fixes an issue where the game will hang when Esc is pressed while transition is active.
Hospital Chase Fix 
- Correctly syncs an attack animation to the rest of the cutscene that plays out during the Hospital chase.
Hotel Water Fix 
- Restores lighting values for the hotel water.
Improved Storage Support 
- Allows you to save the game when you have more than 2 TB of free space.
Increase Blood 
- Increases the blood pool size of dead enemies to better match the PS2 version.
Increase Draw Distance 
- Fixes distant hallway walls (such as those in the Woodside Apartments) from suddenly appearing. This makes them appear gradually, more naturally.
Left-handed Joystick Support 
- Swaps left and right joystick functions. Useful for left-handed players.
Lighting Transition Fix 
- Makes lighting transition smooth from one light source to another for a few particular areas.
Joystick Camera Movement 
- Sets right joystick mode for search camera movement on controllers.
Missing Wall Chunks Fix 
- Fixes an issue on Nvidia graphics cards where wall chunks are missing in some locations.
Multi-Language Support 
- Restores the language selection in the Options menu.
NoCD Patch 
- Disables the CD check. Note: not yet supported in all game versions.
Noise Filter Tuning 
- Makes the noise filter resemble the PlayStation 2's noise filter.
Piston Room Fix 
- Hides a piston behind a door that should not be seen during a cutscene.
Reset Screen Res
- Resets the display adapter on exit which fixes an issue when using WineD3D casing the screen to go dark.
Room 312 Pause Menu Fix
- Restores the noise filter and bloom effects in the pause menu for Room 312.
Room 312 Shadow Fix
- Prevents distracting shadow flickering while in Room 312 of the Hotel.
Rowboat Animation Fix
- Fixes an issue with rowboat animation if you exit to the main menu and reload the game.
SFX Address Fix
- Dynamically updates SH2 memory with correct index locations for the SFX from the sddata.bin file (required if you are using a modified version of the sddata.bin audio file).
Shader Support
- Includes custom shaders for adjusting color, setting ingame brightness and SMAA.
Soft Shadow Support 
- Adds soft shadows, shadow level intensities, shadow fading on flashlight toggles, and self shadows.
Special FX Fix 
- Restores post-processing effects, which includes depth-of-field, motion blur, and pseudo blooms.
Texture Address Fix 
- Dynamically updates SH2 memory to reserve additional space for large texture (required if you are using a large texture files).
Town West Gate Event Fix 
- Changes James' commentary about the back alley Heaven's Night gate at night to properly reflect the gate's status.
UAC Control 
- Checks if administrator access is required for the game to function correctly and prompts for UAC if needed.
Vibration Support 
- Enables force feedback vibration support for XInput and DirectInput gamepads.
White Shader Fix 
- Fixes an issue on Nvidia graphics cards where certain textures would appear as white when they should be black.
Widescreen Fix 
- Allows the game to fit any sized monitor appropriately and fixes other inherit game bugs.
Windowed Mode 
- Runs the game in windowed mode.
Woodside Apartment Object Fix - Fixes spawning placements for objects in Woodside Apartments Room 205.
