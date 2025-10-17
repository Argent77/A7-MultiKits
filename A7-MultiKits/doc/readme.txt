Multiclass Kits
~~~~~~~~~~~~~~~

Version:    1.0
Author:     Argent77

Download:   https://github.com/Argent77/A7-MultiKits/releases/latest
Discussion: https://www.gibberlings3.net/forums/topic/40601-mod-multiclass-kits
            https://forums.beamdog.com/discussion/89800/mod-multiclass-kits


Overview
~~~~~~~~

With this mod it is possible to install true multiclass kits from any combination of single-class kits, which allows
unusual combinations such as Kensai/Assassin or Berserker/Wild Mage/Swashbuckler. Custom kits from mods are considered
as well if detected.

The mod supports any Enhanced Edition games since patch version 2.0 or later, except PsT:EE.


Installation
~~~~~~~~~~~~

This is a WeiDU mod, that means it is very easy to install. Simply unpack the downloaded archive into your game directory
and run either "setup-A7-MultiKits.exe" (Windows) or "setup-A7-MultiKits.command" (macOS). Follow the instructions and
you are ready to start.

To uninstall, run "setup-A7-MultiKits.exe" (Windows) or "setup-A7-MultiKits.command" (macOS) again and follow the prompts.

Note for Siege of Dragonspear (SoD):
GOG and Steam both install the "Siege of Dragonspear" expansion in a way that is not moddable out-of-the-box. You must
first install the mod "DLC Merger" on your SoD installation before this or any other WeiDU-based mods can be installed.
DLC Merger can be downloaded here: https://github.com/Argent77/A7-DlcMerger/releases/latest


Installation Order & Mod Compatibility
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The number of installed multiclass kits will most likely exceed the game's hardcoded limit of available kits.
For that reason it is strongly recommended to install this mod after all other mods that may install new kits.
Since true multiclass kits don't count against the hardcoded limit of the game engine it won't cause any further issues
in that regard.

This mod may overlap slightly with the "Multi-classed kits" components of Talents of Faerûn or other mods that install
multiclass kit variations, but should otherwise be technically compatible.

Note:
Because of hardcoded behavior of the game engine multiclass kits that allow arcane spellcasting may introduce some traits
of selected specialist mages, like abjurers or conjurers, even if the selected kits don't specialize on these spell schools.


Components
~~~~~~~~~~

The mod contains 10 individual components, one for each available multiclass combination:
- Fighter / Mage
- Fighter / Cleric
- Fighter / Thief
- Fighter / Mage / Thief
- Mage / Thief
- Cleric / Mage
- Cleric / Thief
- Fighter / Druid
- Fighter / Mage / Cleric
- Cleric / Ranger

Each component offers two options how to install kits:

1. All kit combinations

This option installs all compatible multiclass kit combinations based on existing single-class kits. Some combinations may
be skipped because of mutually exclusive race or alignment restrictions.
For instance, the multiclass kit "Dwarven Defender / Wild Mage" may be unavailable as the Wild Mage kit is not available
to dwarves.

CAUTION:
The number of potential kit combinations, as well as potential installation time, grows exponentially with the number of
available single-class kits.

2. Choose manually

This option provides an interactive menu that allows to install one or more multiclass kit combinations. Selected kits
can be named individually by the user.


Credits
~~~~~~~

Coding and testing: Argent77


Copyright Notices
~~~~~~~~~~~~~~~~~

The mod "Multiclass Kits" is licensed under the "Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License"
(https://creativecommons.org/licenses/by-nc-sa/4.0/).


Version History
~~~~~~~~~~~~~~~

1.0
- Initial release
