# Changelog for Journey by Moonlight
*The changelog here will offer more detail than what is provided in the Discord channel. If you're curious on the specifics, feel free to check here!*

## JBM v1.1.1
*Small update with some minor fixes, improvements, and additions. One such addition is a new <a href=https://www.nexusmods.com/skyrimspecialedition/mods/94378>DynDOLOD output<a> with a stronger focus on quality*
### Added
 - ElSopa Animated Celtic Icons for SkyUI
    * Added in as **Optional Content**. Choose between animated icons or icons which match the UI's color palette
 - Unplayable Faction Armors ESLified and RMB SPIDified
    * Provides better compatibility for Unplayable Faction Armors and saves an esp slot
 - Khajiit Char Gen Extended
    * Adds more RaceMenu sliders for Khajiit. I've also fixed the English translation
 - Whiterun Objects SMIMed Dragonsreach Stairs
    * Upgrades the mesh for the stairs up to Dragonsreach
 - Vibrant Map Markers
    * I changed up how the paper map looks and these markers look pretty
 - Hornophobic's Shield-Sisters and Ulfric Replacer
    * Replacers for a few NPCs
 - Whiterun Wooden Walls Replacer
    * **Optional content**. Replaces Whiterun's interior walls with wood, instead of plaster
      
### Fixed
 - eFPS
    * Added a patch to fix a faulty occlusion plane in Falkreath
 - Northern Roads
    * Updated the JBM patch to smooth out some seams in Falkreath Hold
 - FWMF
    * Removed unused seasonal variants as they were causing issues for some users
 - FWMF Caro Tuts Paper Map
    * Switched the map to one without Hold icons and titles, as they clashed with map markers too much
 - LODGen
    * Updated with optimized meshes and textures
 - TexGen
    * Updated with optimized textures
 - DynDOLOD
    * Renamed the **Quality** version to **Balanced** and updated it for better optimization.
    * A new **Quality** output is also available, from JBM's files page. See above for a link
 - Bashed Patch
    * Rebuilt and fixed a couple notable errors, like some outfits not having torso armor

### Updated
 - Unplayable Faction Armors
    * Switched to the standalone version for RMB SPIDified
 - Spaghetti's Orc Strongholds AIO
    * Updated to the latest version to fix duplicate formIDs
 - Fish Plaque Fixes and Improvements
    * Updated to latest version
 - Scorching of Skeevers
    * Updated to latest version
 - Universal Cured Eye Serana Fix
    * Updated to latest version
 - Skyrim Objects SMIMed Noble Furniture
    * Updated to latest version
 - The Welkynar Knight
    * Updated to latest version
 - Belethor's Sister
    * Updated to latest version
 - eFPS Unofficial Patch Hub
    * Updated to latest version for the Northern Roads patch for better performance and removal of faulty occlusion planes

## JBM v1.1.0
*A massive update to JBM! Provides plenty of new mods, fixes, updates, improvements, performance tweaks, modularity improvements, and so on.*
**Big thanks to Alabast and Geborgen as well! This update shrinks the *.wabbajack* file down from ~3gb to just 500mb due to their help**
### Added
  - Slightly Better Honey Nut Treat
    * An improvement to one of the most-overlooked and most-heinous objects in the game!
  - HS Player Homes Hjerim + Lux Patch
    * Another of HS's wonderful player home overhauls
  - NPC Stuck in Bleedout Fix
    * Yet another great fix from wSkeever for vanilla problems
  - Spectris
    * The amazing **Pentapox** has released another audio overhaul so of course it's included!
  - Lenny's Eidar Cheese Wedge
    * A new mesh and texture for one of the goofy cheese wedges that gets ignored
  - NPC Parry Stagger Overhaul
    * New animations for combat :D
  - Dynamic Sprint
    * Smooth's latest sprint animation rework, shipped with proper transition animations
  - Impactful Blocking
    * This existed in JBM before its release but was removed due to issues. Said issues are no longer present, so I added it back :)
  - DPI Scaling Fix
    * A new and useful utility-type mod from Doodlezoid
  - Aura's Inventory Tweaks
    * Great new changes for the inventory
  - Object Categorization Framework
    * Required as a master
  - Green Water Cubemap Fix
    * Another nice fix from wSkeever
  - Heart of Dibella Quest Expansion
    * Improvements on a vanilla questline
  - CO 61 Converus Bugfix
    * Resolves a crash some players can run into when using Community Overlays
  - Simplest Witcher Horses
    * A patch between Simplest Horses and Witcher Horses
  - Sweets and Such ESPFE
    * A simple ESPFE conversion of Sweets and Such
  - Sorcerer
    * A great new Simonrim addition
  - Xelzaz
    * One of the best custom companions available!
  - Improved Follower Dialogue Lydia
    * Makes Lydia more of a companion and less of a lame old NPC
  - Bijin's Lydia
    * New look for Lydia
  - Pandorable's Black-Briar Ladies, Dashing Defenders, Shield Sisters, and Warrior Women
    * New looks for multiple NPCs
  - Koralina's Jordis Replacer
    * New look for Jordis
  - Subclasses of Skyrim + SE Downgrade
    * A mod I wanted to include but couldn't due to SE restrictions, now available for SE thanks to a backport
  - Spaghetti's Orc Strongholds AIO
    * One of the finalized amazing AIO overhauls from Spaghetti
  - aljo's Skyrim Unbound Addons
    * Adds new spell options to Unbound's starting list
  - Charming Nirnroot
    * New textures and models for Nirnroot, plus glowing effects
  - TM's Nirnroot Sound Replacer
    * Ribbit ribbit...
  - Moonlilia's SPID Compendium
    * That's right, I included one of my own mods! Distributes some outfits which weren't very present via SPID
  - Know Your Enemy 2 + Armors and Integration
    * Newest version of KYE with some improvements
  - Large Stagger Animations for Loki's Poise
    * A JBM addon to replace medium stagger with large stagger animations when Poise empties
    
### Fixed
 - Improved Camera SE
   * Fixed an issue which could cause crashes and fixed the jittery stopping
 - Flat World Map Framework (FWMF)
   * Fixed the map not working for some users (hopefully!)
 - Lux Patches
   * Moved in load order to ensure changes are given priority
 - Gear Spreader
   * Forced whitelist usage over a blacklist to prevent goofy distribution, like NSFW items. Much more consistent now, I'd say
 - Experience
   * Fixed an issue with the default INI having a max level of 0.
 - Nemesis
   * Fixed the **No OStim** cache not working
 - Schlongs of Skyrim
   * Removed Werewolf anatomy (lmao) and updated to a new version to prevent crashes, see below
 - Modern Combat AI
   * Moved lower to let Lawless override
 - Photo Mode
   * Resolved an issue with Skyrim Upscaler which could cause crashes
 - Poise
   * Fixed player poise health and NPC damage. It's more consistent and balanced
 - Regen Cap
   * Removed from optional as changes are encouraged to handle via MCM. Also fixed the infinite stamina and magicka issue, I hope
 - Valhalla Combat
   * Added stamina cost to attacks to counter goofy stamina regen and make combat a little more engaging
 - Northern Roads
   * Made fixes with a JBM-specific patch
 - EVG Animation Variance
   * Removed torch animations as they cause crashes
 - Immersive Equipment Displays
   * Fixed the keybind, now it's mapped to Shift + Backspace instead of just Backspace
 - N.U.D.E
   * Lowered the timer for underwear application to counter unintentional nudity
 - HIMBO
   * Removed Hide Armor refits as they clipped too much. Made physics a little more rigid to counter goofy behavior
 - CBBE 3BA
   * Adjusted physics to be a little more rigid
 - CBPC Equipment
   * Adjusted physics to be more rigid
 - Fairies
   * Created a small patch to adjust sounds, so they don't sound like demons wishing to steal your soul. That's not as cute!
 - Synthesis Outputs
   * Fixed wonky distribution from the OWL output. Also removed a patcher as it broke some things
 - Read the Room
   * Now only activates on the hotkey as other options cause issues
 - Meta Files for Non-Nexus Links
   * Thanks to Geborgen, meta files should now properly-direct. Thanks again!
 - Traverse the Ulvenwald
   * Fixed some shrubs and trees swapping to winter variants in Autumn
 - Erdtree Gildergreen Replacer
   * Fixed the tree not being allowed to load in due to DynDOLOD and Ulvenwald
 - Moonlilia Graphics for JBM
   * Fixed an issue with a couple textures not having proper normal maps

### Updated
 - Dynamic Weather and Time Detection Settings Loader
   * Updated to latest version
 - TB's Carrot Cake
   * Updated to latest version. Now distributes carrot cake across Skyrim!
 - Lux
   * Updated to latest version
 - Skyrim Upscaler
   * Updated to latest version. Updated INI files to match
 - Gore
   * Updated to latest version
 - Immortui
   * Updated to latest version
 - Sure of Stealing
   * Updated to latest version
 - Precision Creatures
   * Updated to latest version
 - Northern Roads Patch Collection
   * Updated to latest version
 - Northern Roads Patch Collection Addons
   * Updated to latest version
 - Northern Roads Patch Compendium
   * Updated to latest version
 - Northern Roads JBM Moonlilia Fixes
   * Updated to match new patches and removed ones
 - Bow Rapid Combo
   * Updated to latest version
 - OpenSex Addon Hub
   * Updated to latest version
 - OStim Lovers
   * Updated to latest version
 - ER Moveset
   * Updated to latest version
 - JBM Skyrim Priority
   * Renamed to **JBM - Performance** for clarity as it includes INIs related to performance, not just Skyrim Priority
 - JBM INI Files
   * Updated Profile INIs so NPCs use ammo and updated Upscaler INIs for the latest version of Skyrim Upscaler
 - Moonlilia Graphics for JBM
   * Added new textures and updated some existing ones
 - Traverse the Ulvenwald
   * Updated to latest version
 - Thaumaturgy
   * Updated to latest version
 - Hand to Hand
   * Updated to latest version
 - Adamant
   * Updated to latest version
 - Apothecary
   * Updated to latest version
 - Mundus
   * Updated to latest version
 - Mysticism
   * Updated to latest version
 - Aetherius
   * Updated to latest version
 - SSE FPS Stabilizer
   * Changed to medium settings for better performance
 - Faster HDT-SMP
   * Updated to latest version. Uses performance settings too
 - CBBE
   * Updated to latest version
 - Remiel + BiR Replacer
   * Updated to latest version
 - Serana Dialogue Add-On
   * Updated to latest version
 - Serana Dialgoue Add-On Patch Hub
   * Updated to latest version
 - Auri's Kaidan Banter Patch
   * Updated to latest version
 - JBM Difficulty Options
   * Moved some options around and added a separator for Experience INIs
 - Vulcano
   * Updated to latest version
 - Lunaris
   * Updated to latest version
 - Natura
   * Updated to latest version
 - Natura Spriggans
   * Updated to latest version
 - Praedy's Staves AIO Patch Hub
   * Updated to latest version
 - Bloodmoon
   * Updated to latest version
 - EasyNPC Merge
   * Updated to use new NPC replacers
 - LODGen for JBM
   * Updated for new changes
 - TexGen for JBM
   * Updated for new changes
 - DynDOLOD for JBM
   * Updated for new changes. Options are provided for **Quality** and **Performance**
 - Bodyslide for JBM
   * Updated for new changes. Now auto-downloads to make the .wabbajack file smaller
 - Phoenix Compendium
   * Reinstalled and added in its new music

### Removed
 - Kabu's Frost Salts
   * Removed as it doesn't work as well without ENB
 - Mirayasu Map Markers
   * Low resolution textures
 - Sons of Skyrim SPID Housecarls
   * Conflicted with the SPID Compendium but otherwise does the same thing, just with different armors
 - Ryn's Valtheim Towers
   * Breaks AI in the area
 - Ryn's Whiterun City Limits
   * Very heavy on performance due to added clutter
 - Ryn's Bleakwind Basin
   * Amps up difficulty *far* too much
 - Scarcity
   * Implementation isn't quite right for the goals of JBM
 - Wait Your Turn
   * No longer needed
 - Tamaska Werewolf Replacer
   * New mesh messed up animations
 - Know Your Enemy Redux
   * Removed in favor of the newest version of Know Your Enemy
 - Turn of the Seasons Happy Little Trees
   * Removed as HLT is no longer used
 - Happy Little Trees
   * Removed as its changes don't show up due to Ulvenwald
 - Happy Little Trees DLC Base Object Swapper
   * Removed as HLT is no longer used
 - Happy Little Shrubs
   * Removed the esp, kept its meshes and textures
 - Happy Little Trees Alternate Stumps
   * Removed the esp, kept its meshes and textures
 - Skyrim Arrow Overhaul
   * Quiver script causes far too many problems and brought confusion. Arrow options were overwhelming and harmed build variety. Feature creep
 - 2K SMIM Whiterun Stockade
   * Removed as it's overwritten by my custom visuals
 - Markarth Outskirts
   * Very heavy on performance

## JBM v1.0.9
 *Very small update exclusive to the **Discord** server. Provided some fixes and improvements but nothing big.*
 
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
