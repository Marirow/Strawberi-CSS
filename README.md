# PFQ-Strawberi
A series of CSS stylesheets for Pokefarm Q, an accessibility layout for accessing key site functions with the click of a single Strawberi Button.

**Strawberi does not automatically perform actions.** To comply with PFQ TOS (and the limitations of CSS), the Strawberi Button reorganizes inputs on the screen using the ::before pseudo-element. Because the ::before element exists separately from the original inputs, it can be affixed to the bottom of the screen without breaking the rest of the site. To reiterate: Clicking on the Strawberi Button performs the same input as clicking normally. It does not and cannot perform inputs on its own. 

![image](https://github.com/Marirow/PFQ-Strawberi/assets/110361976/b36d9b31-56ff-4011-923a-4cacefea36f6)

*Compatible with PFQ as of 4/2/24. QOL script recommended.*

*Cannot be used for PFNext or any other PokeFarm service.*

*Tested on Firefox.*

## Instructions
1. Access the Site Skins page at https://pokefarm.com/skin.
2. Paste the contents of the release file(s) into the "Extra CSS" section of the Skin Editor.
3. **OR** use my personal skin by pasting **JPM4/strawberi** into the "Other Skin" path and click "Use this Skin."

## Complete-Strawberi.css
- Contains every Strawberi module in a single package. Recommended to inject as-is.
- Individual modules can be disabled by removing the labeled CSS; removing the Core Module (should) prevent all other modules from operating.

### Core Module
- Creates the Strawberi Button(s), allowing the other modules to use them.
- The Strawberi Button sits at the bottom of the screen, taking up one tenth of the viewport.
- Clicking on it presses whatever link or input that the Button is tied to.

### Dialog Module
- Allows the user to close "dialog" prompts without moving the mouse, akin to hitting Enter on the keyboard interface.
- Makes the other modules faster and easier to use.
- Only affects "yes" prompts, not "cancel" prompts.

### Fields Module
- Allows the user to navigate the Fields screen without moving the mouse.
- Makes it easier to "mass click" other users' fields.
- Simplifies berry selecting, PKMN feeding, and field switching.
- The last Button of the last Field instead redirects to the clickback page (/user/~clickback).
- Complements the QOL script's ability to organize PKMN within Fields.

### Party & Scour Module
- Allows the user to navigate the Party and Scour screen without moving the mouse.
- Makes it easier to quickly click/"clickback" other users' profiles.
- Makes it easier to quickly retrieve and reassign PKMN on Scour Missions.
- Simplifies Egg holding, party feeding, showcase feeding, profile switching, and Scour retrieving.
- The last Strawberi Button of the last profile redirects.
- Also closes the Gem prompt after hatching Eggs.
- Works on multiparties, public parties, and private parties.
- Creates a Strawberi Button on the QOL script's "Get More +" feature.
- With the Dialog Module, simplifies reassigning PKMN to the same Scour location multiple times.

### Fishing Module
- Allows the user to navigate the Fishing Area without moving the mouse.
- Makes it easier to fish large numbers of PKMN.
- Simplifies choosing fishing spots, reeling, and throwing Fishing Balls.
- Throws the cheapest Fishing Balls first.

### Boxes Module
- Allows the user to open Treasure Boxes without moving the mouse.
- Makes it easier to open many Treasure Boxes at a time.
- Simplifies opening each Treasure Box category.
- Does not affect BoxBoxes, BoxBoxBoxes, Gragon's Hoards, or Gragon's Gifts (for convenience).
- With the Dialog Module, simplifies viewing the contents of each Box

### Evolution Module
(REQUIRES the QOL script's "easy evolve" function to be active)

- Allows the user to "easy evolve" PKMN in the Farm News screen without moving the mouse.
- Makes it easier to evolve many PKMN at once
- Simplifies clicking on each individual evolution link in the list
- With the Dialog Module, simplifies approving each evolution

### Trade Module
- Allows the user to accept trades without moving the mouse.
- Makes it easier to accept many trades in a row
- Simplifies selecting the "view trade" link and accepting the trade
- Does not affect the Collection Area
- With the Dialog Module, simplifies sending the accepted PKMN to a field

### Lab Module
- Allows the user to refresh the Lab's Egg selection without moving the mouse.
- Makes it easier to refresh many times in a row
- Simplifies selecting the Reload/Reload Now button
- With the Dialog Module, simplifies spending Lab Reloaders
