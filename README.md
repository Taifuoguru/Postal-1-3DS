
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

<img width="822" height="461" alt="Ekran görüntüsü 2026-09-17 232445" src="https://github.com/user-attachments/assets/0c3188f7-33bc-42bd-9d20-2ef9eea75577" />

<img width="815" height="384" alt="Ekran görüntüsü 2026-09-17 232505" src="https://github.com/user-attachments/assets/c34f1430-143d-4b14-bb5f-282dda6163c6" />

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

<img width="2000" height="1500" alt="WhatsApp Image 2026-09-17 at 2fwdsq3 41 12" src="https://github.com/user-attachments/assets/c4277a6f-d9c8-4f17-88ec-615db2060a57" />
<img width="2000" height="1500" alt="WhatsApp Image 2026-09-17 at 23 41 143342" src="https://github.com/user-attachments/assets/d30a0014-794d-4dd9-8a3f-c5da8d383f5f" />
<img width="2000" height="1500" alt="WhatsApp Image 2026-09-17 at 23 41 12" src="https://github.com/user-attachments/assets/9e164d8e-5ff0-4598-b2cd-0315b260a102" />


## Legal Notice

Postal 1 game data is not distributed with this project. You are responsible
for supplying files from a legally obtained copy of the game.

## License

The project is distributed under the GPL-2.0 license. See `LICENSE` for the
full license text.



Hi everyone! This is a completely new port compared to the old one—please read the updated instructions. If you get a black screen on startup, press Start to continue. I suspect it should work on Old 3DS models, but I don't have one to test it on. Please report any bugs if you find them!
