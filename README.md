# MXB Damage Plugin

A realistic visual damage plugin for MX Bikes featuring dynamic deformation, breakable parts, scratches, dirt accumulation, and crash effects.

## Install

1. Close MX Bikes.
2. Download **[MXB-Damage-Setup.exe](https://github.com/FroxyMXB/MXB-Damage-Plugin/releases/latest/download/MXB-Damage-Setup.exe)** from the latest release.
3. Run the installer.
4. It finds your MX Bikes installation, downloads the signed release, and installs the plugin into the game's `plugins` folder.

The installer does not modify bikes, physics, ReShade, profiles, or other plugins. Your settings are kept when updating.

If Windows shows an unsigned-app warning, choose **More info → Run anyway**. The installer is not currently code-signed.

## Manual installation

If you prefer not to use the installer, download the versioned ZIP from the latest release and copy these into the `plugins` folder beside `mxbikes.exe`:

```text
mxb_damage.dlo
mxb_damage\
```

For a Steam installation, use **Steam → MX Bikes → Manage → Browse local files → plugins**.

Do not put the plugin in `Documents\PiBoSo\MX Bikes\mods`, and do not delete the game's native plugin files such as `proxy64.dlo`, `proxy_udp64.dlo`, or `xinput64.dli`.

## In-game use

The menu opens with **Q** the first time you go on track. You can move it by dragging its title bar and configure the menu, repair, and clean-bike keys there.

- **Repair Damage** fixes the bike while keeping accumulated dirt.
- **Clean Bike** removes dirt while keeping damage.
- Automatic updates are enabled by default and are installed after MX Bikes closes.

## Troubleshooting

- Make sure MX Bikes is closed before installing.
- Check that `mxb_damage.dlo` is in the game's `plugins` folder, not the Documents folder.
- If the installer selected the wrong copy of MX Bikes, run it again and choose the folder containing the `mxbikes.exe` you actually launch.
- To remove the plugin manually, close MX Bikes and remove `mxb_damage.dlo` and the `mxb_damage` folder from `plugins`.
