# Platinum-Battle-Zone-Challenge
A ROMHack of Pokémon Platinum, designed for use with the [Archipelago Manual](https://github.com/ManualForArchipelago) Project.

![Heatran from the Platinum Battle Zone Challenge title screen, with the hack's logo above it. The logo reads "Pokémon Platinum Battle Zone Challenge"](https://github.com/Linneus/Platinum-Battle-Zone-Challenge/blob/main/Heatran_PlatinumBZC_Screen.png?raw=true)

# Archipelago Setup

Everything that follows is a guide written for those already familiar with both Archipelago and the Manual Project. If you are starting from no knowledge on either of those, start with [this guide](https://github.com/Linneus/PlatinumAPManual/blob/main/Full%20Archipelago%20Setup%20Guide.md) originally written for the [Platinum AP Manual](https://github.com/Linneus/PlatinumAPManual).

If you already have an Archipelago install, and are at least moderately familiar with the Manual project, continue on.

## Patching and Randomizing Your ROM

Included with your download is two xdelta patches and the xdelta program.
Open xdeltaUI.exe, and then choose whether you’d like to play in the original 30FPS, or with the patched 60FPS game, then open the corresponding .xdelta file as your Patch, your Pokémon Platinum ROM (which must be a clean Rev 1, also known as 1.1, which is the most common variant of the game) as your Source File, and then you’ll select a spot to save your modified ROM in Output File. Be sure to add “.nds” to the name of the file. If you don’t do this, you’ll have to add the file extension after the fact.

![An image of the xDelta UI](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcUjFKWcgVj2IERUmCoOjX-qn6nkTZgdOtJHUErtlpq2kZnp7Cnbx8SFlgkIT-wMIyirVOrTd_uVRcvW_DBI8aq70EgA9Z0KdQFNB7b9RwEH32Az2kS1IoSK0kww2mYw_VQ0rO24pj4s7-Z0yZhaVXJQlDG?key=QmhoNGvKP18WJBxH2sPV0g)

## 30FPS vs. 60FPS

The normal patch will leave the game unchanged compared to its original DS release. However, the 60FPS patch will speed up many sections and aspects of the game, most noticeable in making all battle animations much snappier. This is slightly more taxing on one’s computer, and certain areas struggle to maintain a constant framerate with this patch. The Super Rod, which requires very precise timing in 30FPS, becomes nearly unreactable in 60FPS as well. These issues are less pressing in the Battle Zone Challenge compared to the base game's randomizer.

## Downloading and Using the Randomizer

Next, a modified version of [Universal Pokémon Randomizer ZX](https://github.com/Ajarmar/universal-pokemon-randomizer-zx) is included with the download. Open the program with the launcher file. In the top right, click “Open ROM” and open your modified ROM.

![an image of the Universal Pokémon Randomizer ZX UI, showing "Support: Unofficial ROM"](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdYFKFQfgvMwvGgbo9k2qvpq6Ml5RRJI_WBcPipHJXbDgRhXartMlt5mWmQjCgu-6AC6C-MH0wXmEHlskqAokVm5DnlO_QvJzXHupBhlvOdMHJKK2Sr8epyUdAkXsyxyPgpylwrT9rH-bK2ff2uAjr1abE?key=QmhoNGvKP18WJBxH2sPV0g)

Given that you just opened a modified ROM, you can expect to see the red text and the “Unofficial ROM” support.

Importantly, this is where the Battle Zone Challenge differs quite a bit from the original Platinum AP Manual.
There are certain randomization options that the hack is designed around for the sake of the playthrough and its difficulty, and thus a random settings file, named `battlezone_archi_Setings.rnqs` is included with the download. Load it with the "Load Settings" button.
Many settings in this file are a recommendation/baseline.
Those required/absolutely expected settings are:

### Foe Pokémon
•No Double Battle Mode - Turning this on will cause a 1v2 battle in the Battle Hall, and will increase the difficulty, but is not entirely game breaking.

### Wild Pokémon
•Random, Catch 'em All Mode - Having a random set of Pokémon to work with each run is an intended experience.

•Randomize Held Items - Having a small, random toolset with which to get through the game's required battles is an integral aspect to this hack, and finding extra random items on Pokémon can be very helpful. 

•0 Percentage Level Modifier - All of the Wild Pokémon's levels are balanced for the flow of a playthrough.

### TM/HMs & Tutors
•Random TM/HM Moves - There are only 5 TMs in the random item pool, and very few elsewhere in the game, compared to the 92 in the base game. Getting a random set of TMs each playthrough is one of the core sets of tools that the player is expected to use.

•Keep Field Move TMs - Without this setting, you will lose access to Flash, which is required for use in this hack.

•Random Move Tutors - All Move Tutors are present in this hack, and Shards are in the item pool, meaning that random tutor moves are also expected.

•Full HM Compatibility - This, along with full TM compatibility, can alleviate the potential for softlocks as the player looks for Pokémon to use the required moves.

### Items
•Random Field Items - This is the primary way that players will receive useful items; picking up random items from item balls and berry trees will provide the player a unique toolset each run. Without this setting, the player's toolset will be very limited.

•Random Special Shops - The Battle Zone has been given a variety of special shops, specifically for the player to have access to more random items. Guaranteeing Evolution Items will also expand the range of potential Pokémon that can be used, as the odds of acquiring their items goes up.

### Misc. Tweaks
•Nothing in this category is expected to be set a certain way; however, the player will start the game with the National Dex and the Running Shoes, so the "Give National Dex at Start" and "Run Without Running Shoes" options are not necessary. Similarly, the Distortion World will not be explored.


**Every setting not mentioned in this list is entirely up to the player's preference, and can make the game easier or harder (or even longer/shorter) depending on the choices.**

## Saving your ROM

When you’re done, hit “Randomize (Save)” in the top right to name/save your newly randomized ROM somewhere. You may also consider using the “Save Settings” option to revisit your options easily in the future.
After saving, I would also recommend using the "Produce File" button to easily reproduce your ROM with the exact randomization in case of any issue that may require a new ROM or patch.

## Cheats (Trainer Sight and Experience Multiplier)

If you are a returning player from the Platinum AP Manual, you may be expecting cheats to apply to your ROM. The Battle Zone Challenge game does not have Trainer Sight, and all experience gains will be ~3.5x the expected value from the original game. These are what the hack was balanced around, and spending time to raise your Pokémon's levels is expected to be done at your own pace during the playthrough.

# Using the Manual

## Opening the Launcher

All releases will have a link to the Archipelago Manual APWorld and Universal Tracker. If you have those downloaded and in your custom worlds folder, begin by making sure that the YAML you used for generation is currently in the Players folder. Then, navigate to your Archipelago install, open ArchipelagoLauncher.exe, and then from that, open the Manual Client on the right side. Select the name of the Manual in the dropdown list (Manual_PlatinumBattleZone_Linneus), your room's code and, when prompted, your slot name.

## Using the PopTracker

There is a PopTracker pack for tracking and playing the randomizer. Download [PopTracker](https://github.com/black-sliver/PopTracker/releases/tag/v0.32.1) and the [Platinum BZC PopTracker Pack](https://github.com/Linneus/Platinum-Battle-Zone-Poptracker/releases). Place the .zip file in the "packs" folder of your PopTracker install, and open PopTracker. Clicking on the AP button in the top left will allow you to connect your PopTracker to your Archipelago room and send and receive checks through PopTracker.

## Sending and receiving Locations and Items

Sending checks can be done with either the Manual Client or the [Platinum BZC PopTracker Pack](https://github.com/Linneus/Platinum-Battle-Zone-Poptracker/releases). Click on the corresponding buttons in either client to send those locations.

![The Archipelago Launcher, with the Manual Client highlighted.](https://i.imgur.com/yUZD5xL.png)
![The Manual Client with Platinum Battle Zone loaded.](https://i.imgur.com/WLOhV5M.png)
![The Platinum Battle Zone Challenge PopTracker Pack.](https://i.imgur.com/k4dyRON.png)

Located in the basements of all 3 Pokémon Centers is the AP Items Room. Cross-reference with the left side of the Manual Client and pick up items there throughout your playthrough.

![The Pokémon Center escalator](https://i.imgur.com/ImypB2d.png)
![The AP Items Room](https://i.imgur.com/6vXhlxB.png)

If the player is only in need of a Progression Item needed to proceed in the game, press the R Button to bring up the AP PDA menu, and select an item at virtually any time.

![A menu with options for Key Items, HMs, Badges, Pokétch, and Points is on the screen on Route 229. A text box reads "Hello! AP Items Room here. What category are you looking into?"](https://i.imgur.com/0M2ZyDo.png)
