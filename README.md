# Worms 3D for New Nintendo 3DS

[Download beta-01](https://github.com/EstebanPdN/worms-3d-3ds/releases/tag/beta-01) · [Installation guide](https://estebanpdn.github.io/worms-3d.html#install)

This is my native Worms 3D port for New Nintendo 3DS. Beta-01 is build 51.

This project was developed with the help of [OpenAI Codex](https://openai.com/codex/). Learn more about the development process [here](AI_DEVELOPMENT.md).

## Requirements

- **New Nintendo 3DS, New Nintendo 3DS XL, or New Nintendo 2DS XL**.
- Your own European/PAL *Worms 3D* GameCube disc (`GWMP8P`, revision 0).
- Allow 1 GiB of free space on the SD card for `assets.worms`.

## Installation

1. Open [Forge 3DS Converter 1.2.0](https://github.com/EstebanPdN/estebanpdn.github.io/releases/tag/forge-3ds-converter-v1.2.0), select **Worms 3D**, and choose the ISO dumped from your own disc.
2. When the converter reports **Game data verified**, copy `assets.worms` to `sdmc:/3ds/worms3ds/assets.worms`.
3. For a HOME Menu install, use FBI to install the CIA from the SD card, or go to **Remote Install → Scan QR Code** in FBI and scan the release QR. To use the Homebrew Launcher, put the 3DSX in `sdmc:/3ds/worms3ds/` and launch it there.

[FBI installation QR](https://github.com/EstebanPdN/worms-3d-3ds/releases/download/beta-01/QR-beta-01-github.png)

## Optional local assets

Copy personally prepared mods to `sdmc:/3ds/worms3ds/mods/` as `.worms` packs. You can put compatible local interface art in `sdmc:/3ds/worms3ds/ui/`. The main game runs with `assets.worms` alone. The public beta uses simpler menu art when the optional UI files are absent.

## Verify the download

Compare the SHA-256 of your download with [`SHA256SUMS.txt`](https://github.com/EstebanPdN/worms-3d-3ds/releases/download/beta-01/SHA256SUMS.txt).

## Beta feedback

[Open an issue](https://github.com/EstebanPdN/worms-3d-3ds/issues) with your console model, launcher, build number and the steps to reproduce the issue. For conversion problems, include the disc ID and the converter's error message. With **Developer → Debug buttons** enabled, press and release **SELECT** to save a manual diagnostic report under `sdmc:/3ds/worms3ds/dumps/`. Keep game files, saves and dumps out of public issues.
