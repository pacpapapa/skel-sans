# Skel Sans

[Traditional Chinese](README-zh.md)

Skel Sans is an open-source, generative CJK variable typeface built from medial-axis skeletons of [Noto Sans CJK](https://github.com/notofonts/noto-cjk). Instead of directly editing the original outlines, Skel Sans procedurally reconstructs glyphs as geometric strokes, creating a monolinear system that varies continuously in weight, width, and slant.

Designed and developed by [Yuhao Chang](https://yuh4o.tw/).

![Thumbnail](./images/thumbnail1.png)
![Thumbnail](./images/thumbnail2.png)

## Features

- Four visual profiles: `Vanilla`, `Claw`, `Wiggle`, and `Zigzag`
- Three variation axes: weight (`wght`), width (`wdth`), and slant (`slnt`)
- 65,535 glyphs, with more than 65,000 generated from skeletons
- Geometry-driven, monolinear construction
- OTF (CFF2) and TTF (glyf/gvar) formats
- Licensed under the SIL Open Font License 1.1

| Axis   | Tag    |       Range | Default |
| ------ | ------ | ----------: | ------: |
| Weight | `wght` |  100 to 900 |     100 |
| Width  | `wdth` | 62.5 to 150 |     100 |
| Slant  | `slnt` |    -15 to 0 |       0 |

## Download

All files are hosted as assets on the [Releases page](https://github.com/pacpapapa/skel-sans/releases). The links below always point to the latest release.

OTF and TTF builds of the same profile share the same system font names. Install only one format at a time to avoid duplicate-font conflicts. If you are unsure which format to choose, start with OTF, especially when working in Adobe applications.

### Full Version

The Full version includes all three variation axes: weight, width, and slant.

| Vanilla | Claw | Wiggle | Zigzag |
| :---: | :---: | :---: | :---: |
| [OTF（489 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansVanilla-VariableFont_wght,wdth,slnt.otf)<br>[TTF（446 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansVanilla-VariableFont_wght,wdth,slnt.ttf) | [OTF（850 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansClaw-VariableFont_wght,wdth,slnt.otf)<br>[TTF（851 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansClaw-VariableFont_wght,wdth,slnt.ttf) | [OTF（609 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansWiggle-VariableFont_wght,wdth,slnt.otf)<br>[TTF（568 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansWiggle-VariableFont_wght,wdth,slnt.ttf) | [OTF（872 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansZigzag-VariableFont_wght,wdth,slnt.otf)<br>[TTF（817 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansZigzag-VariableFont_wght,wdth,slnt.ttf) |

### Lite Versions

Each visual profile also comes in six smaller builds with one or two variable axes. Omitted axes are fixed at their default values.

The `fontFamily` suffix indicates which axes remain variable: `W` = weight (`wght`), `D` = width (`wdth`), and `S` = slant (`slnt`).

| Suffix | Vanilla | Claw | Wiggle | Zigzag |
| ---: | :---: | :---: | :---: | :---: |
| WD | [OTF（255 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansVanillaWD-VariableFont_wght,wdth.otf)<br>[TTF（262 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansVanillaWD-VariableFont_wght,wdth.ttf) | [OTF（454 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansClawWD-VariableFont_wght,wdth.otf)<br>[TTF（482 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansClawWD-VariableFont_wght,wdth.ttf) | [OTF（325 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansWiggleWD-VariableFont_wght,wdth.otf)<br>[TTF（335 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansWiggleWD-VariableFont_wght,wdth.ttf) | [OTF（464 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansZigzagWD-VariableFont_wght,wdth.otf)<br>[TTF（461 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansZigzagWD-VariableFont_wght,wdth.ttf) |
| WS | [OTF（188 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansVanillaWS-VariableFont_wght,slnt.otf)<br>[TTF（180 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansVanillaWS-VariableFont_wght,slnt.ttf) | [OTF（332 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansClawWS-VariableFont_wght,slnt.otf)<br>[TTF（319 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansClawWS-VariableFont_wght,slnt.ttf) | [OTF（232 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansWiggleWS-VariableFont_wght,slnt.otf)<br>[TTF（216 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansWiggleWS-VariableFont_wght,slnt.ttf) | [OTF（328 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansZigzagWS-VariableFont_wght,slnt.otf)<br>[TTF（299 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansZigzagWS-VariableFont_wght,slnt.ttf) |
| DS | [OTF（246 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansVanillaDS-VariableFont_wdth,slnt.otf)<br>[TTF（237 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansVanillaDS-VariableFont_wdth,slnt.ttf) | [OTF（451 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansClawDS-VariableFont_wdth,slnt.otf)<br>[TTF（423 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansClawDS-VariableFont_wdth,slnt.ttf) | [OTF（313 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansWiggleDS-VariableFont_wdth,slnt.otf)<br>[TTF（294 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansWiggleDS-VariableFont_wdth,slnt.ttf) | [OTF（463 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansZigzagDS-VariableFont_wdth,slnt.otf)<br>[TTF（425 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansZigzagDS-VariableFont_wdth,slnt.ttf) |
| W | [OTF（107 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansVanillaW-VariableFont_wght.otf)<br>[TTF（101 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansVanillaW-VariableFont_wght.ttf) | [OTF（187 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansClawW-VariableFont_wght.otf)<br>[TTF（173 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansClawW-VariableFont_wght.ttf) | [OTF（136 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansWiggleW-VariableFont_wght.otf)<br>[TTF（121 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansWiggleW-VariableFont_wght.ttf) | [OTF（186 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansZigzagW-VariableFont_wght.otf)<br>[TTF（164 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansZigzagW-VariableFont_wght.ttf) |
| D | [OTF（135 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansVanillaD-VariableFont_wdth.otf)<br>[TTF（150 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansVanillaD-VariableFont_wdth.ttf) | [OTF（254 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansClawD-VariableFont_wdth.otf)<br>[TTF（258 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansClawD-VariableFont_wdth.ttf) | [OTF（179 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansWiggleD-VariableFont_wdth.otf)<br>[TTF（186 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansWiggleD-VariableFont_wdth.ttf) | [OTF（261 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansZigzagD-VariableFont_wdth.otf)<br>[TTF（255 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansZigzagD-VariableFont_wdth.ttf) |
| S | [OTF（105 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansVanillaS-VariableFont_slnt.otf)<br>[TTF（99 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansVanillaS-VariableFont_slnt.ttf) | [OTF（191 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansClawS-VariableFont_slnt.otf)<br>[TTF（170 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansClawS-VariableFont_slnt.ttf) | [OTF（132 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansWiggleS-VariableFont_slnt.otf)<br>[TTF（119 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansWiggleS-VariableFont_slnt.ttf) | [OTF（187 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansZigzagS-VariableFont_slnt.otf)<br>[TTF（161 MB）](https://github.com/pacpapapa/skel-sans/releases/latest/download/SkelSansZigzagS-VariableFont_slnt.ttf) |

## Known Limitations

- **Dense glyphs at heavy weights:** In glyphs with many strokes, especially complex CJK ideographs, expanded strokes may overlap or close counters as `wght` increases. This can reduce legibility at the heaviest settings.

  ![Dense Glyphs Issue](./images/limitation_dense-glyphs.png)

- **Source-outline glyphs:** Some enclosed or reversed symbols (such as `❶`, `🅐`, and `🆋`), box-drawing characters (such as `┌`, `┍`, `┡`, and `┟`), and solid geometric symbols (such as `■`, `●`, and `♠`) do not produce useful skeletons. These glyphs retain forms derived from Noto Sans CJK rather than using the Skel Sans stroke construction.

- **TTF behavior in Adobe applications:** TTF builds may render more slowly in Adobe Creative Cloud applications. Some glyphs can also shift vertically by up to approximately 0.002 em at certain variation settings. This application-specific displacement is subtle and does not occur in the OTF builds.

- **Large file sizes:** Skel Sans retains the full 65,535-glyph set of Noto Sans CJK while using roughly 3.5-6.1 times as many outline points per glyph. Variable-font data multiplies that cost across masters. Choose a Lite version when you do not need all three axes.

## Acknowledgements

Skel Sans was made possible by the following open-source typefaces, libraries, and tools:

- [Noto Sans CJK](https://github.com/notofonts/noto-cjk), the source typeface and glyph set
- [flo-mat](https://github.com/FlorisSteenkamp/mat), the medial-axis transform implementation behind the skeleton extraction
- [Paper.js](https://github.com/paperjs/paper.js), used for vector-geometry processing
- [opentype.js](https://github.com/opentypejs/opentype.js), used for reading and parsing OpenType font data
- [fontTools](https://github.com/fonttools/fonttools), used to assemble, subset, and validate the final variable fonts
- Google Antigravity, Claude Code, and OpenAI Codex, which assisted with implementation, testing, and debugging

## License

The Skel Sans font files are licensed under the [SIL Open Font License, Version 1.1](https://openfontlicense.org/). `Skel` is a Reserved Font Name.
