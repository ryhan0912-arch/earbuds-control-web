# Earbuds Control (web)

A single-page web app for controlling soundcore earbuds from a desktop browser, with no app install.

**Tested on a real device:** soundcore R50i NC / P30i (A3959).

**Supported from the OpenSCQ30 protocol definitions (not yet tested in this app on real hardware):**
R60i NC / P31i, Liberty 5, Liberty 4 Pro, Liberty 4, Liberty 4 NC, Liberty 3 Pro, Liberty Air 2 Pro, Liberty 2 Pro+,
P40i, P20i / P25i / R50i, A20i, Life P2 Mini, Life Note 3, Life Note 3S, Life P3, Life Dot 2 NC, Life A2 NC, Life Dot 2S,
Space A40, Sport X20, C30i, C50i, AeroClip, V20i, Sleep A30, Vortex, Space 2, Space One, Space One Pro, Space Q45,
Life Q30, Life Q35, Life Tune, Life Tune Pro, Life 2 Neo, Q20i, Q11i.

What each model gets depends on what the device supports: sound modes (noise cancelling, transparency),
equalizer, touch controls, and toggles such as LDAC, gaming mode, wear detection, auto power off and dual connection.
Liberty 2 Pro and Motion+ show battery and device info only.

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
