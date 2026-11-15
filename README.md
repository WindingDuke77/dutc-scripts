# DUTC Script Tags

Every LCD tag, block keyword and toolbar argument for the DUTC Space Engineers scripts on one page:

**https://windingduke77.github.io/dutc-scripts/**

| Script | Steam Workshop |
|---|---|
| Dutc Power Deck | [3789962197](https://steamcommunity.com/sharedfiles/filedetails/?id=3789962197) |
| DUTC Solar Tracker | [3813959643](https://steamcommunity.com/sharedfiles/filedetails/?id=3813959643) |
| DUTC Build & Repair | [3789968698](https://steamcommunity.com/sharedfiles/filedetails/?id=3789968698) |
| DUTC Inventory Manager | [3789969690](https://steamcommunity.com/sharedfiles/filedetails/?id=3789969690) ([source](https://github.com/WindingDuke77/dutc-inventory-manager)) |

## Editing

The whole site is `index.html` (no build step). GitHub Pages serves it from the `main` branch.

The screen previews in `img/` are the scripts' own LCD drawing code rendered with the game's fonts
(`tools\pbcheck\preview.ps1` in the DUTC workspace). When a screen changes, re-render and copy the
PNG over the matching file here, e.g. `power_drain.png` becomes `img/power-drain.png`.
