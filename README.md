# dm — feuille de devoirs maison

Feuille de devoirs maison (DM) — exercices numériques avec énoncés et
solutions (basée sur les DM M1 : TNP, points extrêmes, thèmes).

## Contents

| Document | Kind | Notes |
| --- | --- | --- |
| `src/main.tex` | DM sheet (`article`) | Title, TOC, imports `dm_content.tex`. |
| `src/dm_content.tex` | DM body | Imports `dm_1.tex`, `dm_2.tex`. |
| `src/dm_1.tex` | DM 1 — Complexité | Complexity of graphs. |
| `src/dm_2.tex` | DM 2 — DP theme | Dynamic programming theme. |

Solutions are shown when the `showsolutions` toggle is on (see `src/main.tex`).

## Use

```sh
latex_handler new mon_dm --template dm
cd mon_dm
latex_handler compile
latex_handler compile --theme all
```

## Assets

Shared tree in `assets/`: `base_header`, `math`, `environments`, `tikz`,
`themes/more_colours`.
