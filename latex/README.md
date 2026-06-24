# Final written report (LaTeX)

Source for the CSIE 116 (HCI / HAX) report **"Parting Is a Sweet Sorrow:
An Ambient Co-Presence Space for Friendships Drifting Apart in Young Adulthood."**

Built from the two team decks in `../presentation/` (`First.pdf` = motivation /
literature; `Second.pdf` = proposal / design / evaluation).

## Files

- `main.tex` — the report (motivation w/ ABT, background, related work, design
  concept, RQs, evaluation plan, McGee 8-question self-assessment, contributions).
- `references.bib` — bibliography (natbib / `plainnat`).
- `Makefile` — one-command build.

## Build

Needs **XeLaTeX** (used so the Chinese author names render via the macOS system
font *PingFang TC*).

```sh
make          # -> main.pdf
# or:
latexmk -xelatex main.tex
```

`make clean` removes build artifacts.

## Notes

- Engine is XeLaTeX because of `xeCJK` + `\setCJKmainfont{PingFang TC}`. On a
  non-macOS box, change that font to any installed CJK font (e.g. `Noto Serif CJK
  TC`), or comment out the two `xeCJK` lines in `main.tex` (author names then fall
  back / may show as boxes).
- Section coloring is done with a kernel `\@startsection` override (no `titlesec`
  needed — this TeX install is minimal/BasicTeX).
- Built and verified clean against TeX Live 2026 (basic). Only warning is a benign
  "italic shape of PingFang TC undefined" font note.
