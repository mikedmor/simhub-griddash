# Grid Dash

**A modern, modular SimHub dashboard for racing displays, phones, tablets, and full-screen pit walls.**

Grid Dash turns live SimHub telemetry into flexible dashboards that are easy to read at speed and simple to adapt to different cars, games, and screens. Use it as a compact driver HUD, a dedicated phone or tablet display, or a multi-screen Pit Wall for timing, strategy, and race awareness.

## Highlights

- **Modular dashboards** — build layouts from shift lights, gear, speed, tachometer, lap timing, fuel, tyres, pedals, standings, radar, track maps, weather, damage, and more.
- **Visual layout editor** — drag, resize, add, remove, and configure widgets directly in the browser with collision-aware grid placement.
- **Per-game profiles** — automatically switch layouts, themes, units, and display modes when the active game changes.
- **Pit Wall mode** — switch between leaderboard, track map, and telemetry-focused screens on a second monitor.
- **Phone and tablet layouts** — use any modern browser on your local network, with an Android kiosk companion available for dedicated display devices.
- **Themes and accessibility** — customize colors, brightness, corner radius, night modes, high-contrast gear, larger text, and flag labels.
- **Interactive controls** — cycle multifunction widget slots from the touchscreen or bind them to SimHub hardware actions.
- **Persistent track maps** — learn and save circuit outlines from telemetry where supported.
- **Local-first operation** — telemetry rendering and dashboard configuration stay on your devices and local network.

## Requirements

- Windows PC running [SimHub](https://www.simhubdash.com/)
- SimHub configured for a supported racing or driving title
- A modern browser for dashboard displays
- Local network access when using a phone, tablet, or another computer

Telemetry varies between games. Widgets gracefully hide or fall back when a title does not provide a particular value.

## Installation

1. Install and configure SimHub.
2. Download the newest Grid Dash installer from [Releases](https://github.com/mikedmor/simhub-griddash/releases).
3. Close SimHub before running the installer so its plugin files are not locked.
4. Restart SimHub and enable **Grid Dash** when prompted.
5. Open **Grid Dash** from SimHub's left menu to configure the server, profiles, themes, layouts, and license.

> Release packages will appear on the Releases page as public builds become available.

## Connecting a Display

Grid Dash serves dashboards directly from the gaming PC:

- **This PC:** `http://localhost:8920/`
- **Phone, tablet, or another computer:** `http://<server-pc-ip>:8920/`
- **Pit Wall:** `http://localhost:8920/?mode=pitwall`

The SimHub settings page shows the correct URLs for your network and provides a QR code for quickly opening Grid Dash on a mobile device. The default port can be changed in settings.

## Dashboard Modes

### Driver Dash

A compact, highly readable race display for shift lights, gear, speed, delta, lap timing, fuel, tyres, inputs, flags, and nearby traffic.

### Pit Wall

A second-screen race view with switchable leaderboard, map, and telemetry pages for broader timing and strategy information.

### Mobile

Responsive phone and tablet layouts designed for touch interaction and dedicated dash mounting.

## Customization

Grid Dash includes named dashboard presets, per-game profiles, configurable themes, and typed options for individual widgets. The editor can save an override for the active game without changing the original preset, making it easy to experiment or maintain different layouts for different titles.

## Licensing and Updates

Grid Dash is designed to be installable in a limited free mode, with licensed versions unlocking the complete feature set. License options provide lifetime, one-year, or five-year update eligibility.

Licenses support one active device at a time and up to three activation or transfer events per rolling year. Activating on another PC transfers the license; deactivating the current PC releases it for reuse. Versions published during a paid update term remain entitled after that term ends, while newer releases require renewal or run in limited mode.

Public release downloads are not license keys and contain no customer credentials. Activation is handled inside Grid Dash using the purchase email and order number.

## Supported Titles

Grid Dash includes profiles and graceful telemetry fallbacks for a growing range of titles, including:

- Assetto Corsa and Assetto Corsa Competizione
- Automobilista 2
- iRacing
- Le Mans Ultimate
- RaceRoom Racing Experience
- Forza Horizon 5 and 6
- BeamNG.drive
- EA Sports WRC and other rally titles
- American Truck Simulator and Euro Truck Simulator 2

Exact widget availability depends on the telemetry exposed by SimHub and each game.

## Support and Feedback

Use [GitHub Issues](https://github.com/mikedmor/simhub-griddash/issues) for reproducible bugs and release-package problems. Please include:

- Grid Dash version
- SimHub version
- Game and car
- Display/browser or Android device
- Steps to reproduce
- Relevant SimHub log excerpts

Do not post order details, activation tokens, license files, or other private account information in a public issue.

## Status

Grid Dash is under active development. Features, supported telemetry, installers, and licensing behavior may evolve before the first public production release.

## Disclaimer

Grid Dash is an independent SimHub add-on and is not affiliated with SimHub or any racing game developer or publisher.
