# 🍓 PFQ-Strawberi: The Pokéfarm Q Accessibility Tool

A series of accessibility stylesheets for Pokéfarm Q.
- Feed PKMN, go fishing, accept trades, and more with the click of a single button.
- Give your joints some time to rest by tapping and clicking without moving your wrist.
- Make Strawberi your own by tweaking its modular design.
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
- Required. Creates the 🍓 Button(s), allowing the other modules to use them.
- Can be modified to change the style, size, and position of the 🍓 Button.

### 🍓 Lab Module
- Allows the user to refresh the Lab's Egg selection without moving the mouse.
- Makes it easier to refresh many times in a row.
- Simplifies selecting the Reload/Reload Now button.

### 🍓 Party Module
- Allows the user to navigate the Party and Scour screen without moving the mouse.
- Makes it easier to quickly click/"clickback" other users' profiles.
- Simplifies Egg holding, party feeding, showcase feeding, profile switching, and Scour retrieving.
- Works on multiparties, public parties, and private parties.

### 🍓 Field Module
- Allows the user to navigate the Fields screen without moving the mouse.
- Makes it easier to "mass click" other users' fields.
- Simplifies berry selecting, PKMN feeding, and field switching.
- The last 🍓 Button of the last Field redirects to the clickback page (/user/~clickback).

### 🍓 Shelter Module
- Allows the user to refresh the Shelter and view PKMN summaries without moving the mouse.
- Makes it easier to check the Shelter for new Eggs or PKMN.
- Simplifies selecting "View/Adopt" over and over.

### 🍓 Garden Module
- Allows the user to plant and water berries without moving the mouse.
- Makes it easier to navigate the Garden interface without scrolling.
- Simplifies planting the first berry, re-planting it, and watering the Garden.

### 🍓 Wish Module
- Allows the user to upgrade and collected badges without moving the mouse.
- Makes it easier to work through a lot of badges at a time.
- Simplifies scrolling up and down to check each badge's progress.

### 🍓 Fish Module
- Allows the user to navigate the Fishing Area without moving the mouse.
- Makes it easier to go fishing for a long time.
- Simplifies fishing spots, reeling the line, and the entire catching system.

### 🍓 Trade Module
- Allows the user to accept trades without moving the mouse.
- Makes it easier to accept many trades in a row.
- Simplifies selecting the "view trade" link and accepting the trade.

### 🍓 Boxes Module
- Allows the user to open Treasure Boxes without moving the mouse.
- Makes it easier to open many Treasure Boxes at a time.
- Does not affect BoxBoxes, BoxBoxBoxes, Gragon's Hoards, or Gragon's Gifts (for convenience).

### 🍓 Extra Module
- Extra functionality for other modules, including what used to be the Dialog Module.
- Notification Module: Easily click on notification links.
- Dialog Module: Easily close dialog prompts, like pressing Enter.
- Daycare Module: Easily adopt the first or last Egg in your Daycare list.
- Evolve Module: With the QOL script, easily evolve PKMN on the Farm News page.
- Training Module: Easily collect training bags from your PKMN.

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

### Q: Are you worried about releasing this during the PFQ Recode?
A: Not really. If the HTML changes, Strawberi will be updated accordingly.
