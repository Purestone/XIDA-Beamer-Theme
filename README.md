# XIDA Beamer Theme

An unofficial University of Sydney-inspired Beamer theme adapted from [SUDA Beamer Theme](https://github.com/ymliucs/SUDA-Beamer-Theme) by Yumeng Liu, itself based on [THU Beamer Theme](https://www.overleaf.com/latex/templates/thu-beamer-theme/vwnqmzndvwyb).

[View the example presentation](preview.pdf).

## Features

- 4:3 slides with flat ochre (`#E74726`) navigation and title bars.
- Times New Roman text, section navigation, and a school name / page number footer.
- Examples of lists, blocks, mathematics, theorems, tables, and references.

## Build

Install a TeX distribution with XeLaTeX and install Times New Roman separately. Run `xelatex main.tex` twice. Edit `main.tex` to make your presentation. For a new presentation copy `xida.sty` and `figs/` and use:

```latex
\documentclass[aspectratio=43]{beamer}
\usepackage{xida}
```

Text uses Times New Roman; mathematical symbols use the available TeX math fonts.

## Colours

| Name | Hex |
| --- | --- |
| `ochre` | `#E74726` |
| `MasterbrandBlack` | `#0A0A0A` |
| `MasterbrandCharcoal` | `#424242` |
| `MasterbrandWhite` | `#FFFFFF` |

## Attribution and branding

The source SUDA template is published on [Overleaf](https://www.overleaf.com/latex/templates/suda-beamer-theme/zrrdkvxkktjr) under CC BY 4.0. This adaptation credits its author and records its changes above. The theme and original example content in this repository are shared under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), excluding third-party trademarks and assets. The shield is cropped from a vector logo available in a local University of Sydney thesis template. University names and logos remain the property of their respective owners; their use is subject to applicable branding rules. This project is not affiliated with or endorsed by the University of Sydney.
