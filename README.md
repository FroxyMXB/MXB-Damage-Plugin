# MXB Damage Plugin

A realistic visual damage plugin for MX Bikes featuring dynamic deformation, breakable parts, scratches, dirt accumulation, and crash effects.

## Installation

Choose one of the two methods below.

### Option 1 — EXE installer (recommended)

1. Close MX Bikes.
2. Download **[MXB-Damage-Setup.exe](https://github.com/FroxyMXB/MXB-Damage-Plugin/releases/latest/download/MXB-Damage-Setup.exe)** from the latest release.
3. Run the installer.
4. Let it detect MX Bikes, or choose the folder containing `mxbikes.exe`.

The installer downloads and verifies the latest release, then installs:

```text
MX Bikes\plugins\mxb_damage.dlo
MX Bikes\plugins\mxb_damage\
```

It keeps your settings when updating and does not modify bikes, physics, ReShade, profiles, or other plugins.

If Windows shows an unsigned-app warning, choose **More info → Run anyway**. The installer is not currently code-signed.

### Option 2 — Manual ZIP install

Use this if you do not want to run the installer.

1. Close MX Bikes.
2. Download the versioned **`mxb_damage_<version>.zip`** from the latest release.
3. Open the ZIP.
4. Copy both items into the `plugins` folder beside `mxbikes.exe`:

```text
mxb_damage.dlo
mxb_damage\
```

For Steam, open **Steam → MX Bikes → Manage → Browse local files → plugins**.

Manual installs do not receive the installer’s first-install detection, but the plugin can still update itself later when automatic updates are enabled.

## Do not install here

Do not put the plugin in:

```text
Documents\PiBoSo\MX Bikes\mods
```

Do not delete the game's native files such as `proxy64.dlo`, `proxy_udp64.dlo`, or `xinput64.dli`.

## In-game use

The menu opens with **Q** the first time you go on track. You can drag its title bar and configure the menu, repair, and clean-bike keys.

- **Repair Damage** fixes the bike while keeping accumulated dirt.
- **Clean Bike** removes dirt while keeping damage.
- Automatic updates are enabled by default and install after MX Bikes closes.

## Troubleshooting

- Make sure MX Bikes is closed before installing.
- Confirm that `mxb_damage.dlo` is beside `mxbikes.exe` in the game's `plugins` folder.
- If the installer selected the wrong copy, run it again and choose the folder containing the `mxbikes.exe` you actually launch.
- To remove a manual installation, close MX Bikes and remove `mxb_damage.dlo` and the `mxb_damage` folder from `plugins`.
