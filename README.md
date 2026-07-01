<div align="center">
  <img src="assets/icons/GridDash_Icon_Full.png" alt="Grid Dash logo" width="120">
  <h1>Grid Dash</h1>
  <p><strong>A modern, modular SimHub dashboard for racing displays, phones, tablets, and full-screen pit walls.</strong></p>
  <p>
    <a href="https://griddashhub.com/">Website</a> ·
    <a href="https://cdn.shopify.com/s/files/1/0692/0614/7120/files/GridDashSetup.exe?v=1782926842">Download for Windows</a> ·
    <a href="https://github.com/mikedmor/simhub-griddash/releases">Releases</a> ·
    <a href="https://github.com/mikedmor/simhub-griddash/issues">Report an issue</a>
  </p>
</div>

![Grid Dash running as a SimHub racing dashboard](assets/featured_image.png)

Grid Dash transforms live SimHub telemetry into polished, flexible dashboards that are easy to read
at speed. Run a compact driver display, turn a phone or tablet into a dedicated dash, or open a
full-screen Pit Wall for timing, strategy, and race awareness.

## Why Grid Dash?

- **Ready to race** — start with polished layouts instead of an empty canvas.
- **Built around your games** — profiles automatically select the right layout, theme, units, and
  display mode when the active game changes.
- **Designed for every screen** — use a wheel display, desktop browser, second monitor, phone, or
  tablet.
- **Easy to personalize** — arrange modules visually, create reusable components, and tune complete
  color themes from inside SimHub.
- **Local-first** — live telemetry and dashboard rendering stay on your PC and local network.
- **Made for SimHub** — Grid Dash works alongside the telemetry tools and hardware integrations you
  already use.

## Make it yours

Grid Dash includes reusable layouts, configurable components, dashboard themes, animated idle
screens, and per-game assignments. Customize one design and reuse it across the cars, games, and
screens that suit your setup.

<table>
  <tr>
    <td width="50%">
      <img src="assets/Shopify%20Images/SimHubCustomizeLayouts.png" alt="Grid Dash layout management in SimHub">
      <br><strong>Reusable layouts</strong><br>
      Assign dashboard designs by game, select units and themes, and preview changes before driving.
    </td>
    <td width="50%">
      <img src="assets/Shopify%20Images/SimHubCustomizeThemes.png" alt="Grid Dash theme editor in SimHub">
      <br><strong>Complete themes</strong><br>
      Tune dashboard colors and visual states with a live preview inside SimHub.
    </td>
  </tr>
  <tr>
    <td width="50%">
      <img src="assets/Shopify%20Images/SimHubCreateComponent.png" alt="Grid Dash component designer">
      <br><strong>Component Designer</strong><br>
      Build reusable telemetry components from configurable layers with an immediate visual preview.
    </td>
    <td width="50%">
      <img src="assets/Shopify%20Images/SimHubCustomizeIdleScreen.png" alt="Grid Dash idle screen customization">
      <br><strong>Personalized idle screens</strong><br>
      Create a finished waiting screen with colors, driver details, clocks, and animated effects.
    </td>
  </tr>
</table>

## Features

- Driver dashboards with shift lights, gear, speed, RPM, lap timing, delta, fuel, tyres, pedals,
  standings, radar, track maps, weather, damage, flags, and more
- Drag-and-drop visual layout editor with resizing and collision-aware grid placement
- Custom component designer with reusable, configurable layers
- Per-game profiles for layouts, themes, units, and display behavior
- Full-screen Pit Wall views for standings, circuit position, timing, and telemetry
- Responsive phone and tablet layouts
- Custom themes, night-friendly displays, accessibility options, and animated idle screens
- Touch controls and SimHub hardware-action support
- Circuit learning and persistent track maps where telemetry permits
- Server discovery and QR-assisted mobile connection

Exact data availability varies by game and by the telemetry exposed through SimHub. Grid Dash hides
or gracefully adapts modules when a value is unavailable.

## Requirements

- A Windows PC running [SimHub](https://www.simhubdash.com/)
- A supported racing or driving title configured in SimHub
- A modern browser for dashboard displays
- Local network access for phones, tablets, and other computers

## Install Grid Dash

1. Install and configure [SimHub](https://www.simhubdash.com/).
2. [Download the Grid Dash installer](https://cdn.shopify.com/s/files/1/0692/0614/7120/files/GridDashSetup.exe?v=1782926842).
3. Close SimHub before running the installer so its plugin files can be updated safely.
4. Restart SimHub and enable **Grid Dash** when prompted.
5. Select **Grid Dash** from SimHub's left menu to configure your server, layouts, themes, and
   license.

The lightweight installer downloads and verifies the current Grid Dash release. Future updates can
be checked from within Grid Dash.

## Connect a display

Grid Dash serves dashboards from your gaming PC:

| Display | Address |
| --- | --- |
| Gaming PC | `http://localhost:8920/` |
| Phone, tablet, or another computer | `http://<server-pc-ip>:8920/` |
| Pit Wall | `http://localhost:8920/?mode=pitwall` |

The Grid Dash page inside SimHub shows the correct address for your network and provides a QR code
for fast mobile connections. The default port can be changed in settings.

## Android companion

The Grid Dash Android companion turns a spare phone or tablet into a focused racing display. It can
discover available rigs on your local network, remember previously connected servers, open QR/deep
links, lock the connected dashboard to landscape, maintain screen brightness, and support kiosk-style
use.

Visit [griddashhub.com](https://griddashhub.com/) for Android availability and installation details.

## Licensing

Grid Dash can be installed and evaluated in a limited free mode. A paid license unlocks the complete
feature set, with one-year, five-year, and lifetime update options available from the
[Grid Dash store](https://griddashhub.com/products/simhub-grid-dashboard).

- One active Windows device per license
- Up to three activations or device transfers per rolling year
- Activate inside Grid Dash using your purchase email and order number
- Deactivate the current PC before moving the license whenever possible
- Versions released during a paid update term remain entitled after that term ends

The public installer and GitHub release files never contain customer credentials or license keys.

## Supported titles

Grid Dash includes profiles and telemetry fallbacks for a growing range of games, including:

- Assetto Corsa and Assetto Corsa Competizione
- Automobilista 2
- iRacing
- Le Mans Ultimate
- RaceRoom Racing Experience
- Forza Horizon 5 and 6
- BeamNG.drive
- EA Sports WRC and other rally titles
- American Truck Simulator and Euro Truck Simulator 2

## Releases

This repository is used to publish Grid Dash release files and release notes. It does not contain the
Grid Dash source code.

Most users should install Grid Dash through the
[official Windows installer](https://cdn.shopify.com/s/files/1/0692/0614/7120/files/GridDashSetup.exe?v=1782926842)
and allow its signed update process to select and verify the correct package. Files on the
[Releases page](https://github.com/mikedmor/simhub-griddash/releases) are also consumed by the
installer and in-app updater.

## Support and feedback

For reproducible bugs or release-package problems, open a
[GitHub issue](https://github.com/mikedmor/simhub-griddash/issues) and include:

- Grid Dash and SimHub versions
- Game and car
- Display, browser, or Android device
- Steps to reproduce
- Relevant SimHub log excerpts

For purchase, billing, refund, or private activation help, use the contact options at
[griddashhub.com](https://griddashhub.com/). Do not post order numbers, purchase email addresses,
activation tokens, license files, or other private account information in a public issue.

## Disclaimer

Grid Dash is an independent SimHub add-on. It is not affiliated with SimHub or with any racing game
developer or publisher. All product names and trademarks belong to their respective owners.
