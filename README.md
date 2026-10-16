# PS5 x Xbox Hybrid - Decky CSS Loader theme

System-wide console-style theme for the Steam Deck (Gaming Mode).
PS5 motion (spotlight dimming, soft zoom, white focus ring) + Xbox geometry and green accents.

## Install
1. Copy this whole folder (`PS5-Xbox-Hybrid`) to `/home/deck/homebrew/themes/`
   (Desktop Mode file manager, or `scp -r`).
2. Gaming Mode -> `...` Quick Access -> Decky -> CSS Loader -> scroll to bottom -> Refresh.
3. Enable "PS5 x Xbox Hybrid" and open its options.

Requires a current Steam client (uses `color-mix()`, `:has()`, `:is()` and the CSS `scale` property).

## Options (QAM -> CSS Loader -> this theme)
| # | Option | What it does |
|---|--------|--------------|
| 1 | Style | Hybrid / PS5 / Xbox base look. Every other option defaults to "Style Default" and follows this. |
| 2 | Accent Color | 10 presets + Custom (two color pickers) |
| 3 | Background | PS5 Deep Blue, Xbox Charcoal, Aurora, Graphite, OLED Black, Custom Color, Custom Image |
| 4 | Wallpaper Darkness | Overlay strength for Custom Image |
| 5 | Background Mode | "Behind Steam art" (safe) or "Replace everything" |
| 6 | Corner Radius | Sharp -> Pill |
| 7 | Focus Zoom | Off -> Huge |
| 8 | Dim Unfocused Tiles | Off -> Spotlight |
| 9 | Tile Ring | None / White / Accent / Accent 2 / White + Accent... |
| 10 | Tile Glow | Off / Soft / Strong / Dual Accent |
| 11 | Focus Fill | White (PS5) / Accent (Xbox) / Gradient / Glass for buttons, rows, tabs |
| 12 | Tab Style | Pill / Underline / Pill + Underline / Plain |
| 13 | Animation Speed | Instant -> Cinematic |
| 14 | Side Panels | Frosted / Solid / Clear for Quick Access + Steam menu |
| 15 | Font | Steam default, Segoe-style, SST-style, Rounded (only fonts installed on the Deck are used) |
| 16-18 | Toggles | Transparent top bar, recolor Steam accent, restyle buttons/rows |

## Custom wallpaper
Put an image anywhere under `/home/deck/homebrew/themes/`, choose Background -> Custom Image, then pick the file.

## If something looks off
Valve hashes Steam's CSS class names and renames them in updates. See `TUNING.md`.
