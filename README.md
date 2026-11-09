# Carbon Box

A modified version of the **Carbon** theme for Batocera's EmulationStation,
adapted and tested on **ROCKNIX**, which does not ship Carbon and does not
offer it in the theme downloader.

This is a fork of [fabricecaruso/es-theme-carbon](https://github.com/fabricecaruso/es-theme-carbon).
The `carbon-box` branch starts from upstream commit
[`421cec0`](https://github.com/fabricecaruso/es-theme-carbon/commit/421cec038116fe7b6711fa35683470884a28ed55)
(October 2024), the version bundled with Knulli, and adds only the changes
listed below. The `master` branch tracks upstream.

## Changes from upstream Carbon

Two new options under **UI Settings → Theme Configuration**:

| Option | Values | What it does |
|---|---|---|
| **Preview image** | Screenshot (image) / Cover (thumb) | Picks which scraped image is shown in the game preview panel before the video starts. |
| **Preview video delay** | Theme default, 0 s to 5 s in 0.25 s steps | How long the preview waits before the video starts playing. |

Both apply to the Detailed, Grid, Game Carousel, Tiles, Icons, Carousel,
Boxes and Content views. Option labels are translated in every language the
theme supports.

The theme headers now say `es-theme-carbon-box (fork of es-theme-carbon)`.
All original author and license notices are kept as they were.

Tested on an Orange Pi 5 (RK3588) running ROCKNIX.

## Installation

1. Download this repository as a ZIP (**Code → Download ZIP** on the
   `carbon-box` branch) and extract it.
2. Copy the extracted folder to the EmulationStation themes folder on your
   device (on ROCKNIX: `/storage/.config/emulationstation/themes/`).
3. Restart EmulationStation and select the theme under **UI Settings → Theme Set**.

## Credits

- **simple**: Nils Bonenberger
- **Carbon**: Eric Hettervik (Rookervik)
- **es-theme-carbon** for Batocera: Fabrice Caruso
- Languages and missing systems (Batocera v36): maioni
- Upstream contributors: see the [upstream history](https://github.com/fabricecaruso/es-theme-carbon/commits/master)
- Carbon Box changes: Matheus C. Salvalagio

## License

[Creative Commons Attribution-NonCommercial-ShareAlike 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
(CC BY-NC-SA), the same license as the original theme. The full text is in
[`readme.txt`](readme.txt).

You may share and modify this theme as long as you credit the authors above,
indicate your changes, distribute derivatives under the same license, and do
not use it commercially.

System logos and trademarks are the property of their respective owners.
