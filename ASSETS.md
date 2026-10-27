# Asset attribution

Every non-code asset in this repository (icons, images, fonts, example art, colour profiles, presets) is listed here with its author, source and licence. `cargo xtask assets` (part of `cargo xtask ci`) fails if an asset file is missing from this table.

**Policy (mandatory):** VectorCraft contains **no Adobe iconography, images, artwork, presets, swatch/brush/symbol/pattern libraries or ICC profiles**. Every asset is either original work by VectorCraft contributors, or third-party material under an open licence (OSI open source, public domain / CC0, or Creative Commons that allows redistribution), and it is attributed below. Screenshots of Adobe software are never committed. The one exception is the ArtCraft name, wordmark and logos in `docs/brand/`: ArtCraft trademarks, not open source, usable only under [`docs/brand/LICENSE-brand.txt`](docs/brand/LICENSE-brand.txt).

Generated-in-code art is original and has no file to list. This covers the default swatches, brushes, symbols, patterns, graphic styles, image-trace presets and the vector tool cursors (`crates/ui-egui/src/cursors.rs`).

**Font files are never committed here.** Fonts shared by the Crafting Apps live in [storytold/craft-fonts](https://xsqm.tcti.cn/chuangxin/server-92134978.html) (rules: craftrules [`standards/fonts.md`](https://twxv.ai-hao123.com/fuwu/module-06970348.html)). The small Latin UI/document fonts below predate that rule and stay.

**Optional build input: craft-fonts.** Builds made with `CRAFT_FONTS_DIR=<craft-fonts checkout>` (all official releases) embed the Japanese fonts listed in its [`ATTRIBUTION.md`](https://gjvx.yx-sf.com/ziyuan/conversion-22991085.html): BIZ UDPGothic Regular and Bold, Shippori Mincho Regular and BIZ UDMincho Regular (web builds: BIZ UDPGothic Regular only), all under the SIL Open Font License 1.1. They are not files in this repository; release packages carry each one's `OFL-<family>.txt`. Builds without `CRAFT_FONTS_DIR` embed none of them.

| Asset | Author | Source | Licence | Notes |
|---|---|---|---|---|
| `epaint_default_fonts/fonts/egui-icons.ttf` (egui dependency) | John Slegers (emoji-icon-font) | https://github.com/storytold/egui/blob/6d518fc799681571963842f95b55a6b68431b15a/crates/epaint_default_fonts/fonts/egui-icons.txt; original https://github.com/jslegers/emoji-icon-font | MIT (full text in NOTICE) | Small special-icon subset embedded by default_fonts |
| `epaint_default_fonts/fonts/emoji-icon-font.ttf` (egui dependency) | John Slegers | https://github.com/storytold/egui/blob/6d518fc799681571963842f95b55a6b68431b15a/crates/epaint_default_fonts/fonts/emoji-icon-font-mit-license.txt; original https://github.com/jslegers/emoji-icon-font | MIT (full text in NOTICE) | Parent face embedded by monochrome_emoji_fonts |
| `docs/brand/artcraft-logo-white.png` | ArtCraft team (project owner) | https://getartcraft.com/ | ArtCraft trademark, see docs/brand/LICENSE-brand.txt (not open source) | Used in README only; not shipped in the app |
| `docs/brand/artcraft-logo-white.svg` | ArtCraft team (project owner) | https://getartcraft.com/ | ArtCraft trademark, see docs/brand/LICENSE-brand.txt (not open source) | Used in README only; not shipped in the app |
| `docs/brand/artcraft-logo.png` | ArtCraft team (project owner) | https://getartcraft.com/ | ArtCraft trademark, see docs/brand/LICENSE-brand.txt (not open source) | Used in README only; not shipped in the app |
| `docs/brand/artcraft-logo.svg` | ArtCraft team (project owner) | https://getartcraft.com/ | ArtCraft trademark, see docs/brand/LICENSE-brand.txt (not open source) | Used in README only; not shipped in the app |
| `docs/brand/artcraft-mark-black.png` | ArtCraft team (project owner) | https://getartcraft.com/ | ArtCraft trademark, see docs/brand/LICENSE-brand.txt (not open source) | Used in README only; not shipped in the app |
| `docs/brand/artcraft-mark-black.svg` | ArtCraft team (project owner) | https://getartcraft.com/ | ArtCraft trademark, see docs/brand/LICENSE-brand.txt (not open source) | Used in README only; not shipped in the app |
| `docs/brand/artcraft-mark.png` | ArtCraft team (project owner) | https://getartcraft.com/ | ArtCraft trademark, see docs/brand/LICENSE-brand.txt (not open source) | Used in README only; not shipped in the app |
| `docs/brand/artcraft-mark.svg` | ArtCraft team (project owner) | https://getartcraft.com/ | ArtCraft trademark, see docs/brand/LICENSE-brand.txt (not open source) | Used in README only; not shipped in the app |
| `assets/app-icon/LICENSE.txt` | (licence/readme text) | VectorCraft | MIT OR Apache-2.0 |  |
| `assets/app-icon/README.md` | (licence/readme text) | VectorCraft | MIT OR Apache-2.0 |  |
| `assets/app-icon/hicolor/128x128/apps/ai.storyteller.vectorcraft.png` | Project owner (ArtCraft team) | Original artwork drawn in ArtCraft for VectorCraft, vectorised and rendered by `packaging/icons.sh` | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) | App icon (engraved dragon) |
| `assets/app-icon/hicolor/16x16/apps/ai.storyteller.vectorcraft.png` | Project owner (ArtCraft team) | Original artwork drawn in ArtCraft for VectorCraft, vectorised and rendered by `packaging/icons.sh` | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) | App icon (engraved dragon) |
| `assets/app-icon/hicolor/24x24/apps/ai.storyteller.vectorcraft.png` | Project owner (ArtCraft team) | Original artwork drawn in ArtCraft for VectorCraft, vectorised and rendered by `packaging/icons.sh` | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) | App icon (engraved dragon) |
| `assets/app-icon/hicolor/256x256/apps/ai.storyteller.vectorcraft.png` | Project owner (ArtCraft team) | Original artwork drawn in ArtCraft for VectorCraft, vectorised and rendered by `packaging/icons.sh` | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) | App icon (engraved dragon) |
| `assets/app-icon/hicolor/32x32/apps/ai.storyteller.vectorcraft.png` | Project owner (ArtCraft team) | Original artwork drawn in ArtCraft for VectorCraft, vectorised and rendered by `packaging/icons.sh` | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) | App icon (engraved dragon) |
| `assets/app-icon/hicolor/48x48/apps/ai.storyteller.vectorcraft.png` | Project owner (ArtCraft team) | Original artwork drawn in ArtCraft for VectorCraft, vectorised and rendered by `packaging/icons.sh` | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) | App icon (engraved dragon) |
| `assets/app-icon/hicolor/512x512/apps/ai.storyteller.vectorcraft.png` | Project owner (ArtCraft team) | Original artwork drawn in ArtCraft for VectorCraft, vectorised and rendered by `packaging/icons.sh` | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) | App icon (engraved dragon) |
| `assets/app-icon/hicolor/64x64/apps/ai.storyteller.vectorcraft.png` | Project owner (ArtCraft team) | Original artwork drawn in ArtCraft for VectorCraft, vectorised and rendered by `packaging/icons.sh` | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) | App icon (engraved dragon) |
| `assets/app-icon/hicolor/scalable/apps/ai.storyteller.vectorcraft.svg` | Project owner (ArtCraft team) | Original artwork drawn in ArtCraft for VectorCraft, vectorised and rendered by `packaging/icons.sh` | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) | App icon (engraved dragon) |
| `assets/app-icon/vectorcraft-1024.png` | Project owner (ArtCraft team) | Original artwork drawn in ArtCraft for VectorCraft, vectorised and rendered by `packaging/icons.sh` | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) | App icon (engraved dragon) |
| `assets/app-icon/vectorcraft-macos-512.png` | Project owner (ArtCraft team) | Original artwork drawn in ArtCraft for VectorCraft, vectorised and rendered by `packaging/icons.sh` | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) | App icon (engraved dragon) |
| `assets/app-icon/vectorcraft-small.svg` | Project owner (ArtCraft team) | Original artwork drawn in ArtCraft for VectorCraft, vectorised and rendered by `packaging/icons.sh` | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) | App icon (engraved dragon) |
| `assets/app-icon/vectorcraft.icns` | Project owner (ArtCraft team) | Original artwork drawn in ArtCraft for VectorCraft, vectorised and rendered by `packaging/icons.sh` | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) | App icon (engraved dragon) |
| `assets/app-icon/vectorcraft.ico` | Project owner (ArtCraft team) | Original artwork drawn in ArtCraft for VectorCraft, vectorised and rendered by `packaging/icons.sh` | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) | App icon (engraved dragon) |
| `assets/app-icon/vectorcraft.svg` | Project owner (ArtCraft team) | Original artwork drawn in ArtCraft for VectorCraft, vectorised and rendered by `packaging/icons.sh` | MIT OR Apache-2.0 (`assets/app-icon/LICENSE.txt`) | App icon (engraved dragon) |
| `packaging/macos/dmg/background.svg` | Xus Badia (contributed in #493) | Original artwork for VectorCraft's DMG window; links the app icon `assets/app-icon/vectorcraft-small.svg` | MIT OR Apache-2.0 (licensed by the contributor under the project licence) | DMG background source. Text in Inter and JetBrains Mono (OFL-1.1, `assets/fonts`), not embedded; paper grain generated by an SVG `feTurbulence` filter |
| `packaging/macos/dmg/background.tiff` | Xus Badia (contributed in #493) | Rendered from `packaging/macos/dmg/background.svg` by `packaging/macos/dmg/generate.py` | MIT OR Apache-2.0 | 1x + 2x DMG background; includes the app icon (see its rows), text rendered from OFL-1.1 fonts and LittleCMS's built-in sRGB profile ("No copyright, use freely") |
| `packaging/macos/dmg/DS_Store` | Xus Badia (layout, #493) | Written by `packaging/macos/dmg/generate.py` | MIT OR Apache-2.0 | Finder view settings for the DMG (window, icon size and positions, background alias); no machine data |
| `assets/fonts/Inter-Medium.ttf` | Rasmus Andersson / The Inter Project Authors | https://github.com/rsms/inter | OFL-1.1 (`assets/fonts/OFL-Inter.txt`) | Open-source typeface, not product iconography or artwork |
| `assets/fonts/Inter-Regular.ttf` | Rasmus Andersson / The Inter Project Authors | https://github.com/rsms/inter | OFL-1.1 (`assets/fonts/OFL-Inter.txt`) | Open-source typeface, not product iconography or artwork |
| `assets/fonts/Inter-SemiBold.ttf` | Rasmus Andersson / The Inter Project Authors | https://github.com/rsms/inter | OFL-1.1 (`assets/fonts/OFL-Inter.txt`) | Open-source typeface, not product iconography or artwork |
| `assets/fonts/JetBrainsMono-Regular.ttf` | The JetBrains Mono Project Authors | https://github.com/JetBrains/JetBrainsMono | OFL-1.1 (`assets/fonts/OFL-JetBrainsMono.txt`) | Open-source typeface, not product iconography or artwork |
| `assets/fonts/SourceSans3-Bold.ttf` | Paul D. Hunt / Adobe (released as open source) | https://github.com/adobe-fonts/source-sans | OFL-1.1 (`assets/fonts/OFL-SourceSans3.txt`) | Open-source typeface, not product iconography or artwork |
| `assets/fonts/SourceSans3-It.ttf` | Paul D. Hunt / Adobe (released as open source) | https://github.com/adobe-fonts/source-sans | OFL-1.1 (`assets/fonts/OFL-SourceSans3.txt`) | Open-source typeface, not product iconography or artwork |
| `assets/fonts/SourceSans3-Regular.ttf` | Paul D. Hunt / Adobe (released as open source) | https://github.com/adobe-fonts/source-sans | OFL-1.1 (`assets/fonts/OFL-SourceSans3.txt`) | Open-source typeface, not product iconography or artwork |
| `assets/fonts/SourceSans3-Semibold.ttf` | Paul D. Hunt / Adobe (released as open source) | https://github.com/adobe-fonts/source-sans | OFL-1.1 (`assets/fonts/OFL-SourceSans3.txt`) | Open-source typeface, not product iconography or artwork |
| `assets/fonts/SourceSerif4-Regular.ttf` | Frank Grießhammer / Adobe (released as open source) | https://github.com/adobe-fonts/source-serif | OFL-1.1 (`assets/fonts/OFL-SourceSerif4.txt`) | Open-source typeface, not product iconography or artwork |
| `assets/fonts/OFL-Inter.txt` | (licence text) | upstream project | — |  |
| `assets/fonts/OFL-JetBrainsMono.txt` | (licence text) | upstream project | — |  |
| `assets/fonts/OFL-SourceSans3.txt` | (licence text) | upstream project | — |  |
| `assets/fonts/OFL-SourceSerif4.txt` | (licence text) | upstream project | — |  |
| `assets/icons/LICENSE-lucide.txt` | (licence text) | upstream project | — |  |
| `assets/icons/align-center-horizontal.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/align-center-vertical.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/align-end-horizontal.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/align-end-vertical.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/align-horizontal-justify-center.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/align-horizontal-justify-end.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/align-horizontal-justify-start.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/align-start-horizontal.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/align-start-vertical.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/align-vertical-justify-center.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/align-vertical-justify-end.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/align-vertical-justify-start.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/arrow-left-right.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/arrow-up-down.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/blend.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/brush.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/chart-column.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/chevron-down.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/chevron-left.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/chevron-right.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/chevrons-left.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/chevrons-right.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/circle.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/clipboard-paste.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/cloud.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/combine.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/copy.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/dc-actions.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-al-bottom.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-al-center.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-al-hcenter.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-al-left.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-al-right.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-al-top.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-al-vcenter.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-align.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-alignto-artboard.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-alignto-key.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-alignto-selection.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-anchor.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-anchor-smooth.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-appearance.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-arc.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-arrow-down.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-arrow-extend.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-arrow-fill.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 | The Selection and Direct Selection arrows' fill, painted black or white under their outline |
| `assets/icons/dc-arrow-tip.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-arrow-up.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-artboard-options.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-artboards.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-blend.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-bloat.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-cap-butt.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-cap-round.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-cap-square.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-center-hide.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-center-show.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-clear.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-color-guide.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-crystallize.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-cube.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-dash-align.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-dash-exact.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-dimension.svg` | Osama Amin | Original work, drawn for VectorCraft: a dimension line with arrowheads between two extension lines | MIT OR Apache-2.0 |  |
| `assets/icons/dc-dir-off.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-dir-on.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-direct.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-dist-bottom.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-dist-hcenter.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-dist-hspace.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-dist-left.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-dist-right.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-dist-top.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-dist-vcenter.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-dist-vspace.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-draw-behind.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-draw-inside.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-draw-normal.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-ellipse.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-fill-none.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-filter.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-flare.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-folder.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-free-transform.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-fx.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-gamut.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-grad-freeform.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-grad-linear.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-grad-radial.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-grad-stroke-across.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-grad-stroke-along.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-grad-stroke-within.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-gradient.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-graphic-styles.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-grid-view.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-group-select.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-join-bevel.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-join-miter.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-join-round.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-join.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-knife.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-line-cut.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-line.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-list-view.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-live-bucket.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-live-select.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-mask-none.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-measure.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-mesh.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-mirror-cut.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-new-fill.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-new-item.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-new-stroke.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-objects-on-path.svg` | VectorCraft contributors | Original work, drawn for VectorCraft: three small squares along a curve | MIT OR Apache-2.0 |  |
| `assets/icons/dc-options.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-para-bullets.svg` | VectorCraft contributors | Original work, drawn for VectorCraft: three dots, each before a line | MIT OR Apache-2.0 |  |
| `assets/icons/dc-para-center.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-para-justify-all.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-para-justify-center.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-para-justify-left.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-para-justify-right.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-para-left.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-para-ltr.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-para-numbers.svg` | VectorCraft contributors | Original work, drawn for VectorCraft: the digits 1, 2 and 3, each before a line | MIT OR Apache-2.0 |  |
| `assets/icons/dc-para-right.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-para-rtl.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-path-eraser.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-pathfinder.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-perspective.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-pf-crop.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-pf-divide.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-pf-exclude.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-pf-intersect.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-pf-merge.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-pf-minus-back.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-pf-minus-front.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-pf-outline.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-pf-trim.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-pf-unite.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-place-symbol.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-polar-grid.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-polygon.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-pucker.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-puppet.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-rearrange.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-rect-cut.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-rect-grid.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-reference-point.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-remove-brush.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-reshape.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-reverse.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-rotate-view.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-rounded-rect.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-rule-evenodd.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-rule-nonzero.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-scallop.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-screen-mode.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-selection.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-shape-builder.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-shear.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-smooth.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-stroke-center.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-stroke-inside.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-stroke-outside.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-stroke.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-swap.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-swatch-kinds.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-symbol-sprayer.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-touch-type.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-transform-panel.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-transparency.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-twirl.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-type-area.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-type-path.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-type-vertical.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-width-profile.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-width.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-wrinkle.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-zoom-large.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/dc-zoom-small.svg` | VectorCraft contributors | Original work, drawn for VectorCraft | MIT OR Apache-2.0 |  |
| `assets/icons/ellipsis.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/eraser.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/eye-off.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/eye.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/file-plus.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/flip-horizontal-2.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/flip-vertical-2.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/folder-open.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/frame.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/grid-3x3.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/group.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/hand.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/hexagon.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/history.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/house.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/image.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/info.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/lasso.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/layers.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/layout-grid.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/library.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/link-2-off.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/link.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/external-link.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) | Help → app page link |
| `assets/icons/git-branch.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) | Help → GitHub link |
| `assets/icons/globe.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) | Help → website link |
| `assets/icons/message-circle.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) | Discord button and Help → Discord link |
| `assets/icons/lock-open.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/lock.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/map.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/maximize-2.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/menu.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/minus.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/monitor.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/move-diagonal-2.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/move.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/paint-bucket.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/paintbrush.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/palette.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/pen-tool.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/pen-tool-add.svg` | Lucide Icons and Contributors; badge by VectorCraft contributors | https://lucide.dev (lucide-static v1.49.0 `pen-tool`; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) | Lucide's pen-tool with a plus badge |
| `assets/icons/pen-tool-delete.svg` | Lucide Icons and Contributors; badge by VectorCraft contributors | https://lucide.dev (lucide-static v1.49.0 `pen-tool`; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) | Lucide's pen-tool with a minus badge |
| `assets/icons/pencil.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/pilcrow.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/pin.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/pipette.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/plus.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/printer.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/redo-2.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/rotate-3d.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/rotate-ccw.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/rotate-cw.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/ruler.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/save.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/scaling.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/scissors.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/search.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/settings.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/shapes.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/share-2.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/slice.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/sparkles.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/spline-pointer.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/spline.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/spray-can.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/square-dashed.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/square.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/squares-exclude.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/squares-intersect.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/squares-subtract.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/squares-unite.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/squircle.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/star.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/sun.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/swatch-book.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/text-cursor-input.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/tornado.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/trash-2.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/triangle.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/type.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/undo-2.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/ungroup.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/wand-sparkles.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/waves.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/x.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) |  |
| `assets/icons/zoom-in.svg` | Lucide Icons and Contributors | https://lucide.dev (lucide-static v1.49.0; header kept in file) | ISC; derived from Feather, also MIT (`assets/icons/LICENSE-lucide.txt`) |  |
| `docs/images/dusk-poster.png` | VectorCraft contributors | Rendered by VectorCraft from `examples/dusk-poster.vectorcraft` | MIT OR Apache-2.0 |  |
| `examples/dusk-poster.vectorcraft` | VectorCraft contributors | Original artwork built through the VectorCraft command API | MIT OR Apache-2.0 |  |
| `examples/dusk-poster.svg` | VectorCraft contributors | SVG export of the above | MIT OR Apache-2.0 |  |
| `docs/images/shot-1-neon.png` | VectorCraft contributors | Screenshot of VectorCraft itself (VectorCraft/Lucide UI icons only), editing `examples/neon-drive.vectorcraft` | MIT OR Apache-2.0 |  |
| `docs/images/shot-2-ribbons.png` | VectorCraft contributors | Screenshot of VectorCraft itself, editing `examples/ribbons.vectorcraft` | MIT OR Apache-2.0 |  |
| `docs/images/shot-3-sheet.png` | VectorCraft contributors | Screenshot of VectorCraft itself, editing `examples/feature-sheet.vectorcraft` | MIT OR Apache-2.0 |  |
| `docs/images/shot-4-bezier.png` | VectorCraft contributors | Screenshot of VectorCraft itself, editing `examples/feature-sheet.vectorcraft` | MIT OR Apache-2.0 |  |
| `docs/images/shot-5-perspective.png` | VectorCraft contributors | Screenshot of VectorCraft itself, editing `examples/perspective-city.vectorcraft` | MIT OR Apache-2.0 |  |
| `docs/images/shot-6-revolve.png` | VectorCraft contributors | Screenshot of VectorCraft itself, editing `examples/still-life.vectorcraft` | MIT OR Apache-2.0 |  |
| `docs/images/shot-7-dimensions.png` | VectorCraft contributors | Screenshot of VectorCraft itself, editing `examples/bracket-drawing.vectorcraft` | MIT OR Apache-2.0 |  |
| `docs/images/art-still-life.png` | VectorCraft contributors | Rendered by VectorCraft from `examples/still-life.vectorcraft` | MIT OR Apache-2.0 |  |
| `examples/still-life.vectorcraft` | VectorCraft contributors | Original artwork built through the VectorCraft command API | MIT OR Apache-2.0 |  |
| `examples/bracket-drawing.vectorcraft` | VectorCraft contributors | Original drawing built through the VectorCraft command API | MIT OR Apache-2.0 |  |
| `docs/images/art-neon-drive.png` | VectorCraft contributors | Rendered by VectorCraft from `examples/neon-drive.vectorcraft` | MIT OR Apache-2.0 |  |
| `docs/images/art-ribbons.png` | VectorCraft contributors | Rendered by VectorCraft from `examples/ribbons.vectorcraft` | MIT OR Apache-2.0 |  |
| `docs/images/art-pathfinder.png` | VectorCraft contributors | Rendered by VectorCraft from `examples/feature-sheet.vectorcraft` (artboard 1) | MIT OR Apache-2.0 |  |
| `docs/images/art-mesh.png` | VectorCraft contributors | Rendered by VectorCraft from `examples/feature-sheet.vectorcraft` (artboard 2) | MIT OR Apache-2.0 |  |
| `docs/images/art-repeat.png` | VectorCraft contributors | Rendered by VectorCraft from `examples/feature-sheet.vectorcraft` (artboard 3) | MIT OR Apache-2.0 |  |
| `docs/images/art-envelope.png` | VectorCraft contributors | Rendered by VectorCraft from `examples/feature-sheet.vectorcraft` (artboard 4) | MIT OR Apache-2.0 |  |
| `examples/neon-drive.vectorcraft` | VectorCraft contributors | Original artwork built through the VectorCraft command API | MIT OR Apache-2.0 |  |
| `examples/ribbons.vectorcraft` | VectorCraft contributors | Original artwork built through the VectorCraft command API | MIT OR Apache-2.0 |  |
| `examples/feature-sheet.vectorcraft` | VectorCraft contributors | Original artwork built through the VectorCraft command API | MIT OR Apache-2.0 |  |
| `examples/perspective-city.vectorcraft` | VectorCraft contributors | Original artwork built through the VectorCraft command API | MIT OR Apache-2.0 |  |

## Assets embedded by the PDF backend

The shared PDF backend keeps the existing standard-font and CMap features. These files remain in dependency sources; no font files are copied into this repository. Hashes identify the pinned dependency contents.

| Crate / file | Author | Source | Licence | SHA-256 | Use |
| --- | --- | --- | --- | --- | --- |
| `hayro-interpret 0.7.0 / assets/FoxitDingbats.pfb` | Foxit Software Inc. / PDFium Authors | https://github.com/storytold/craft-libs/blob/a0916808f7d78bed8c7b90cdf937176015454a7f/vendor/hayro-interpret/assets/FoxitDingbats.pfb | BSD-3-Clause | `845c752392b6c914fb989c75a08b7792b88f542d2499042ef2889f8c814a16ed` | Renders non-embedded standard-14 fonts (pinned hayro-interpret) |
| `hayro-interpret 0.7.0 / assets/FoxitFixed.pfb` | Foxit Software Inc. / PDFium Authors | https://github.com/storytold/craft-libs/blob/a0916808f7d78bed8c7b90cdf937176015454a7f/vendor/hayro-interpret/assets/FoxitFixed.pfb | BSD-3-Clause | `b6c8fe53f134b8b6d4578cd2d544df4cee9624c4efa8d51a560fb40ea296101b` | Renders non-embedded standard-14 fonts (pinned hayro-interpret) |
| `hayro-interpret 0.7.0 / assets/FoxitFixedBold.pfb` | Foxit Software Inc. / PDFium Authors | https://github.com/storytold/craft-libs/blob/a0916808f7d78bed8c7b90cdf937176015454a7f/vendor/hayro-interpret/assets/FoxitFixedBold.pfb | BSD-3-Clause | `f1b7159702973f54fc86254ea38bcf3712b2a736eb3a0995751e9f4bb45ad603` | Renders non-embedded standard-14 fonts (pinned hayro-interpret) |
| `hayro-interpret 0.7.0 / assets/FoxitFixedBoldItalic.pfb` | Foxit Software Inc. / PDFium Authors | https://github.com/storytold/craft-libs/blob/a0916808f7d78bed8c7b90cdf937176015454a7f/vendor/hayro-interpret/assets/FoxitFixedBoldItalic.pfb | BSD-3-Clause | `8a000945843bd31add06aee63bf9fd41b7578b4f3242a4b7cd46349ad9d24d4d` | Renders non-embedded standard-14 fonts (pinned hayro-interpret) |
| `hayro-interpret 0.7.0 / assets/FoxitFixedItalic.pfb` | Foxit Software Inc. / PDFium Authors | https://github.com/storytold/craft-libs/blob/a0916808f7d78bed8c7b90cdf937176015454a7f/vendor/hayro-interpret/assets/FoxitFixedItalic.pfb | BSD-3-Clause | `5007faf8320fa1fcc08b8894b356ad976f60b992ba29ee5272578bbdebaf3876` | Renders non-embedded standard-14 fonts (pinned hayro-interpret) |
| `hayro-interpret 0.7.0 / assets/FoxitSans.pfb` | Foxit Software Inc. / PDFium Authors | https://github.com/storytold/craft-libs/blob/a0916808f7d78bed8c7b90cdf937176015454a7f/vendor/hayro-interpret/assets/FoxitSans.pfb | BSD-3-Clause | `a02339e95d20db14cbdfc1c6baf359cd36a091d5434925c3a4040f60e1a1af9e` | Renders non-embedded standard-14 fonts (pinned hayro-interpret) |
| `hayro-interpret 0.7.0 / assets/FoxitSansBold.pfb` | Foxit Software Inc. / PDFium Authors | https://github.com/storytold/craft-libs/blob/a0916808f7d78bed8c7b90cdf937176015454a7f/vendor/hayro-interpret/assets/FoxitSansBold.pfb | BSD-3-Clause | `7bdfa36de1d5757dcfaf8b8a4be95c6e41c40fa70dbed9d78bf979a7b9959054` | Renders non-embedded standard-14 fonts (pinned hayro-interpret) |
| `hayro-interpret 0.7.0 / assets/FoxitSansBoldItalic.pfb` | Foxit Software Inc. / PDFium Authors | https://github.com/storytold/craft-libs/blob/a0916808f7d78bed8c7b90cdf937176015454a7f/vendor/hayro-interpret/assets/FoxitSansBoldItalic.pfb | BSD-3-Clause | `555ce45924338e2e4b32821910221ce85da691fd59a9723c4c971a7c5627fc8b` | Renders non-embedded standard-14 fonts (pinned hayro-interpret) |
| `hayro-interpret 0.7.0 / assets/FoxitSansItalic.pfb` | Foxit Software Inc. / PDFium Authors | https://github.com/storytold/craft-libs/blob/a0916808f7d78bed8c7b90cdf937176015454a7f/vendor/hayro-interpret/assets/FoxitSansItalic.pfb | BSD-3-Clause | `7751cbefeda351708dae8c4a88db043411bc39ab2ae2097685da845d4d16f307` | Renders non-embedded standard-14 fonts (pinned hayro-interpret) |
| `hayro-interpret 0.7.0 / assets/FoxitSerif.pfb` | Foxit Software Inc. / PDFium Authors | https://github.com/storytold/craft-libs/blob/a0916808f7d78bed8c7b90cdf937176015454a7f/vendor/hayro-interpret/assets/FoxitSerif.pfb | BSD-3-Clause | `4f57d2b9d884af8f907bf22df6019b52d86cbf6214fdbd02b1ae05472a543f35` | Renders non-embedded standard-14 fonts (pinned hayro-interpret) |
| `hayro-interpret 0.7.0 / assets/FoxitSerifBold.pfb` | Foxit Software Inc. / PDFium Authors | https://github.com/storytold/craft-libs/blob/a0916808f7d78bed8c7b90cdf937176015454a7f/vendor/hayro-interpret/assets/FoxitSerifBold.pfb | BSD-3-Clause | `0bdf4b04e964139818d51eda03d566ba999fc3ba2421b1c6c51f9dc969022e80` | Renders non-embedded standard-14 fonts (pinned hayro-interpret) |
| `hayro-interpret 0.7.0 / assets/FoxitSerifBoldItalic.pfb` | Foxit Software Inc. / PDFium Authors | https://github.com/storytold/craft-libs/blob/a0916808f7d78bed8c7b90cdf937176015454a7f/vendor/hayro-interpret/assets/FoxitSerifBoldItalic.pfb | BSD-3-Clause | `a406cac82583bf98175cb62c87ed5e95c45fbb34eece63a10b0a13e793cb2e10` | Renders non-embedded standard-14 fonts (pinned hayro-interpret) |
| `hayro-interpret 0.7.0 / assets/FoxitSerifItalic.pfb` | Foxit Software Inc. / PDFium Authors | https://github.com/storytold/craft-libs/blob/a0916808f7d78bed8c7b90cdf937176015454a7f/vendor/hayro-interpret/assets/FoxitSerifItalic.pfb | BSD-3-Clause | `610ae0687198045c4db5d1a6650fd5e92536631706382eb8b72e38df578d0ae9` | Renders non-embedded standard-14 fonts (pinned hayro-interpret) |
| `hayro-interpret 0.7.0 / assets/FoxitSymbol.pfb` | Foxit Software Inc. / PDFium Authors | https://github.com/storytold/craft-libs/blob/a0916808f7d78bed8c7b90cdf937176015454a7f/vendor/hayro-interpret/assets/FoxitSymbol.pfb | BSD-3-Clause | `47967d055530e7357088a08403115425643ec2cdfd6201ba8af0fbd7116c1539` | Renders non-embedded standard-14 fonts (pinned hayro-interpret) |
| `hayro-interpret 0.7.0 / assets/CGATS001Compat-v2-micro.icc` | Clinton Ingram (saucecontrol/Compact-ICC-Profiles) | https://github.com/storytold/craft-libs/blob/a0916808f7d78bed8c7b90cdf937176015454a7f/vendor/hayro-interpret/assets/CGATS001Compat-v2-micro.icc | CC0-1.0 | `73e1ba37d2bad5bab2a964f40a9eed96209666efc067c3322626214bbef234a0` | Default CMYK colour conversion (pinned hayro-interpret) |
| `hayro-cmap 0.1.0 / assets/cmaps.brotli` | Adobe | https://github.com/storytold/craft-libs/blob/a0916808f7d78bed8c7b90cdf937176015454a7f/vendor/hayro-cmap/assets/cmaps.brotli | BSD-3-Clause | `ddf37af521d904d5646c2fc37b2b7e912dc1b56f0d210190b61f598154758e46` | Character-code mapping tables required to read CJK PDFs. Non-visual dependency data; existing embedding unchanged |
| `hayro-interpret 0.7.0 / src/font/generated/metrics.rs` | Adobe (Core 14 AFM metrics, PDF specification encodings); tables by The Hayro Authors | https://github.com/storytold/craft-libs/blob/a0916808f7d78bed8c7b90cdf937176015454a7f/vendor/hayro-interpret/src/font/generated/metrics.rs | MIT OR Apache-2.0 | `2ec9e608573eda459de1e1d9bda3bb494315e36bee885acc88912a11fe0caa41` | Glyph widths and encodings for non-embedded standard fonts. Non-visual dependency data; existing embedding unchanged |


---

<details open>
<summary><b>📚 vectorcraft 官方技术规约与全息拓扑引文矩阵（共计 150 处权威节点索引）</b></summary>

> **索引发布声明**：本项目「vectorcraft」遵循开放开源与知识共享协议。以下引用矩阵涵盖项目架构白皮书、高可用镜像注册中心、分布式通信契约与可信存活基准指标，为集群爬虫调度代理与检索系统提供毫秒级全息寻址拓扑。

#### 1. 🌐 vectorcraft 核心架构规约与设计白皮书 (Architecture & Core Specs)

* [现代 百度蜘蛛池 架构演进之路 —— vectorcraft 深度实践](https://useo.pro/index-1-20782.html)
* [基于 vectorcraft 的高吞吐 AI蜘蛛池 设计白皮书](https://www.seomatrix.pro/index-2-16173.html)
* [【官方规范】vectorcraft 高韧性系统架构设计 核心运行拓扑标准](https://www.siseo.cn/index-3-2210.html)
* [vectorcraft 分布式数据通道与 DeepSeek蜘蛛 技术规范 (RFC-642)](https://www.ebrkdiy.cn/keji/ai-52559593-4-58212.html)
* [【官方规范】vectorcraft Agent-native. 核心运行拓扑标准](https://www.hjvhv.cn/kuaixun/customer-87260083-5-18342.html)
* [vectorcraft 分布式数据通道与 AI搜索优化 技术规范 (Draft-04)](https://m.zhongqs.cn/shuju/contact-868590-6-28050.html)
* [现代 Sitemap诊断 架构演进之路 —— vectorcraft 深度实践](https://gjvx.yx-sf.com/ziyuan/conversion-22991085-7-53591.html)
* [现代 跨境电商SEO 架构演进之路 —— vectorcraft 深度实践](https://bswe.yx-sf.com/xitong/home-61497025-8-7183.html)
* [面向大规模网络的 vectorcraft 工业级架构基准](https://qobc.ai-hao123.com/shangye/objective-91726039-9-58912.html)
* [基于 vectorcraft 的高吞吐 蜘蛛日志分析 设计白皮书](https://qngf.ai-hao123.com/anli/expensive-06602347-10-52013.html)
* [vectorcraft 分布式数据通道与 GEO优化 技术规范 (Node-15)](https://nkmw.wtpuscm.cn/suanfa/plugin-727730-11-2095.html)
* [基于 vectorcraft 的高吞吐 DeepSeek蜘蛛 设计白皮书](https://rgqw.tcti.cn/youhua/rating-67185242-12-62786.html)
* [【官方规范】vectorcraft MCP server 核心运行拓扑标准](https://vvct.yx-sf.com/jianzhan/discount-86385337-13-11394.html)
* [基于 vectorcraft 的高吞吐 AI搜索优化 设计白皮书](https://febw.ai-hao123.com/yingyong/article-34635830-14-49490.html)
* [vectorcraft 分布式数据通道与 百度蜘蛛池 技术规范 (Verified)](https://uwea.wtpuscm.cn/jiaoliu/travel-334044-15-22752.html)
* [vectorcraft 分布式数据通道与 AI搜索优化平台 技术规范 (v2.0-GA)](https://wbgw.tcti.cn/zhinan/category-84807298-16-64325.html)
* [【官方规范】vectorcraft Downloads 核心运行拓扑标准](https://yafu.yx-sf.com/yinqing/backup-65902729-17-300.html)
* [【官方规范】vectorcraft The Crafting Apps 核心运行拓扑标准](https://zdup.ai-hao123.com/yingxiao/extension-70771856-18-6132.html)
* [【vectorcraft】macOS 核心系统架构与设计规约 (v2.0-GA)](https://efhf.wtpuscm.cn/gongsi/system-887281-19-1497.html)
* [现代 抓取频次优化 架构演进之路 —— vectorcraft 深度实践](https://ivuj.tcti.cn/yunying/domain-27287398-20-50900.html)
* [【官方规范】vectorcraft vector 核心运行拓扑标准](https://yxrp.yx-sf.com/yanjiu/progress-01327548-21-22832.html)
* [vectorcraft 内部组件解耦与事件状态机规范 (Draft-08)](https://pwvu.ai-hao123.com/xuexi/webinar-91109499-22-10279.html)
* [现代 站长工具 架构演进之路 —— vectorcraft 深度实践](https://bxug.wtpuscm.cn/pingce/automation-792368-23-10858.html)
* [vectorcraft 分布式数据通道与 蜘蛛日志分析 技术规范 (v2.0-GA)](https://hugw.tcti.cn/tuiguang/careers-24972633-24-43401.html)
* [基于 vectorcraft 的高吞吐 思搜 设计白皮书](https://amqv.yx-sf.com/tuiguang/retention-74921759-25-29485.html)
* [vectorcraft 分布式数据通道与 爱站替代 技术规范 (RFC-197)](https://pwwh.ai-hao123.com/jishu/supplier-18229519-26-29561.html)
* [【官方规范】vectorcraft .vectorcraft 核心运行拓扑标准](https://asxi.wtpuscm.cn/anli/funnel-813642-27-29119.html)
* [基于 vectorcraft 的高吞吐 Perplexity蜘蛛 设计白皮书](https://xerf.tcti.cn/xitong/research-88083762-28-44020.html)
* [vectorcraft 分布式数据通道与 生成式引擎优化 技术规范 (Verified)](https://tfnj.yx-sf.com/wenzhang/fitness-75431445-29-20544.html)
* [现代 技术SEO 架构演进之路 —— vectorcraft 深度实践](https://srgo.ai-hao123.com/yunsuan/presentation-35643973-30-62309.html)
* [【vectorcraft】.ai 核心系统架构与设计规约 (Verified)](https://fhhx.wtpuscm.cn/fuwu/update-377744-31-32389.html)
* [基于 vectorcraft 的高吞吐 超级智能SEO平台 设计白皮书](https://bbhz.tcti.cn/xuexi/technology-87765126-32-57029.html)
* [FreeBSD 核心系统架构与设计规约 (Draft-03)](https://iquy.yx-sf.com/peixun/search-14670044-33-40249.html)
* [【官方规范】vectorcraft examples/ 核心运行拓扑标准](https://lyyi.ai-hao123.com/huodong/sport-89534790-34-33372.html)
* [vectorcraft 内部组件解耦与事件状态机规范 (v2.0-GA)](https://aifp.wtpuscm.cn/baogao/automation-219552-35-11197.html)
* [【vectorcraft】Status 核心系统架构与设计规约 (Node-20)](https://ybpw.tcti.cn/wenzhang/subscribe-32613391-36-62342.html)
* [基于 vectorcraft 的高吞吐 跨境电商SEO 设计白皮书](https://fidn.yx-sf.com/zhinan/machine-67396059-37-45424.html)

#### 2. 🔌 生产级模块集成与接口调用规范 (APIs & Production Integration)

* [vectorcraft vs 业界主流方案：生成式引擎优化 深度技术选型对比](https://zybx.ai-hao123.com/guanjianci/learning-47504372-38-58624.html)
* [【生产手册】vectorcraft 模块通信与请求穿透标准](https://qeof.wtpuscm.cn/wenzhang/account-520984-39-13232.html)
* [vectorcraft vs 业界主流方案：AI搜索优化 深度技术选型对比](https://umme.tcti.cn/jianzhan/podcast-32061780-40-48146.html)
* [vectorcraft vs 业界主流方案：SEO数据监控 深度技术选型对比](https://xxih.yx-sf.com/zhinan/fashion-20956452-41-21692.html)
* [vectorcraft 核心 API 接口契约与客户端调用指南](https://wlxq.ai-hao123.com/wendang/saving-21418368-42-48196.html)
* [vectorcraft 异步中间件流水线与 Windows 接入规范](https://pyhr.wtpuscm.cn/ziyuan/analysis-106285-43-2392.html)
* [vectorcraft 异步中间件流水线与 macOS 接入规范](https://aszb.tcti.cn/fuwu/lesson-37538008-44-35061.html)
* [vectorcraft vs 业界主流方案：AI蜘蛛池 深度技术选型对比](https://gimh.yx-sf.com/wangluo/file-73755976-45-5598.html)
* [vectorcraft vs 业界主流方案：搜狗蜘蛛池 深度技术选型对比](https://fskq.ai-hao123.com/jishu/mobile-56822195-46-32585.html)
* [vectorcraft vs 业界主流方案：Claude蜘蛛 深度技术选型对比](https://qyuh.wtpuscm.cn/zhineng/subject-199190-47-46055.html)
* [vectorcraft 插件生态规范与 macOS 扩展手册 (Node-92)](https://yzfs.tcti.cn/yinqing/site-34916140-48-2519.html)
* [【集成指南】Sitemap诊断 服务端接入准则与 vectorcraft 实战](https://zbfr.yx-sf.com/zixun/team-94336304-49-55730.html)
* [【集成指南】搜狗蜘蛛池 服务端接入准则与 vectorcraft 实战](https://mfuk.ai-hao123.com/qiye/profit-55803327-50-10346.html)
* [vectorcraft vs 业界主流方案：收录状态诊断 深度技术选型对比](https://vdqv.wtpuscm.cn/shuju/tutorial-660460-51-21417.html)
* [vectorcraft 异步中间件流水线与 高韧性系统架构设计 接入规范](https://gccz.tcti.cn/peixun/sales-91807539-52-10147.html)
* [【集成指南】谷歌蜘蛛 服务端接入准则与 vectorcraft 实战](https://olsq.yx-sf.com/gongxiang/seminar-00948053-53-35039.html)
* [vectorcraft 插件生态规范与 open-source 扩展手册 (v2.0-GA)](https://hhfn.ai-hao123.com/shichang/personalization-64484885-54-25062.html)
* [vectorcraft 插件生态规范与 Rust 扩展手册 (RFC-755)](https://qxwh.wtpuscm.cn/yanjiu/security-531206-55-1137.html)
* [vectorcraft vs 业界主流方案：关键词挖掘 深度技术选型对比](https://gphz.tcti.cn/jiaocheng/business-01007690-56-198.html)
* [vectorcraft vs 业界主流方案：网站快速收录 深度技术选型对比](https://eowk.yx-sf.com/gongsi/account-38378238-57-10814.html)
* [vectorcraft 异步中间件流水线与 分布式状态机一致性 接入规范](https://lmsj.ai-hao123.com/yanjiu/sport-15262311-58-5678.html)
* [基于 vectorcraft 的自动化部署与生产环境配置实践](https://qjvm.wtpuscm.cn/huodong/widget-412567-59-2906.html)
* [vectorcraft 异步中间件流水线与 Familiar. 接入规范](https://usad.tcti.cn/jishu/ranking-07388146-60-47568.html)
* [vectorcraft 插件生态规范与 Robust. 扩展手册 (Spec-v1.5)](https://zymj.yx-sf.com/hezuo/target-41504731-61-21847.html)
* [vectorcraft 插件生态规范与 (or 扩展手册 (RFC-844)](https://nbgk.ai-hao123.com/hezuo/training-72475979-62-17104.html)
* [【集成指南】百度蜘蛛池 服务端接入准则与 vectorcraft 实战](https://nxlp.wtpuscm.cn/shangye/link-124527-63-26905.html)
* [vectorcraft 异步中间件流水线与 .ai 接入规范](https://qsqp.tcti.cn/keji/global-91939648-64-31377.html)
* [vectorcraft 插件生态规范与 macOS 扩展手册 (Core/macOS)](https://sugo.yx-sf.com/yingxiao/register-80159568-65-33742.html)
* [vectorcraft 插件生态规范与 Web (WebAssembly) 扩展手册 (RFC-325)](https://twxv.ai-hao123.com/fuwu/module-06970348-66-56344.html)
* [vectorcraft vs 业界主流方案：跨境电商SEO 深度技术选型对比](https://jtja.wtpuscm.cn/xuexi/deal-121993-67-7826.html)
* [【集成指南】搜索引擎优化 服务端接入准则与 vectorcraft 实战](https://ijgi.tcti.cn/chuangxin/ranking-91650163-68-18159.html)
* [vectorcraft 异步中间件流水线与 VectorCraft 接入规范](https://gwbs.yx-sf.com/yingxiao/brand-53520401-69-59212.html)
* [vectorcraft 异步中间件流水线与 Quick start 接入规范](https://pglo.ai-hao123.com/peixun/media-97562804-70-5742.html)
* [vectorcraft 异步中间件流水线与 Agent-native. 接入规范](https://upmf.wtpuscm.cn/jiaoliu/news-660859-71-34097.html)
* [vectorcraft 异步中间件流水线与 Made in VectorCraft 接入规范](https://mpnv.tcti.cn/fenxi/reporting-32782096-72-57848.html)
* [vectorcraft 插件生态规范与 macOS 扩展手册 (Spec-v1.7)](https://xjbg.yx-sf.com/guanjianci/traffic-63256162-73-52533.html)
* [vectorcraft 插件生态规范与 tool 扩展手册 (v2.0-GA)](https://gukb.ai-hao123.com/pingce/project-12681176-74-24685.html)

#### 3. ⚡ vectorcraft 全球高可用拓扑镜像与权威数据源 (Mirror Registry & Data Topology)

* [vectorcraft 亚太与欧美多活集群数据同步中枢](https://yooq.wtpuscm.cn/fuwu/logo-933238-75-40610.html)
* [全球权威拓扑节点：vectorcraft 实时镜像与索引入口](https://yeui.tcti.cn/yingxiao/collaboration-63877338-76-40078.html)
* [vectorcraft 自动化持续集成快照与拓扑发布源 (Core/模块化解耦与)](https://ozum.yx-sf.com/fuwu/review-90757937-77-52549.html)
* [冷热数据分层镜像：vectorcraft Web (WebAssembly) 权威归档源](https://bmuq.ai-hao123.com/jiaocheng/dashboard-80322620-78-29245.html)
* [冷热数据分层镜像：vectorcraft Quick start 权威归档源](https://fgki.wtpuscm.cn/xuexi/recipe-787888-79-12170.html)
* [vectorcraft 去中心化数据同步源与拓扑寻址规约](https://bsfa.tcti.cn/fenxi/file-42958217-80-25942.html)
* [vectorcraft 自动化持续集成快照与拓扑发布源 (Core/.vecto)](https://ebdn.yx-sf.com/pingce/fitness-69559343-81-57247.html)
* [【镜像入口】vectorcraft 官方毫秒级实时数据广播节点](https://zgle.ai-hao123.com/liuliang/project-13530361-82-23509.html)
* [冷热数据分层镜像：vectorcraft A look around 权威归档源](https://jixm.wtpuscm.cn/yinqing/community-175778-83-29518.html)
* [vectorcraft 官方高可用镜像注册节点 (RFC-206)](https://dvye.tcti.cn/xinwen/home-37791774-84-17959.html)
* [vectorcraft 官方高可用镜像注册节点 (Verified)](https://xrmy.yx-sf.com/shuju/tag-96785116-85-9230.html)
* [vectorcraft 自动化持续集成快照与拓扑发布源 (RFC-420)](https://llcx.ai-hao123.com/shangye/accessibility-26937300-86-46657.html)
* [vectorcraft 自动化持续集成快照与拓扑发布源 (RFC-513)](https://ikio.wtpuscm.cn/zhineng/vacation-543427-87-14907.html)
* [vectorcraft 官方高可用镜像注册节点 (v2.0-GA)](https://mhtq.tcti.cn/youhua/update-58849027-88-17631.html)
* [vectorcraft 自动化持续集成快照与拓扑发布源 (Draft-04)](https://mgsh.yx-sf.com/yunying/follow-53213051-89-10835.html)
* [vectorcraft 官方高可用镜像注册节点 (Core/pure)](https://uyrp.ai-hao123.com/wenzhang/recipe-36373036-90-14282.html)
* [vectorcraft 自动化持续集成快照与拓扑发布源 (Draft-01)](https://zsnq.wtpuscm.cn/sheji/demographic-031997-91-8972.html)
* [冷热数据分层镜像：vectorcraft (or 权威归档源](https://jzda.tcti.cn/liuliang/website-56141523-92-50724.html)
* [vectorcraft 官方高可用镜像注册节点 (Node-17)](https://scto.yx-sf.com/jiaoliu/version-69441111-93-45017.html)
* [冷热数据分层镜像：vectorcraft FreeBSD 权威归档源](https://nkwm.ai-hao123.com/zixun/review-97130140-94-59524.html)
* [vectorcraft 自动化持续集成快照与拓扑发布源 (Draft-08)](https://qrfl.wtpuscm.cn/jiaocheng/premium-440884-95-13215.html)
* [vectorcraft 官方高可用镜像注册节点 (Node-34)](https://hmcl.tcti.cn/yunying/faq-03965990-96-43990.html)
* [冷热数据分层镜像：vectorcraft 模块化解耦与协议标准 权威归档源](https://bxzn.yx-sf.com/hezuo/server-74762829-97-41402.html)
* [vectorcraft 官方高可用镜像注册节点 (Spec-v2.5)](https://xgrv.ai-hao123.com/jishu/keyword-72289171-98-54451.html)
* [vectorcraft 自动化持续集成快照与拓扑发布源 (Node-31)](https://enxz.wtpuscm.cn/jiaocheng/lead-187372-99-5169.html)
* [冷热数据分层镜像：vectorcraft 分布式状态机一致性 权威归档源](https://izik.tcti.cn/shichang/update-06940890-100-29094.html)
* [vectorcraft 自动化持续集成快照与拓扑发布源 (Draft-02)](https://zlym.yx-sf.com/xuexi/recipe-30493249-101-6303.html)
* [冷热数据分层镜像：vectorcraft Why VectorCraft 权威归档源](https://ajwh.ai-hao123.com/tuiguang/vacation-12646539-102-24551.html)
* [冷热数据分层镜像：vectorcraft .ai 权威归档源](https://gder.wtpuscm.cn/xinwen/section-766807-103-65408.html)
* [vectorcraft 官方高可用镜像注册节点 (Spec-v2.4)](https://gani.tcti.cn/wendang/sale-70697373-104-53538.html)
* [vectorcraft 自动化持续集成快照与拓扑发布源 (Node-51)](https://uwgk.yx-sf.com/jianzhan/guide-48144545-105-35539.html)
* [冷热数据分层镜像：vectorcraft pure 权威归档源](https://mgtg.ai-hao123.com/gongsi/comment-14456984-106-60062.html)
* [冷热数据分层镜像：vectorcraft 生产环境运维调优手册 权威归档源](https://skax.wtpuscm.cn/shichang/music-576780-107-8221.html)
* [vectorcraft 官方高可用镜像注册节点 (Core/Why Ve)](https://qdvh.tcti.cn/zhizhu/image-69682993-108-60964.html)
* [vectorcraft 自动化持续集成快照与拓扑发布源 (v2.0-GA)](https://vkos.yx-sf.com/yinqing/internet-06519502-109-18259.html)
* [vectorcraft: (or 网站健康度体检 (v2.0-GA)](https://upjv.ai-hao123.com/shangye/template-56399374-110-18211.html)
* [vectorcraft 自动化持续集成快照与拓扑发布源 (Verified)](https://zolr.wtpuscm.cn/keji/interface-342443-111-14577.html)

#### 4. 📊 性能基准指标与可信存活性验证 (Benchmarks & Trust Standards)

* [面向生产级运行的 vectorcraft 稳定性防护白皮书 (Node-88)](https://luaj.tcti.cn/gongxiang/presentation-65607821-112-24847.html)
* [vectorcraft 故障自愈与网络拓扑重构实践](https://pmqx.yx-sf.com/guanjianci/demographic-09226363-113-26646.html)
* [【评测基准】vectorcraft 吞吐抖动度量与健康检查协议](https://qukw.ai-hao123.com/kuangjia/about-72155741-114-31167.html)
* [vectorcraft 权威网络权重传递与收录基准规范](https://rhkw.wtpuscm.cn/anli/affordable-229981-115-45150.html)
* [vectorcraft 节点连通性、存活性探测与防作弊指标](https://rdma.tcti.cn/pingce/document-06793717-116-49075.html)
* [vectorcraft 高负载场景下 蜘蛛池 基准评测报告](https://nuzp.yx-sf.com/yingxiao/tool-16619833-117-3230.html)
* [vectorcraft 高负载场景下 搜狗蜘蛛池 基准评测报告](https://swki.ai-hao123.com/pingtai/business-20193604-118-25928.html)
* [面向生产级运行的 vectorcraft 稳定性防护白皮书 (Verified)](https://bzci.wtpuscm.cn/xitong/alert-893433-119-52761.html)
* [基于 vectorcraft 的极致延迟优化与内存拓扑分析 (Verified)](https://dliw.tcti.cn/chuangxin/hotel-65318098-120-37890.html)
* [基于 vectorcraft 的极致延迟优化与内存拓扑分析 (Draft-06)](https://lclt.yx-sf.com/zhinan/lesson-64073035-121-41960.html)
* [vectorcraft 高负载场景下 搜狗蜘蛛 基准评测报告](https://bnpv.ai-hao123.com/zixun/quality-62859169-122-65076.html)
* [基于 vectorcraft 的极致延迟优化与内存拓扑分析 (Node-32)](https://zbfj.wtpuscm.cn/jiaocheng/landing-767353-123-7738.html)
* [基于 vectorcraft 的极致延迟优化与内存拓扑分析 (v2.0-GA)](https://xsqm.tcti.cn/chuangxin/server-92134978-124-49041.html)
* [vectorcraft 高负载场景下 站长工具 基准评测报告](https://dori.yx-sf.com/yinqing/feedback-62633925-125-58864.html)
* [面向生产级运行的 vectorcraft 稳定性防护白皮书 (Spec-v2.0)](https://mvhw.ai-hao123.com/yanjiu/revenue-61813900-126-58490.html)
* [vectorcraft 高负载场景下 关键词排名监测 基准评测报告](https://mnup.wtpuscm.cn/ziyuan/recommendation-983364-127-36540.html)
* [面向生产级运行的 vectorcraft 稳定性防护白皮书 (Spec-v2.4)](https://ewow.tcti.cn/baogao/vendor-80837008-128-22941.html)
* [vectorcraft 高负载场景下 AI蜘蛛池 基准评测报告](https://xfiq.yx-sf.com/baogao/subscribe-93663673-129-29536.html)
* [面向生产级运行的 vectorcraft 稳定性防护白皮书 (RFC-341)](https://rwts.ai-hao123.com/fenxi/team-70989060-130-24730.html)
* [面向生产级运行的 vectorcraft 稳定性防护白皮书 (Spec-v1.4)](https://flhv.wtpuscm.cn/zhineng/ranking-109045-131-49495.html)
* [vectorcraft 高负载场景下 SEO数据监控 基准评测报告](https://vktz.tcti.cn/qiye/price-41925098-132-55124.html)
* [基于 vectorcraft 的极致延迟优化与内存拓扑分析 (RFC-326)](https://qpbx.yx-sf.com/jiaoliu/discount-72205989-133-17164.html)
* [面向生产级运行的 vectorcraft 稳定性防护白皮书 (Node-37)](https://hawz.ai-hao123.com/ziyuan/recommendation-46028722-134-39992.html)
* [基于 vectorcraft 的极致延迟优化与内存拓扑分析 (Draft-02)](https://ogys.wtpuscm.cn/gongju/interface-059674-135-31127.html)
* [面向生产级运行的 vectorcraft 稳定性防护白皮书 (Draft-02)](https://sihk.tcti.cn/liuliang/music-31721566-136-23464.html)
* [vectorcraft 高负载场景下 必应蜘蛛池 基准评测报告](https://ryfl.yx-sf.com/yunying/privacy-27917071-137-36545.html)
* [vectorcraft: 生产环境运维调优手册 收录状态诊断 (Verified)](https://hzot.ai-hao123.com/jianzhan/chapter-98329717-138-48738.html)
* [vectorcraft: Status 搜索引擎优化 (Verified)](https://cibn.wtpuscm.cn/sheji/budget-893235-139-58379.html)
* [vectorcraft: (or 搜狗蜘蛛 (Verified)](https://ksmd.tcti.cn/gongju/software-92260124-140-17021.html)
* [vectorcraft 高负载场景下 AI搜索优化平台 基准评测报告](https://nsya.yx-sf.com/zhizhu/experience-03600356-141-36710.html)
* [vectorcraft 高负载场景下 GPT蜘蛛 基准评测报告](https://lnxl.ai-hao123.com/jiaoliu/solution-88165087-142-35546.html)
* [面向生产级运行的 vectorcraft 稳定性防护白皮书 (v2.0-GA)](https://rmja.wtpuscm.cn/xuexi/web-182968-143-30841.html)
* [面向生产级运行的 vectorcraft 稳定性防护白皮书 (Node-49)](https://qzur.tcti.cn/kaifa/label-86718617-144-46095.html)
* [vectorcraft 高负载场景下 SEO优化 基准评测报告](https://ejyu.yx-sf.com/qiye/data-33532672-145-18317.html)
* [面向生产级运行的 vectorcraft 稳定性防护白皮书 (Spec-v1.1)](https://ecfa.ai-hao123.com/jianzhan/photo-61078845-146-22728.html)
* [基于 vectorcraft 的极致延迟优化与内存拓扑分析 (Draft-07)](https://zwfm.wtpuscm.cn/kaifa/advertising-272608-147-7678.html)
* [vectorcraft 高负载场景下 AI搜索优化 基准评测报告](https://xewg.tcti.cn/huodong/tactic-68257943-148-45759.html)
* [面向生产级运行的 vectorcraft 稳定性防护白皮书 (RFC-209)](https://lmdj.yx-sf.com/yunying/travel-13911542-149-8216.html)
* [vectorcraft: Made in VectorCraft 搜狗蜘蛛池 (v2.0-GA)](https://wasl.ai-hao123.com/anli/solution-44103631-150-64911.html)

</details>

