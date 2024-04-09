# 🍓 PFQ-Strawberi: The Pokéfarm Q Accessibility Tool

A series of accessibility stylesheets for Pokéfarm Q.
- Feed PKMN, go fishing, accept trades, and more with the click of a single button.
- Give your joints some time to rest by tapping and clicking without moving your wrist.
- Make Strawberi your own through customization options and a modular design.
- *Only compatible with PFQ. QOL script recommended. Tested on Firefox.*

Make farming easier; use Strawberi.

## 🍓 Instructions
1. Access the Site Skins page at https://pokefarm.com/skin.
2. Paste the contents of the release file(s) into the "Extra CSS" section of the Skin Editor.
3. **OR** use the integrated Site Skins by pasting **JPM4/strawberi** or **JPM4/blackberi** into the "Other Skin" path.

## 🍓 Strawberi.css
Contains every Strawberi module in a single package. Recommended to inject as-is.

Individual modules, listed below, can be disabled by removing the labeled CSS.

### 🍓 Core Module
- Required.
- Creates the 🍓 Button(s), allowing the other modules to use them.
- Can be modified to change the style, size, and position of the 🍓 Button.

### 🍓 Extra Module
- Extra functionality for other modules, including what used to be the Dialog Module.
- Allows the user to quickly close "dialog" prompts, same as pressing the Enter key.
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

### 🍓 Wishforge Module
- Allows the user to upgrade and collected badges without moving the mouse.
- Makes it easier to work through a lot of badges at a time.
- Simplifies scrolling up and down to check each badge's progress.
- With the Dialog Module, simplifies approving badge crafting.

### 🍓Shelter Module
- Allows the user to refresh the Shelter and view PKMN summaries without moving the mouse.
- Makes it easier to refresh many times in a row.
- Simplifies selecting "View/Adopt" over and over.
- With the Dialog Module, adopt a PKMN immediately after viewing it.

## Q&A

### Q: How does Strawberi's Field Module compare to [Winterbraid's One Click Fields](https://pfq.link/~Mzx6)?
A: It's a different implementation.
- OCF is developed for Chrome;
- Strawberi is developed for Firefox.
- OCF is lightweight and standalone;
- Strawberi covers most of the site.
- OCF uses precise CSS selectors;
- Strawberi is designed to be scalable.
- OCF can be toggled with the QOL script;
- Strawberi cannot.

Use whichever one works better for you.

### Q: Will there be a Garden Module?
A: No, due to CSS limitations. For a practical solution, see [Neonyan's Easy Garden Watering](https://pfq.link/~V9yD).

### Q: Are you worried about releasing this during the PFQ Recode?
A: Not really. If the HTML changes, Strawberi will be updated accordingly.
