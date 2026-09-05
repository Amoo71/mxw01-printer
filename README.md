# MXW01 Studio

Modern dark-mode Web Bluetooth app for the **MXW01** mini thermal / cat printer.

**Live demo:** https://amoo71.github.io/mxw01-printer/

## Features

- 📱 Full mobile support (touch drag, responsive)
- 🎨 Dark glassmorphism UI
- 🖼 Multi-image layers
- 🔄 Rotate, scale, flip, opacity, reorder
- ✋ Drag layers on the canvas
- 🎛 Dither filters (Floyd-Steinberg, Atkinson, Bayer, Threshold, Pixelate)
- 💪 Filter strength + pixelate size
- 🌑 Print darkness / intensity control
- ⚡ Direct Web Bluetooth print (no official app needed)

## Usage

1. Open the page in **Chrome, Edge or Opera** (desktop or Android)
2. Turn on your MXW01 printer
3. Tap **Verbinden** and select the device
4. Add images, edit layers, choose a filter
5. Adjust print darkness and hit **Drucken**

## Protocol

Uses the reverse-engineered MXW01 BLE protocol (service `ae30` / characteristics `ae01`–`ae03`).

## License

MIT
