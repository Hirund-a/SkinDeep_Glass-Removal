# Skin Deep - Glass Shard removal

## Table of Contents

- [About](#about)
- [How to Setup](#how-to-setup)
- [TODO](#todo)

## About

This mod provides file replacements to allow players to overwrite certain player animations for the game Skin Deep. These animations in question are those pertaining to the "Die-Hard"-esque picking of broken glass from the player character's feet.

Since this mod is a file swap, there are no guarantees it will remain persistent between game updates or work with future updates

Made for game version `2025.05.05.2010`

## How to Setup

1. Download the following repository onto your computer, either by navigating to `<> Code` and then using `Download ZIP` or by cloning the repository

    (Extract the zip file if you downloaded as ZIP)

2. Locate your local game files of "Skin Deep":
    - On Steam, right click the game in your library, then navigate to `Manage > Browse Local Files`.
    - On EGS, right click the game in your library, click `Manage`, then under `Installation` click the `Open Install Location` icon.

    Once in your game's folder, keep the window handy to make the next steps easier.

3. The repository/files you downloaded contains 3 folder/directories:

    - `original` : contains the games original files as a backup
    - `modded - no shards` : overites glass removal animations with idle animations and removes glass shards from spawning during the animations
    - `modded - shards` : overites glass removal animations with idle animations but keeps glass shards spawning as they are being "removed"

    Inside each folder is another folder called `base`.

    Copy this folder.

4. Paste the folder inside your game's folder. You will likely get a prompt to confirm overwriting 3 files, select ok.

If you have the game running while performing these steps, you will not see any visible changes. Either close the game before hand or exit and relaunch the game.

## TODO

These are potential ways this mod can go. Do not treat any of these as promises by the repo authors/contributors of future features, these are just notes to self.

- Same thing but with shrapnel in torso?
- Same thing but with lodged bullets in torso?
- Same thing but with glass while crawling?