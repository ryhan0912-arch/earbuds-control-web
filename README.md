# Earbuds Control (web)

A single-page web app for controlling **soundcore R50i NC / P30i (model A3959)** earbuds from a desktop browser, with no app install.

**Open it:** https://ryhan0912-arch.github.io/earbuds-control-web/ in Chrome or Edge on Windows, macOS, Linux or ChromeOS.

## Features

- Detects which soundcore device is on and connects to it automatically; shows a picker when several are on, and reconnects when the earbuds come back out of the case

- Battery level and charging status for each earbud
- Sound mode: noise cancelling (adaptive, manual 1–5, scene), transparency, normal; wind noise reduction
- Equalizer: 22 presets and a custom 8-band EQ
- Touch controls for single, double and triple tap and long press on each earbud
- Mode switch cycle, gaming mode, 3D surround, touch tone, low battery prompt, auto power off
- Dual connection on/off and device list
- Serial number and firmware version

## Requirements

- Chrome or Edge 117 or newer on a desktop computer (uses the Web Serial API over Bluetooth RFCOMM)
- Earbuds paired and connected to the computer
- Phones, Firefox and Safari are not supported (no Web Serial over Bluetooth)

## How to use

1. Take the earbuds out of the case and make sure they're connected in your OS Bluetooth settings.
2. First time only: open the page, click **Add device** and pick the entry named **JL_SPP** or the earbuds' name.
3. From then on, just open the page — it finds and connects to your device by itself.

## Credits and license

The Bluetooth protocol details come from the open-source
[OpenSCQ30](https://github.com/Oppzippy/OpenSCQ30) project by Oppzippy, licensed under GPL-3.0.
This project is also released under the **GNU General Public License v3.0**.

## Disclaimer

This is an unofficial, community project. It is **not affiliated with, endorsed by, or supported by Anker Innovations**.
"soundcore" and "Anker" are trademarks of their respective owners and are used here only to describe compatibility.
Use at your own risk; changing device settings is done entirely through the earbuds' standard control commands.
