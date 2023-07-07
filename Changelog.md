# Changelog for Journey by Moonlight
*The changelog here will offer more detail than what is provided in the Discord channel. If you're curious on the specifics, feel free to check here!*

## JBM v1.0.8
*Small improvements to some features. Updates to LODGen and TexGen Outputs for improved performance. Should be save-compatible, technically. See below!*
### Added
  - Dynamic Weather and Time Detection Settings Loader - Minor adjustments to mod to tweak visibility and alertness in different weather conditions
  - Book of Shadows Settings Loader - Slight adjustments to smoke bomb duration and player cough immunity
  - DynDOLOD DLL Settings Loader - No changes made but exists for future changes
    
### Fixed
  - Community Shaders - Disabled terrain parallax as it was resulting in excessive artifacts
  - Gear Spreader - Downgraded to an older version. Excluded various mods from distribution and boosted max distribution
      * Containers should now have actual interesting loot, not just clutter and paintings
      * As it does its changes at the main menu, it might be save-compatible? Feedback is needed to verify, as distribution may only affect new saves
  - moreHUD - Changed which settings loader version is used to resolve it breaking MCM. Changed a few settings and unhid it in MCM
  - Subtle Feminine Sprint Animation by Xtudo - Updated conditions to only play without a weapon and outside of combat. Uses Smooth's otherwise
  - Natural Waterfalls - Gave Simplicity of Sea higher priority to prevent water shaders from messing up
    
### Updated
  - Community Shaders - Updated to latest version
  - Skyrim Unbound Reborn - Updated to latest version with some additional patches included in its FOMOD
  - JBM LODGen Output - Converted to BC7 compression for better performance and slightly-better visuals
  - JBM TexGen Output - Reran with new LODGen Output enabled, removed excess files
  - Ohmes-Raht Personal Tweaks - Ohmes-Raht are now ~4% smaller. They should be even smaller but I don't wanna overdo it. Let me know though yo
    
### Removed
  - Smooth Random Sprint Animation 15% Faster Sprint - Made sprinting look a little janky. Also removed to make subtle sprint work nicer
    
*As with every JBM update, it's recommended that you take any files you've changed and add them to a new mod marked **[NoDelete]** to avoid losing them!*
*A guide for this can be found in #modding-support in the Discord server.*

## JBM v1.0.7
*Even bigger update! OMG! Adds some new mods, improves on QoL, improved performance, and lowered default difficulty slightly. Likely not save-compatible but you're welcome to test and verify! I'll try to do it myself as well.*
### Added
  - Mihail's Ring-necked Pheasants - Adds a new creature to show up in the world, which fits JBM's aesthetic nicely
  - Skyrim Arrow Overhaul Settings Loader - Allows changes to be made without needing an MCM recording
  - SkyRem Economy Settings Loader - Same as above
  - Smooches of Skyrim Settings Loader - Same as above
  - Thugs Not Assassins Confrontation - Adds a little more roleplay to the game, allowing you to confront those who send thugs
  - Water Blending - New Doodlezoid mod, enhances visuals even further!
  - Complex Parallax Materials - Integrates parallax support which may show up on some textures, not all!
  - Gear Spreader - Distributes equipment in the mod to containers, without conflicts
  - BWB Kaidan Bow/Katana - Fixes a texture mismatch and provides even better visuals for Kaidan's weapons
  - PC Head Tracking and Voice Type - Was already supposed to be included but *someone* forgot to tag it. Adds an extra option for a player voice.
  - Improved Camera Patch Collection - Adds support for Scion to Improved Camera
  - Natural Waterfalls Majestic Mountains Patch - Provides a fix for the two mods
    
### Fixed
  - Northern Roads Modlist Fixes - Fixes a seam near Riften and Goldenglow Estate
  - DynDOLOD Output - Updated to hopefully resolve water shader issues. Also lowered quality slightly, boosting performance considerably
    * Performance gain on my specs was about 15 FPS uncapped, should allow the modlist to run better on lower specs too!
  - Synthesis Output - Updated to blacklist some mods from OWL distribution. Effectively, stops enemies from getting wacky or unfitting equipment, like a pan.
    * Yes, a pan, like a skillet. Thank you, Skyrim on Skooma!
   
### Updated
   - Community Shaders - New version to support **Water Blending** and **Complex Parallax Materials** and mapped to F1
   - Diverse Foods - Updated and added a Hearthfire patch
   - Photo Mode - Updated to latest version
   - SkyRem Economy - Adjusted values, making seasons and location less impactful while reputation and the war are moreso
   - Trade & Barter - Lowered selling prices slightly but boosted status bonuses
   - Skyrim Arrow Overhaul - Swapped so that arrows drop on loading a bow if no quiver is equipped, to provide compatibility with **Go To Bed**
     * Also adjusted MCM settings. Bows no longer drain stamina when aiming and heavy armor doesn't reduce stamina regen. Quivers also hold **2.5x** more
   - Spell Tutor - Changed to a progress-based system, bumped the chances of learning up, and lowered chances of tome destruction
   - QuickLoot EE - Disabled in combat and on animals to resolve issues with it not working sometimes
   - Regen Cap - Boosted health regen by 10x (0.1 to 1.0), boosted stamina regen from 15 to 25, and magicka from 3 to 30
      * Makes recovery after the fight nicer but still encourages potions, healing spells, and/or recovery foods
   - Precision - Disabled recoil on objects for the player to make combat in dungeons and corridors less annoying
   - Wounds - Lowered chances for broken bones, increased minimum movement speed, bumped the armor offset up slightly, and improved recovery time for injuries
      * Combat is still challenging but recovery is less punishing while still requiring *some* time away from the fight
   - Mists of Tamriel - Enabled subtle volumetric mists and lowered the chance of morning fog considerably
   - Harvest Overhaul Redone - Improved chances of a higher harvest yield
   - Immersive Interactions - Disabled a couple animations to be less problematic
   - SunHelm - Adjusted profiles to be less demanding, properly-mapped keybinds, and disabled eating/drinking animations due to overlap
   - Road Signs Fast Travel - Lowered gold cost for fast travel via road signs
   - Animated Interactions & Idles - Changed wait idle to random
   - Missives - Improved the gold reward for various radiant quests to make them more worthwhile
   - Honed Metal - Allowed NPCs to access rare materials and lowered the gold cost for requesting crafting services
   - Dynamic Things Alternative - Boosted the experience multiplier to be 5% higher (.25x to .3x)
   - Smooches of Skyrim - oWo. Upped the max number of animation loops
   - Dynamic Wait - Time now ramps up as it progresses. *Zoooooooooooooooom!!!*
   - Official JBM Keymap - Updated to include the new keybind for Community Shaders
   - Format - Slight improvement to the format as well. Sections now have their own headers for link navigation
   
### Removed
   - Scribes of Skyrim - Unfortunately causes issues with text not appearing. Great mod though
     
## JBM v1.0.6
*Big Update! Adds multiple new mods which **should** work with existing saves and updates a few existing ones.*
  - **Added**
      - Photo Mode - Adds new features for taking screenshots
      - Simplicity of Seeding - Quality of life improvements to Hearthfire's planters
      - MQ105SprintTriggerScript Fix - Fix for an issue that can occur with the vanilla main quests
      - Dynamic Wait Settings Loader - Allows for changes made to Dynamic Wait to save without an MCM recording
      - TB's Carrot Cake 2K BOS - Why? Because **carrot cake**! BOS allows it to work alongside the high poly Sweet Rolls :D
      - Cathedral 3D Pine Shrubs - Another great mesh and texture upgrade which matches the JBM aesthetic
      - ElSopa HD Grindstone Hearthfire Patch - Patches the grindstone added in Hearthfire to use the new mesh and textures
      - More Scar Sliders (Northborn Scars - High Poly Head) - Adds more scar options which work alongside Northborn Scars and High Poly Head
        
  - **Updated**
      - Dynamic Bow Animation - New improvements to existing animations
      - Bow Rapid Combo v3 - Again, new improvements
      - Improved Camera SE - Switched to the new **Nexus** release in favor of easier installation
        
  - **JBM Improvements**
      - Official Key Map - Updated to **v1.0.6** to match the new keybinds
      - JBM INI Files - Added INI presets for **Skyrim Upscaler** to further aid installation and save some headache in set up
      - Changelog Format - Cleaned up the Changelog format to help differentiate between changes. **Fixed** and **Updated** are now 2 separate categories

## JBM v1.0.5
  - **Fixed or Updated**
      - Fonts - Reinstalled Font Overhaul and Scribes of Skyrim, overwriting Dragonbreaker UI's custom font. Resolves an issue with text not appearing in books and such.

## JBM v1.0.4
  - **Fixed or Updated**
      - Gore
          - Moved HPH Replacer plugin to a higher priority to resolve texture bug
      - Northern Roads
          - Updated **Modlist Fixes** plugin to resolve seams around Whiterun
      - Moonlilia's Patch Collection for Custom Races
          - Updated animation conditions to stop crouch idle in RaceMenu
      - Glorious Doors of Skyrim
          - Removed Whiterun door replacers to resolve missing textures
      - R's Farmhouses
          - Removed some meshes to fix mismatched textures
      - Dynamic Animal Variants SPID
          - Removed dogs from distribution to prevent mismatched textures
      - Improved Camera
          - Hopefully fixes the meta file to direct to the right URL and version
      - **Format Changes**
          - *Changelog will now simply state mod names on Discord. **Updated** tag is now **Fixed or Updated**. Github page now provides more info.

## JBM v1.0.3
  - **Removed**
      - Equus - Meta file repeatedly causes issues despite attempts to fix it
      - flowchartx64.dll - Comes from CreationKit installs and gives an error if CK is not installed
      - p4com64.dll - Comes from CreationKit installs and gives an error if CK is not installed

## JBM v1.0.2
  - **Added**
      - Reshade - Added **reshade-presets** folder for easier preset additions
  - **Updated**
      - Equus - Hopefully fixes the meta file for new users
      - Improved Camera - Hopefully fixes the meta file for new users
      - Synthesis Output - Updated masters to account for removed mods
      - EasyNPC - Updated the NPC Replacers used
  - **Removed**
      - CreationKit.exe - Removed to save 50 MB of space on installation. *Streamlining!*
      - Synthesis Hotfix - Not needed in v1.0.2. Will remain up for a few days for those on **v1.0.1**

## JBM v1.0.1
  - **Removed**
      - Conditional Expressions Extended from LL
      - QuarterCranks Presets AIO
      - Inari Ears and Tails
          - Currently not whitelisted for Wabbajack downloads
  - **Updated**
      - Improved Camera - Updated its meta file
      - Equus - Updated its meta file. Download is in the Discord if needed
      - Synthesis Output Update - Fixes missing masters as a result of removing Inari

## JBM v1.0.0
  - <a href="https://modwat.ch/u/Moonlilia/plugins">Modwatch</a>
  - Why a Modwatch? It functions as the changelog for the 2k+ mods included in the first release :)
