# Postal 1 3DS

A Nintendo 3DS port of Postal 1 built from the open-source Postal engine.

This repository contains the engine and Nintendo 3DS platform code only. It
does not include Postal 1 game data, music, maps, or other copyrighted assets.
To run the port, use data files from your own legally obtained copy of Postal
1.

## Status

The port can load the original game archives and play the campaign on real
hardware. It is still an alpha project and may have performance limitations or
compatibility issues in some levels.

## Installation

Copy the homebrew files to the following directory on the SD card:

```text
sdmc:/3ds/postal/
  postal1-3ds.3dsx
  postal1-3ds.smdh
  data/
```

Copy the original Postal 1 data files into `sdmc:/3ds/postal/data/`:

```text
res.sak
shell.sak
game.sak
system1.fnt
smash.fnt
POSTAL.INI
```

Some installations also require the original `title` and `res` directories.
Keep their original contents and directory names when copying them from the PC
version.

## Controls

| Input | Action |
| --- | --- |
| Circle Pad | Movement |
| C-Stick | Aim cursor movement |
| Touch Screen trackpad | Aim cursor movement |
| R / ZR | Primary fire |
| L / ZL | Throw grenade or molotov |
| D-Pad Left / Right | Previous / next weapon |
| D-Pad Up / Down | Quick weapon selection |
| A | Confirm menu selection |
| B | Back or cancel |
| X | Execute |
| Y | Suicide |
| START | Pause menu or back |
| SELECT | Open or close the cheat console |

## Bottom Screen HUD

The bottom screen provides a live HUD with:

- Health and armor bars
- Ammo count
- FPS counter
- Nearby-target radar
- Touchpad aiming mode

Press `SELECT` to open the Cheat Console:

- God Mode
- Infinite Ammo
- Next Level

## Building

Requirements:

- devkitPro
- devkitARM
- libctru
- SDL2 with Nintendo 3DS support

Build the ELF and convert it to a 3DSX executable:

```bash
make N3DS=1
3dsxtool bin/postal1-3ds.elf bin/postal1-3ds.3dsx
```

## Legal Notice

Postal 1 game data is not distributed with this project. You are responsible
for supplying files from a legally obtained copy of the game.

## License

The project is distributed under the GPL-2.0 license. See `LICENSE` for the
full license text.
