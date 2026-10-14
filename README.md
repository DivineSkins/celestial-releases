# Celestial Launcher

Celestial is a desktop mod manager for League of Legends custom skins on **Windows and macOS**, built by [Divine Skins](https://divineskins.gg). Browse, download, organize and apply skins from one library.

[![Latest Release](https://img.shields.io/github/v/release/DivineSkins/celestial-releases?style=for-the-badge)](https://github.com/DivineSkins/celestial-releases/releases)
[![Windows](https://img.shields.io/badge/Windows-10%2B_x64-0078D4?style=for-the-badge)](#downloads)
[![macOS](https://img.shields.io/badge/macOS-Apple_Silicon-000000?style=for-the-badge&logo=apple)](#downloads)
[![Website](https://img.shields.io/badge/Website-divineskins.gg-783cb5?style=for-the-badge)](https://divineskins.gg)

This repository hosts official installers, release notes and automatic-update files.

## Downloads

**[Download Celestial](https://divineskins.gg/install-mods)** or browse the [GitHub releases](https://github.com/DivineSkins/celestial-releases/releases).

| Platform | Requirements                     | Installer                           |
| -------- | -------------------------------- | ----------------------------------- |
| Windows  | Windows 10 or 11, 64-bit         | `Celestial_<version>_x64-setup.exe` |
| macOS    | macOS 12 or later, Apple Silicon | `Celestial_<version>_arm64.dmg`     |

A compatible League of Legends installation is required to apply skins. The current Mac download is for Apple Silicon; an Intel Mac build is not available.

Windows and macOS releases can have different version numbers. The newest GitHub release may contain an installer for only one platform. The download page offers the latest available installer for each platform.

## Features

- Browse Divine Skins and install skins from the website or the in-app store.
- Import skin packages, organize folders and favorites, and save profiles.
- Choose the variants and layers included in a skin package.
- Apply champion and map mods, including supported LeagueToolkit game-data edits.
- Use Quick Fix, full repair, batch repair and backup restore for supported skin issues.
- Enable optional import fixes for textures, ability effects, voiceovers, gear and health bars, plus mod optimization.
- Check skins against your installed game files and update supported older asset formats.
- Receive automatic app updates. Mac installers are signed by Divine Studio LLC and notarized by Apple.

### macOS player edition

Mac supports the player workflow: browsing, downloads, package imports, library management, profiles, packaged variants, repairs and manual skin application.

Creator Hub, raw WAD and loose-folder imports, generated mods such as NoSkin and SkinLite, champion-select overlays, and game-control hotkeys remain Windows-only. Settings → **Mac vs Windows** shows the differences for the version you have installed.

### Supported mod formats

| Format     | Description                                                                                      |
| ---------- | ------------------------------------------------------------------------------------------------ |
| `.modpkg`  | LeagueToolkit packages with metadata, thumbnails, layers and supported game-data edits.          |
| `.fantome` | Fantome skin packages. Supported older asset formats are updated during preparation.             |
| `.zip`     | Mod archives containing the supported package structure. An arbitrary ZIP is not a skin package. |

Compatibility depends on the individual mod and the current League patch. Some skins still need an update from their creator.

## Installation

### Windows

1. Download the Windows `.exe` installer.
2. Run it and open **Celestial**.
3. Follow setup and select your League installation.

### macOS

1. Download and open the Apple Silicon `.dmg`.
2. Drag **Celestial.app** into **Applications**, then eject the disk image.
3. Open Celestial from Applications and select your League installation during setup.
4. When applying skins, approve Celestial's helper if macOS prompts you.

Run the app from Applications so it can install automatic updates. If you are upgrading from Mac version 2.1.0 or earlier, install the current DMG once to get automatic updates.

## Using skins

1. Browse [Divine Skins](https://divineskins.gg/explore-mods), use the in-app store, or import a supported package.
2. Enable the skins you want and choose any packaged variants in your library.
3. Start the patcher or select **Apply skins** on Mac before entering a new game. The League client can already be open.
4. Launch your game normally.

On Mac, selection changes and Stop affect future games. A game already running keeps its prepared skins.

For a skin with issues, right-click it to access repair tools. Automatic import fixes are optional and can be enabled in **Settings → Import**.

## Support

- **[Discord](https://discord.com/invite/divineskins):** bug reports, troubleshooting and feature requests.
- **[Website](https://divineskins.gg)**
- **Email:** support@divineskins.gg

When reporting a problem, include your operating system, Celestial version, League patch, the affected skin and any error message.

## Disclaimer

Celestial is intended for client-side cosmetic customization. Use it at your own risk. Celestial and Divine Skins are not endorsed by, sponsored by or affiliated with Riot Games.

Game updates can affect skin compatibility. Signing and notarization verify the Mac application's distribution; they do not guarantee compatibility with every skin or game update.
