# Worms 3D for New Nintendo 3DS

[Download beta-01](https://github.com/EstebanPdN/worms-3d-3ds/releases/tag/beta-01) · [Installation guide](https://estebanpdn.github.io/worms-3d.html#install)

This is the public release repository for the Worms 3D port for New Nintendo 3DS, New Nintendo 3DS XL and New Nintendo 2DS XL. Beta-01 is build 50.

## Prepare your SD card

1. Open [Forge 3DS Converter 1.2.0](https://github.com/EstebanPdN/estebanpdn.github.io/releases/tag/forge-3ds-converter-v1.2.0). Select **Worms 3D** and choose an ISO dumped from your European GameCube disc (PAL, disc ID `GWMP8P`, revision 0). Conversion runs on your computer.
2. When the converter reports **Game data verified**, copy `assets.worms` from beside the ISO to `/3ds/worms3ds/assets.worms` on the SD card. Allow 1 GiB of free space for this file.
3. For a HOME Menu install, scan the FBI QR from the release, or install the CIA with FBI. For the Homebrew Launcher, copy the 3DSX into `/3ds/worms3ds/` and launch it there.

Both launchers read the same SD data. The release includes SHA-256 checksums for the downloads.

## Beta feedback

When reporting a problem, include the console model, launcher, build number and the steps that reproduced it. For conversion issues, include the disc ID and the converter's error message. Keep disc images and extracted game files on your own computer.
