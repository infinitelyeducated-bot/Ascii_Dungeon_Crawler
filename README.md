# Ascii Dungeon Crawler

A party-based ASCII dungeon crawler in a single HTML file. No install, no server: double-click and play.

This is the **single-file edition** of [PixelBear's Dungeon Crawler](https://github.com/infinitelyeducated-bot/pixelbear-dungeon-crawler). It is the same game with one difference: everything to do with networking (Host/Join, the Network dialog, network status, multiplayer lobby) is removed, because a single file cannot run the signalling server. Party chat, the dice roller, the in-game guide, saving and every gameplay feature are all still here.

## Play

- Double-click **`Run_Game_Ascii_Dungeon_Crawler.cmd`**, or open `Ascii_Dungeon_Crawler.html` directly in a browser.
- Online: https://infinitelyeducated-bot.github.io/Ascii_Dungeon_Crawler/Ascii_Dungeon_Crawler.html

Press **Esc** in the game for the pause menu, which includes a full **Game Guide** (controls, map key, classes, combat system, bestiary) with a Print button.

## Quick reference

| Key | Action |
|-----|--------|
| W A S D / Arrows | Move (10 spaces per turn) |
| F | Basic attack |
| 1 / 2 / 3 | Class attack / spell / power attack |
| R | Rest |
| G | Guard |
| E | End turn |
| Esc | Pause menu and Game Guide |

Five classes: Fighter, Archer, Rogue, Wizard, Cleric. Up to six party members. Every 5th floor is a boss floor.

## For two or more computers

Use the server edition instead, which adds LAN/WAN multiplayer:
https://github.com/infinitelyeducated-bot/pixelbear-dungeon-crawler

## Building this file

This file is generated from the server edition by `build-single-file.cjs` in that repo. Do not edit `Ascii_Dungeon_Crawler.html` by hand; change the source modules there and rebuild.

## License

MIT
