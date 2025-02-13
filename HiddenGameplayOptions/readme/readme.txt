Reveal Hidden Gameplay Options
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Version:    4.7
Author:     Argent77

Download:   https://github.com/Argent77/A7-HiddenGameplayOptions/releases/latest
            http://www.shsforums.net/files/file/1223-reveal-hidden-gameplay-options/
Discussion: https://forums.beamdog.com/discussion/64524
            http://www.shsforums.net/forum/654-hidden-options-ee/


Overview
~~~~~~~~

The Enhanced Editions provide a great number of settings that are not directly accessible in the
in-game options menu, but instead have to be manually enabled or disabled in the game's
configuration file which might discourage less computer-savvy players from using them at all.

This mods adds a number of useful options directly to the game, which includes the (in)famous
debug console, various graphics and feedback settings, and more.

All Enhanced Edition games patched to v2.0 or higher are supported, which currently includes BG:EE
(with or without SoD), BG2:EE, IWD:EE, PST:EE and EET.


Installation
~~~~~~~~~~~~

This is a WeiDU mod, that means it is very easy to install. Simply unpack the downloaded archive
into your game directory and run "setup-HiddenGameplayOptions.exe".

Note for Siege of Dragonspear (SoD):
GOG and Steam both install the "Siege of Dragonspear" expansion in a way that is not moddable out
of the box. You must install a mod called "DLC Merger" on your SoD installation before this or
any other WeiDU-based mods can be installed.
The mod can be downloaded here: https://github.com/Argent77/A7-DlcMerger/releases/latest


Compatibility & Installation Order
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The mod supports all Enhanced Edition games patched to v2.0 or higher. It is also compatible with
Pecca's "Dragonspear UI++" and "Infinity UI++", and largely compatible with all of Lefreut's
Enhanced UI variants, K4f4r's Classic BG UI and Tipun's User Interface.
Some options may be moved into other sections when these mods have been detected. The "Improved
Cheat Menu" may also produce some minor visual glitches if Lefreut's Enhanced UI is installed.
Functionality is not adversely affected, however.

The mod can not be installed together with EEUITweaks component "Hidden Game Options". You can
install either one, but not both at the same time.

Patching UI definition files can be tricky. To ensure that a failed patch attempt does not corrupt
the game it will fail with a forced error and restore the original state of the patched files.

It is recommended to install this mod after Tweaks Anthology and any GUI mods. The component
"Improved Cheat Menu" should be installed after any content mods to maximize its usefulness.


Components
~~~~~~~~~~

1. Install all Hidden Gameplay Options at once

This is a convenience option that allows you to install all available options at once, except for
the keybinding options. See more detailed information about individual options below.


The following components are available if you skip the component "Install Hidden Gameplay Options
at once":


2. Improved Cheat Menu

This component expands the cheat menu, which can be opened if the debug console is enabled, by
a number of options:
- A list of available items that can be created in the party's inventory,
- A list of available spells and abilities that can be added to selected characters,
- A list of available stores which can be opened to make purchases, identify items, or peruse
  temple services and rest options,
- A list of available creatures which can be spawned on the map,
- A collection of useful debug and script commands, such as fixing fallen rangers or paladins,
  toggling on/off strref display for game text, changing party reputation, or advancing (game
  or real) time.

The following UI mods are supported:
- lefreut's Enhanced UI (all variants): May produce minor visual glitches which don't affect
  functionality.
- Pecca's Dragonspear UI++
- Pecca's Infinity UI++
- Tipun's User Interface
- Classic BG UI (by K4f4r)

This component is also included in the convenience option "Install all Hidden Gameplay Options
at once".


3. Update resource tables for "Improved Cheat Menu"

This component allows you to update the resource tables used by the "Improved Cheat Menu" without
having to reinstall the whole mod. It doesn't register to the WeiDU.log, so it can be called at
any time as often as desired.


4. Add in-game option "Enable Debug Mode"

Allows you to enable cheat keys and the debug console in the game.

Option can be found in Gameplay section.


5. Add in-game option "Enable UI Edit Mode"

Enabling this setting allows you to use UI edit functionality in the game.

Option can be found in Gameplay section.


6. Add in-game option "Show Strrefs"

Setting this option places string reference numbers in front of game strings.

Option can be found in Gameplay section.


7. Add in-game option "Hotkeys On Tooltips"

When this option is enabled tooltips will display hotkeys when available.

Option can be found in Gameplay section.


8. Add in-game option "Show trigger icons on tab"

Setting this option reveals more information about interactive regions when pressing the TAB key.

Option can be found in Gameplay section.


9. Add in-game option "Allow Spacebar in Dialogs" (only available for PST:EE)

Setting this option allows you to use the spacebar to continue in dialogs.

Option can be found in Gameplay section.


10. Add in-game option "Limits druidic spells for Cleric/Ranger" (not available for PST:EE)

Setting this option limits druidic spell levels to level 3 for Cleric/Rangers (as per D&D rules).

Option can be found in Gameplay section.


11. Add in-game option "3E Sneak Attack"

Setting this option activates Sneak Attack and Crippling Strike, which are special abilities
similar to those from 3rd Edition Dungeons & Dragons rules.

Option can be found in Gameplay section.


12. Add in-game option "Critical Hit Screen Shake"

Setting this option triggers a screen shake whenever a party member rolls a critical hit in combat.

Option can be found in Gameplay > Feedback > Visual Feedback (or Gameplay section in PST:EE).


13. Add in-game option "Show extra combat info"

Setting this option displays all factors that influence an attack roll.

Option can be found in Gameplay > Feedback > Feedback Messages.


14. Add in-game option "Show Game Date and Time on Pause"

Setting this option shows game date and time when activating pause.

Option can be found in Gameplay > Feedback > Feedback Messages.


15. Add in-game option "Disable Area Map Zoom" (only available for PST:EE)

Setting this option disables animation when zooming in or out of the area map screen.

Option can be found in Graphics > Display Options.


16. Add in-game option "Reverse Mouse Wheel Zoom"

Setting this option reverses zoom direction when using the mouse wheel.

Option can be found in Graphics > Display Options.


17. Add in-game option "Pause Game on Map Screen"

Setting this option causes the game to pause whenever the map screen is active.

Option can be found in Graphics > Display Options.


18. Add in-game option "Enable Fog" (not available for PST:EE)

Setting this option enables fog effects on maps.

Option can be found in Graphics > Display Options.


19. Add in-game option "Disable Movies"

Enabling this option disables movie playback.

Option can be found in Graphics > Display Options.


20. Add in-game option "No Cosmetic Attacks" (only available for PST:EE)

Enabling this option shows attack animations only when characters are making real attacks.
This option is already available in unmodded BG:EE, BG2:EE and IWD:EE.

Option can be found in Gameplay section.


21. Add in-game option "XP Bonus in Nightmare Mode" (not available for PST:EE)

Enabling this option allows your characters to get bonus XP in Legacy of Bhaal Mode (BGEE/BG2EE)
or Heart of Fury Mode (IWDEE). This setting will not affect the extra XP granted by the regular
difficulty modes.

Option can be found in Gameplay section.


22. Add in-game option "Trigger Bored Sounds" (not compatible with Lefreut's Enhanced UI (LeUI))

Enabling this option will trigger bored sounds when you haven't assigned actions to your characters
for an extended period of time.

Option can be found in Sounds > Character Sounds or Gameplay > Feedback (PST:EE only).


23. Add in-game option "Frame Rate" (experimental) (not available for PST:EE, not compatible with
    Lefreut's Enhanced UI (LeUI) and K4f4r's Classic BG UI)

This component installs a slider control that can be used to set the desired frame rate of the game.
You can choose between 30, 40, 50 and 60 frames per second. The game's default is 30 fps.

The component is marked as "experimental", as there are situations where setting this option has
no effect:
1. When Options > Gameplay > Feedback > "More Confirmation Prompts" is active.
2. When quitting the game directly to the desktop from a running game.

Option can be found in Graphics section if Dragonspear UI++ is installed, otherwise it can be found
in Gameplay section.


24. Add in-game option "Action Feedback" (not compatible with Lefreut's Enhanced UI (LeUI),
    K4f4r's Classic BG UI and Tipun's User Interface)

This component installs a slider control that can be used to show small symbols around character
sprites that indicate their current action (e.g. fighting, spellcasting or thieving actions).
You can choose between several feedback levels. Higher levels are only effective when option
"Debug Mode" has been enabled as well.

Option can be found in Gameplay > Feedback.


25. Add in-game option "Display Level Up Icon" (only available for PST:EE, requires "Level Up"
    Icon Tweaks)

This option allows you to show or hide the "Level Up" icon, that can be found in the portrait
window or health bar of party members that are ready to level up. It requires the mod "'Level Up'
Icon Tweaks" to be installed, which adds the functionality to toggle visibility of the icon.

Option can be found in Gameplay > Feedback.


26. Add in-game option "Show Area of Effect Range" (not available for PST:EE)

Setting this option displays the range of an Area of Effect spell before it is fired.

Option can be found in Gameplay > Feedback > Visual Feedback.

Note: This option has no effect in games before patch version 2.5.16.6.


27. Add in-game option "Enhanced Path Search"

Improves pathfinding by continuously recalculating the search path of characters.

Option can be found in Gameplay section.


28. Add in-game option "Expire Trap Highlights" (not available for PST:EE)

Controls whether highlighting of detected traps or hidden doors should disappear after while.

Option can be found in Gameplay > Feedback > Visual Feedback.


29. Add in-game option "Show Learnable Spells"

Controls whether a green tint is shown for spell scrolls that can be written to a mage's spellbook.

Option can be found in Graphics > Display Options.


30. Add in-game option "Render Search Map"

Controls whether holding down SHIFT will show an overlay of the static search map for the current
area.

Option can be found in Graphics > Display Options.


31. Add in-game option "Render Dynamic Search Map"

Controls whether holding down CTRL will show an overlay of dynamic search map regions, such as
blocked doorways or the personal space of creatures.

Option can be found in Graphics > Display Options.


32. Add in-game options for Tweak Anthology's "Create Interval Saves" (requires Tweaks Anthology
    component "Create interval saves")

This component installs two options to the Gameplay section:
- Enable Interval Saves:
  Controls whether the game is saved at regular intervals.
- Create Interval Saves during Combat:
  Controls whether interval saves are created even during combat.

Both options are only effective if Tweaks Anthology's mod component "Create interval saves" is
installed.

Options can be found in Gameplay section.


33. Add in-game option "Force Dialog Pause"

Enabling this option forces the game to pause while conversations are active.
This option makes Tweaks Anthology's mod component "Force All Dialogue to Pause" redundant.

Option can be found in Gameplay > Feedback > Visual Feedback (or Gameplay section in PST:EE).


34. Add in-game option for Tweak Anthology's "Restored Loading Hints" (requires Tweaks Anthology
    component "Restored Loading Hints")

Enabling this option shows loading hints from original Baldur's Gate II in the log window of the
game. This option requires Tweaks Anthology's mod component "Restored Loading Hints" to be
installed.

Option can be found in Gameplay section.


35. Update key bindings for priest and/or mage spells

This component recreates the key bindings for priest spells and/or mage spells. It considers all
regular spells and High Level Abilities (HLAs) available at the time of installation, which
includes the original game spells as well as spells added by mods.

It comes in three flavors:
- Update key bindings for priest spells only
- Update key bindings for mage spells only
- Update key bindings for priest and mage spells

This component is not included in the convenience option "Install all Hidden Gameplay Options
at once".


Credits
~~~~~~~

Coding and testing: Argent77

Additional coding help: AncientCowboy

French translation: Gwendolyne, JohnBob

Italian translation: Zaramorte

Polish translation: Cahir

Brazilian Portuguese translation: Nasher, Felipe

Russian translation: Saigon1983, yota13, Austin87

Korean translation: begaborn

Simplified Chinese translation: Lewis Liu

Spanish translation: alaisFcZ, IOVIVO


Copyright Notice
~~~~~~~~~~~~~~~~

The mod "Reveal Hidden Gameplay Options" is licensed under the "Creative Commons Attribution-
ShareAlike 4.0 International License" (http://creativecommons.org/licenses/by-sa/4.0/).


History
~~~~~~~

4.7
- Fixed potential placement issues of frame rate slider if Dragonspear UI++ is installed

4.6
- Updated Simplified Chinese translation
- Updated Project Infinity metadata

4.5
- Added compatibility with Pecca's Infinity UI++
- Added Simplified Chinese translation (thanks Lewis Liu)
- Updated Russian translation
- Fixed positioning of Action Feedback slider in Dragonspear UI++
- Improved installation feedback for the "Install all" component

4.4
- Added Italian translation (thanks Zaramorte)

4.3
- Improved compatibility of "Improved Cheat Menu" with Iwdification and SCS
- Added support for BG2EE version of Pecca's Dragonspear UI++
- Added compatibility checks for Pecca's Infinity UI
- Added compatibility checks for K4f4r's Classic BG UI
- Added compatibility checks for Tipun's User Interface
- Updated French translation (thanks JohnBob)
- Updated Brazilian Portuguese translation (thanks Felipe)

4.2
- Added compatibility with Pecca's Infinity UI++ for "Improved Cheat Menu"
- Added quick filters for the cheat menu lists (areas, items, spells, stores and creatures) to
  "Improved Cheat Menu"

4.1
- Updated Russian translation (thanks yota13)

4.0
- Added new components "Improved Cheat Menu" and "Update resource tables for Improved Cheat Menu"
- Added labels for Project Infinity
- Fixed potential keybinding issues in PST:EE caused by the "Update keybindings" component

3.0
- Added option "Force Dialog Pause"
- Added multiple choice option "Update keybindings for priest and/or mage spells"
- Improved conditions for installing game options

2.6
- Added Korean translation (thanks begaborn)
- Added Project Infinity metadata
- Added German translation for WeiDU prompts
- Added WeiDU SUPPORT information
- Added missing info to readme
- Fixed potential display issues with component names in WeiDU.log and Project Infinity

2.5
- Added two Gameplay options for controlling Tweak Anthology's "Create Interval Saves" feature
- Simplified installation process by removing artificial component to install options individually
- Updated Russian translation (thanks yota13)

2.4
- Fixed a compatibility issue with "Lefreut Enhanced UI" in option "Expire Trap Highlights"
- Fixed several typos in the readme

2.3
- Added Russian translation (thanks Saigon1983)
- Added option "Show Learnable Spells"
- Added option "Expire Trap Highlights"
- Added option "Enhanced Path Search"
- Added option "Render Dynamic Search Map"
- Added option "Render Search Map"
- Expanded frame rate slider to support 60 fps

2.2
- Fixed compatibility issues of slider controls with SoD patch 2.5

2.1
- Improved compatibility with Lefreut's UI mod variants

2.0
- Added option "Set Frame Rate"
- Added option "Action Feedback"
- Added option "Trigger Bored Sounds"
- Added option "Show Area of Effect Range"
- Added option "No Cosmetic Attacks" to PSTEE
- Added option "Enable Level Up Icon" to PSTEE
- Made compatible with EE patch v2.5
- Added two missing strings for option "3E Sneak Attack"

1.3
- Added Polish translation (thanks Cahir)

1.2
- Marked mod incompatible with EEUITweaks component "Hidden Game Options"

1.1
- Added Brazilian Portuguese translation (thanks Nasher)
- Updated WeiDU setup executable to v242

1.0
- Updated WeiDU setup executable to v241 (stable)
- Converted French readme to UTF-8
- Fixed spelling in French translation

0.5-beta
- Added valid strings for option "3E Sneak Attack"
- Updated French translation

0.4-beta
- Added French translation (thanks Gwendolyne)

0.3-beta
- Added workaround to make all options fully working (thanks AncientCowboy)
- Added German translation
- Relocated "Hotkeys On Tooltips" to Gameplay section
- Improved handling of option "3E Sneak Attack"
- Updated several descriptions

0.2-beta
- Initial release
