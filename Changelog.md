## v1.2.2
### The Housekeeping Update
* Adds new Calling abilities and rolltable
* Adds Diseases, and respective rolltables
* Adds Miscast tiers 5 and 6
* Adds Magical Goodies and other miscellaneous items
* Adds Housekeeping errata for spells and abilities
* Fixes more typos
* Adds new Housekeeping rolltables for exploration, camping, dungeon generation and NPC inspiration.

## v1.2.1
* Fixes mistyped stats on Hunter
* Fixes mistyped source on Hedgewitch's _Child of Ghal_
* Itemises jobs and specialty classes, which can now be dragged into player character sheets
* Itemises kindred
* Reworked character creation document to support new job and kindred lists
* Adds full spell and performance list displayers
* Removes custom HP in favour of active effects
* Adds all items displayer
* Adds checkbox for enabling crit mod (in favour of active effects)
* Improves sheet and roll message formatting

## v1.2.0
* Updates to Foundry v13 and CSB 5.0.2
  * Note: This version is less compatible with Foundry v12 or less, and CSB 4 or less.
* Fixes Miracle and Fateweave modifiers always disabling explodes, even when the modifier is disabled
* Adds ability to change spell and performance critical range
* Spell, ability and item damages can no longer crit on rolls of 1
* Adds active effect displayer
* Adds light radii and duration to light source descriptions
* Fixed lots of code formatting
* Improves some sheet formatting
* Fixes broken crits on damaged weapon attacks
* Improves weapon info tooltips
* Improves spell formatting in sheet
* Adds reset button to Custom HP Formula in case of broken formula
* Converts most modifiers to active effects attached to abilities
  * Modifiers that still rely on resources will still be tracked in Modifiers instead of the Active Effect displayers
* Adds base modifiers (crit stunt, prone target, etc.) to template sheet
* Converts Sky Passage and Burning Blood into active effects
* Brings NPC sheets up to date with PC sheets, also adds modifier and active effects displayer

## v1.1.0
* Overhauled and itemised modifiers, which double as resource trackers
* Adds base modifiers: Prone Target, Crit Stunt, Dual Wield and Stunned Target
* Adds new modifiers for existing job and specialty class abilities, which may replace base sheet functionality:
-
  * Duelist: Lunge
  * Sage: Miracle (Disables automatic exploding)
  * Occultist: Otherworldly Occulsion
  * Nomad: Painful Memory,
  * Thief: Knife in the Dark
  * Marauder: Blood on the Blade, Suckerpunch
  * Performer: Dramatic Entrance, Silverstep, Solo
  * Gladiator: Beatdown, Theatre of Battle
  * Chaos Knight: Bloodthirst, Burning Blood
  * Pistoleer: Called Shot, Fireworks, Scattershot
  * Kitcheneer: Cold Cut, Flambé
  * Astrologer: Fateweave (Disables automatic exploding)
  * Rose Knight: Lance of the Forest
  * Blademaster: Patience, Strike First

* Adds unarmed strikes to Nomad's Self Preservation
* Traveller's Fortitude now correctly alters Last Breath
* Burning Blood now increases maximum HP
* Adds CSB sheet tutorial to the Character Creation document
* Adds camping tracker scene
* Adds urban exploration example
* Adds default scenes without lighting for easy duplicating
* Updates character sheet modifiers document
* Updates all luck-based macros to have 0 as their default value
* Differently coloured dice for damage types on attacks, spells and items when used with Dice So Nice
* Fixes computing errors in inventory
* Improves ammo tracking and simplifies attack window when weapon does not use ammo
* Ammunition automatically takes up slots depending on the size of the ammunition
* Inventory slots now work rules as written (small items can now stack up to 10, but always count as taking up 1 inventory slot)
* Fixes AppendToDamage not working on secondary damage rolls
* Fixes damage and damage die size changes not reflecting on secondary damage buttons
* Adds GM screen to landing scene

## v1.0.4
* Prevents extra plus symbols appearing on stats with temp modifiers
* Prevents description icons from appearing on items without descriptions
* Adds broken icon to broken items
* Removes annoying tutorial tooltips on spells, weapons and abilities
* Streamlines inventory and equipped items
* Makes attack table clearer
* Fixes some settings tooltips
* Improvements to sheet clarity
* Improvements to weapon sheet clarity
* Starting heavy weapons are now defaulted to 2 slots instead of 1
* Adds blank weapon templates for ranged and melee weapons, large/medium/small
* Fixes alt damage dice displaying non-alt damage dice
* Fixes HP breaking if it ever becomes a decimal number
* Potion Belt item now properly increases maximum slots by 3
* Displays Corruption effects and automates Corruption stats

## v1.0.3
* Fixes hunter ability sources (they are no longer Scholar abilities)
* Fixes Thief abilities multiplying inventory slots
* Fixes ammo not updating correctly when a ranged weapon is used
* Fixes damage modifiers not affecting damage rolls
* Better clarity on main tabbed panel
* Adds ability to append item text to damage rolls

## v1.0.2
* Hard to Kill correctly updates Last Breath
* Adds ShowDescriptionInDamage to weapons
* Improves formatting on stat checks, attacks and damages
* Improves formatting on spell checks and adds easy access to miscasts
* Improves  and streamlines miscast macro and camp encounter macro dialogue window
* Fixes raw spell check rolls not working
* Secondary damage never displays on-sheet if it is not enabled
* Fixes manual explodes rolling multiple dice if the respective weapon has multiple damage dice
* Alters how advantage works in NPC sheets
* Improves formatting of NPC sheets
* Adds custom HP formula
* Fixes normal dice rolls sometimes not rolling until an advantage type is selected
* Fixes wrong roll formula when using the Camp Encounter macro
* Changes default NPC icon

## v1.0.1
* Fixes broken core rolls
* Fixes broken tokens and mismatching names in sample bestiary
* Fixes typos in character creation help
* Adds Starting Gear rolltable (included in character creation help)
* Alters info section on NPC sheets

## v1.0.0
* Initial Commit
