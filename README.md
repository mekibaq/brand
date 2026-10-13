# mekiba brand

The files you need to show mekiba correctly: the logo as vector and image, the app icon, and the color and font tokens. The same files are on [mekiba.si/docs, Signal Kit](https://mekiba.si/docs/#signal-kit); the rules are the [Identity Spec](https://mekiba.si/docs/#identity-spec).

| File | What it is |
|---|---|
| `mekiba-mark.svg`, `mekiba-mark-1024.png` | The mark: ring, core and orbit. For avatars, small spaces and anywhere the name is already written |
| `mekiba-lockup.svg`, `mekiba-lockup-2400.png` | Mark and name together, as in the site header. The name is drawn as outlines, so no font is needed |
| `mekiba-icon.svg`, `mekiba-icon-512.png` | App icon: the mark on a dark rounded square, slightly heavier so it stays sharp at 16 px |
| `mekiba-tokens.css`, `mekiba-tokens.json` | Colors and fonts as variables |

Every logo file is made for mekiba's dark background (`#060608`) or similar dark surfaces. Versions for light and lime backgrounds are not defined yet.

## Name

- **mekiba**, always lowercase, also at the start of a sentence. Not Mekiba or MEKIBA.
- **$MEKIBA** for the token.
- Product names as written: Quantum Scan, Quantum Vault, Key Lab, Chain Radar, Quantum Observatory, Quantum AI. The terminal is the Quantum Defense Terminal.
- Tagline: *The Quantum Toolkit for Web3.* Domain: mekiba.si.

## Logo

| Part | Color | Geometry (24-unit grid) |
|---|---|---|
| Ring | `#ECE8E1` | Centre (12, 12), radius 8.5, stroke 1.4 |
| Core | `#ECE8E1` | Centre (12, 12), radius 2.2 |
| Orbit | `#D2FE05` | Centre (20.5, 12) on the ring, radius 2 |
| App icon | Same colors | Rounded square 24 × 24, corner 5, `#060608`; ring radius 7.5, stroke 1.6; orbit radius 2.2 at (19.5, 12) |

- **Clear space:** at least 4 units of the 24-unit grid (the orbit's diameter) free on every side.
- **Minimum size:** mark 16 px, lockup 88 px wide. Below 24 px, use the app icon.
- **Always the official file.** Do not redraw the mark, retype the name in a font, change a color, stretch it, or add outlines, glows or shadows.

## Color

| Token | Value | Role |
|---|---|---|
| ink | `#060608` | Background |
| fg | `#ECE8E1` | Text, logo ring and core |
| mute | `#8D8A85` | Secondary text |
| lime | `#D2FE05` | Accent, logo orbit, colored backgrounds |
| ice | `#9FD8FF` | Support |
| violet | `#B7A4FF` | Support |
| mint | `#7BE3B6` | Support, positive |
| red | `#F2647A` | Negative only |

## Fonts

Roboto Condensed (300, 400, 500, 600) for headings, text and the wordmark; Geist Mono (400, 500) for code and data. Both are free under the SIL Open Font License 1.1 and load from Google Fonts; they are not in this repository.

## Using these files

The mekiba name and logo identify mekiba. You may use these files, unchanged, to refer to mekiba (articles, listings, integrations, community posts). No other rights are granted, and using them does not mean mekiba endorses you.
