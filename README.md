<h1 align="center">Worms 3DS</h1>

<p align="center">
  <strong>Take your squad into battle.</strong><br>
  Worms 3D, adapted for two screens on New Nintendo 3DS.
</p>

<p align="center">
  <a href="#download-and-installation">Download</a> ·
  <a href="#features">Features</a> ·
  <a href="#screenshots">Screenshots</a> ·
  <a href="#documentation">Documentation</a> ·
  <a href="https://github.com/EstebanPdN/worms-3ds/releases/tag/beta-01">Changelog</a> ·
  <a href="#community-and-bug-reports">Community</a>
</p>

<p align="center">
  <a href="https://github.com/EstebanPdN/worms-3ds/releases/tag/beta-01"><img src="docs/badges/version.svg" alt="Public release: beta-01" height="22"></a>
  <a href="#requirements"><img src="docs/badges/platform.svg" alt="New Nintendo 3DS" height="22"></a>
</p>

<p align="center">
  <img src="docs/images/showcase-rounded.webp" alt="Worms 3DS with a match on the upper screen and the team HUD and radar on the lower screen" width="1200">
</p>

<p align="center">
  <a href="https://estebanpdn.github.io/worms-3d.html"><img src="docs/images/website.svg" alt="Visit Worms 3DS on Esteban’s Forge" width="142" height="46"></a>
  <a href="https://github.com/EstebanPdN/worms-3ds/issues"><img src="docs/images/issues.svg" alt="Report a bug on GitHub Issues" width="166" height="46"></a>
  <a href="https://www.patreon.com/c/EstebanPdN"><img src="docs/images/patreon.svg" alt="Support EstebanPdN on Patreon" width="216" height="46"></a>
</p>

This is my native New Nintendo 3DS port of the GameCube version of *Worms 3D*. I'm still testing matches and performance in the first public beta.

This project was developed with the help of [OpenAI Codex](https://openai.com/codex/). Learn more about the development process [here](AI_DEVELOPMENT.md).

## Features

<table>
  <tr>
    <td width="50%" valign="top"><strong>Start a quick match</strong><br>Take your team into a 3D battlefield on the upper screen.</td>
    <td width="50%" valign="top"><strong>Keep the radar close</strong><br>The lower screen shows team slots, health, the turn timer and the radar during a match.</td>
  </tr>
  <tr>
    <td width="50%" valign="top"><strong>Pick your weapon</strong><br>Open the lower-screen inventory to see what's available for the current turn.</td>
    <td width="50%" valign="top"><strong>Bring your own mods</strong><br>Load compatible local <code>.worms</code> packs from the SD card.</td>
  </tr>
</table>

## Download and installation

<p>
  <a href="https://github.com/EstebanPdN/worms-3ds/releases/download/beta-01/Worms-3D-beta-01.cia"><img src="docs/images/download-cia.svg" alt="Download Worms 3DS CIA" width="210" height="46"></a>
  <a href="https://github.com/EstebanPdN/worms-3ds/releases/download/beta-01/Worms-3D-beta-01.3dsx"><img src="docs/images/download-3dsx.svg" alt="Download Worms 3DS for Homebrew Launcher" width="210" height="46"></a>
</p>

[Beta-01 release notes](https://github.com/EstebanPdN/worms-3ds/releases/tag/beta-01) · [SHA-256 checksums](https://github.com/EstebanPdN/worms-3ds/releases/download/beta-01/SHA256SUMS.txt)

### Requirements

- **New Nintendo 3DS, New Nintendo 3DS XL, or New Nintendo 2DS XL**.
- Your own European/PAL *Worms 3D* GameCube disc (`GWMP8P`, revision 0).
- Allow 1 GiB of free space on the SD card for `assets.worms`.

### Prepare the game data

1. Open [Forge 3DS Converter 1.2.0](https://github.com/EstebanPdN/estebanpdn.github.io/releases/tag/forge-3ds-converter-v1.2.0), select **Worms 3D**, and choose the ISO dumped from your own disc.
2. When the converter reports **Game data verified**, copy `assets.worms` to `sdmc:/3ds/worms3ds/assets.worms`.

### CIA / FBI

Install the CIA from your SD card with FBI, or open **Remote Install → Scan QR Code** and scan:

<a href="https://github.com/EstebanPdN/worms-3ds/releases/download/beta-01/QR-beta-01-github.png"><img src="https://github.com/EstebanPdN/worms-3ds/releases/download/beta-01/QR-beta-01-github.png" width="220" height="220" alt="FBI installation QR code for the beta-01 CIA"></a>

### Homebrew Launcher / 3DSX

Put `Worms-3D-beta-01.3dsx` in `sdmc:/3ds/worms3ds/` alongside `assets.worms`, then launch it from the Homebrew Launcher.

### Optional local assets

Put compatible `.worms` mod packs in `sdmc:/3ds/worms3ds/mods/` and compatible local interface art in `sdmc:/3ds/worms3ds/ui/`. The public beta runs with `assets.worms` alone and uses simpler menu art when the optional UI files are absent.

## Screenshots

<p align="center">
  <img src="docs/images/weapons.webp" width="300" alt="A worm aiming a bazooka above the weapons inventory">
  <img src="docs/images/island.webp" width="300" alt="An overhead view of the island above the match radar and team HUD">
</p>

## Documentation

- [Installation guide](https://estebanpdn.github.io/worms-3d.html#install)
- [Beta-01 changelog](https://github.com/EstebanPdN/worms-3ds/releases/tag/beta-01)
- [AI development notes](AI_DEVELOPMENT.md)

## Community and bug reports

[Open an issue](https://github.com/EstebanPdN/worms-3ds/issues) with your console model, launcher, build number, map, game mode and the steps to reproduce the issue. For conversion problems, include the disc ID and the converter's error message.

With **Developer → Debug buttons** enabled, press and release **SELECT** to save a diagnostic report under `sdmc:/3ds/worms3ds/dumps/`. Keep game files, saves and dumps out of public issues.

## Credits

*Worms 3D* and its artwork belong to Team17 and their respective rights holders. Nintendo 3DS is a trademark of Nintendo. I distribute the port builds separately from the original game data. [New Nintendo 3DS wordmark reference](https://commons.wikimedia.org/wiki/File:New_Nintendo_3DS_logo.svg)
