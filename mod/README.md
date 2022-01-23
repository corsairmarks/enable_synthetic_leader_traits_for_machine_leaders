# Overview

Does what [Leader Traits: All Eligible Species Traits](https://steamcommunity.com/sharedfiles/filedetails/?id=2499031295) does for species-based leader traits, but for Machine Units - they gain the Synthetic leader traits.  In order to qualify, the Machine Unit leader(s) must belong to a Machine Intelligence with the Synthetic Age ascension perk, to a non-gestalt empire with the Synthetic Personality Matrix technology, or an Ancient Machine Intelligence.

Requested by [Marrow](https://steamcommunity.com/profiles/76561198257383427).

# Changes

Adds new effects, events, and on_action hooks to ensure Machine Unit leaders gain the same special traits as Synthetic leaders.

## Compatibility

All the mod's logic is implemented in standalone events and effects which should not conflict with other mods.  Does **not** require Leader Traits: All Eligible Species Traits.

Not included in my compilation mod [Subtle Polish: A Collection of Fixes and Enhancements](https://steamcommunity.com/sharedfiles/filedetails/?id=2522974089).  This mod is compatible with the compilation.

Built for Stellaris version 3.3.\* "Libra."  Not compatible with achievements.

### Recommended Companion Mods

Like leaders?  Try a couple of my other leader-related mods that work with this one.

* [Leader Traits: All Eligible Species Traits](https://steamcommunity.com/sharedfiles/filedetails/?id=2499031295) enables your non-Machine Unit leaders to have all the species-based leader traits for which their species has the related trait
* [Leader Traits: Scientist AI Assistant Upgrader](https://steamcommunity.com/sharedfiles/filedetails/?id=2498166286) will help your scientists upgrade to "Sapient AI Assistants" from "Custom AI Assistants" when you discover the right technology
* [Leader Traits: Enhanced Randomisation](https://steamcommunity.com/sharedfiles/filedetails/?id=2553806265) will help your leaders get species-appropriate traits (no more substance abusing robots!) and can randomly get _any_ of the class-appropriate traits when levelling up
* [Retain Leaders from Integrated Subjects](https://steamcommunity.com/sharedfiles/filedetails/?id=2553818684) will let you choose whether you would like to keep leaders from integrated subjects or conquered/infiltrated primitives

### When to Install

This mod can be safely added or removed from your savegame after the game has started.  It is implemented through custom events and effects without adding gameplay objects.  If you remove it, your game will work normally.

## Changelog

* 1.0.0 Initial version
* 1.1.0 In order to get the Synthetic leader traits, an empire must be one three things: Fallen Machine Empire, Machine Intelligence with the Synthetic Age ascension perk, or a non-gestalt empire with the Synthetic Personality Matrix technology (normal empires usually cannot get Machine Unit leaders, but you might via mods)
* 1.2.0 Mark as compatible with Stellaris 3.2 "Herbert" - no script changes
* 1.3.0 Mark as compatible with Stellaris 3.3 "Libra" - no script changes

## Source Code

Hosted on [GitHub](https://github.com/corsairmarks/enable_synthetic_leader_traits_for_machine_leaders)

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.