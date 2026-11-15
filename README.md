# MXB Damage

Realistic visual crash damage for MX Bikes: bending parts, parts that break off, scratches, dirt and mud, seat tears and crash effects.

## Installation

Choose one of the two methods below.

### Option 1 — EXE installer (recommended)
1. Close MX Bikes.
2. Download **[MXB-Damage-Setup.exe](https://github.com/FroxyMXB/MXB-Damage-Plugin/releases/latest/download/MXB-Damage-Setup.exe)** from the latest release.
3. Run the installer.
4. Let it detect MX Bikes, or choose the folder containing `mxbikes.exe`.

The installer downloads and verifies the latest release from GitHub, then installs:

- `MX Bikes\plugins\mxb_damage.dlo`
- `MX Bikes\plugins\mxb_damage\`

It keeps your settings when updating and does not modify bikes, physics, ReShade, profiles, or other plugins.

If Windows shows an unsigned-app warning, choose **More info → Run anyway**. The installer is not currently code-signed.

### Option 2 — Manual ZIP install
Use this if you do not want to run the installer.

1. Close MX Bikes.
2. Download the versioned `mxb_damage_<version>.zip` from the latest release.
3. Open the ZIP.
4. Copy both items into the `plugins` folder beside `mxbikes.exe`:
   - `mxb_damage.dlo`
   - `mxb_damage\`

For Steam, open **Steam → MX Bikes → Manage → Browse local files → plugins**.

Manual installs can still update themselves later when automatic updates are enabled.

## In-game use

The menu opens by itself the first time you go on track; after that press **Q** (you can change the key). Drag its title bar to move it and the corner grip to resize it.

- **Main page:** Repair Damage (fixes the bike, keeps the dirt), Clean Bike (removes dirt, keeps the damage), the Damage and Dirt switches, and the Damage / Dirt Multipliers (0.5x - 2.0x).
- **Parts page:** choose which parts may come off.
- **Settings page:** Keep Damage in Pits, Performance Mode, Bike Snow (needs MXB Whiteout), menu key and automatic updates.

Automatic updates are on by default and install after MX Bikes closes.

## Troubleshooting
- Make sure MX Bikes is closed before installing.
- Confirm that `mxb_damage.dlo` is beside `mxbikes.exe` in the game's `plugins` folder.
- If the installer selected the wrong copy, run it again and choose the folder containing the `mxbikes.exe` you actually launch.
- To remove a manual installation, close MX Bikes and remove `mxb_damage.dlo` and the `mxb_damage` folder from `plugins`.
