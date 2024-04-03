# 🍓 PFQ-Strawberi
A series of accessibility stylesheets for Pokéfarm Q, accessing key site functions with the click of a single 🍓 Button.

**Strawberi does not automatically perform actions.** To comply with PFQ TOS (and CSS limitations), the 🍓 Button reorganizes inputs on the screen using the ::before pseudo-element. It does not and cannot perform inputs on its own. 

*Compatible with PFQ as of 4/2/24. QOL script recommended.*

*Cannot be used for PFNext or any other PokeFarm service.*

*Tested on Firefox.*

## 🍓 Instructions
1. Access the Site Skins page at https://pokefarm.com/skin.
2. Paste the contents of the release file(s) into the "Extra CSS" section of the Skin Editor.
3. **OR** use the integrated site skin by pasting **JPM4/strawberi** into the "Other Skin" path.

## 🍓 Complete-Strawberi.css
Contains every Strawberi module in a single package. Recommended to inject as-is.

Individual modules, listed below, can be disabled by removing the labeled CSS.

### 🍓 Core Module
- Required.
- Creates the 🍓 Button(s), allowing the other modules to use them.
- Can be modified to change the style, size, and position of the 🍓 Button.

### 🍓 Dialog Module
- Allows the user to quickly close "dialog" prompts, like pressing Enter on the keyboard.
- Makes the other modules faster and easier to use.
- Only affects "yes" prompts, not "cancel" prompts.

### 🍓 Fields Module
- Allows the user to navigate the Fields screen without moving the mouse.
- Makes it easier to "mass click" other users' fields.
- Simplifies berry selecting, PKMN feeding, and field switching.
- The last 🍓 Button of the last Field instead redirects to the clickback page (/user/~clickback).
- Complements the QOL script's ability to organize PKMN within Fields.

### 🍓 Party & Scour Module
- Allows the user to navigate the Party and Scour screen without moving the mouse.
- Makes it easier to quickly click/"clickback" other users' profiles.
- Makes it easier to quickly retrieve and reassign PKMN on Scour Missions.
- Simplifies Egg holding, party feeding, showcase feeding, profile switching, and Scour retrieving.
- Also closes the Gem prompt after hatching Eggs.
- Works on multiparties, public parties, and private parties.
- Creates a 🍓 Button on the QOL script's "Get More +" feature.
- With the Dialog Module, simplifies reassigning PKMN to the same Scour location multiple times.

### 🍓 Fishing Module
- Allows the user to navigate the Fishing Area without moving the mouse.
- Makes it easier to fish large numbers of PKMN.
- Simplifies choosing fishing spots, reeling, and throwing Fishing Balls.
- Throws the cheapest Fishing Balls first.

### 🍓 Boxes Module
- Allows the user to open Treasure Boxes without moving the mouse.
- Makes it easier to open many Treasure Boxes at a time.
- Simplifies opening each Treasure Box category.
- Does not affect BoxBoxes, BoxBoxBoxes, Gragon's Hoards, or Gragon's Gifts (for convenience).
- With the Dialog Module, simplifies viewing the contents of each Box.

### 🍓 Evolution Module
- (REQUIRES the QOL script's "easy evolve" function to be active).
- Allows the user to "easy evolve" PKMN in the Farm News screen without moving the mouse.
- Makes it easier to evolve many PKMN at once.
- Simplifies clicking on each individual evolution link in the list.
- With the Dialog Module, simplifies approving each evolution.

### 🍓 Trade Module
- Allows the user to accept trades without moving the mouse.
- Makes it easier to accept many trades in a row.
- Simplifies selecting the "view trade" link and accepting the trade.
- Does not affect the Collection Area.
- With the Dialog Module, simplifies sending the accepted PKMN to a field

### 🍓 Lab Module
- Allows the user to refresh the Lab's Egg selection without moving the mouse.
- Makes it easier to refresh many times in a row.
- Simplifies selecting the Reload/Reload Now button.
- With the Dialog Module, simplifies spending Lab Reloaders
