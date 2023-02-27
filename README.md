## How to use it


Compile file thesis.tex once or twice with LualaTex. If references are modified, additionally compile thesis.aux with BibTex, then compile thesis.tex once or twice again with LualaTex.

## Origin of this template

Matheus Schossler adapted this template in February 2023 based on Liang-Bo Wang GitHub [repo](https://github.com/ccwang002/wustl-latex-dissertation-template/). Liang-Bo Wang's version (2022) is based on Kyle J. Harms (`@harmsk`)'s GitHub [repo](https://github.com/harmsk/wustl-latex-dissertation-template/tree/f5386bb93dee6e5c0c5b1faed317b687be0f199a).

These are the adaptations compared to Liang-Bo Wang's version (2022):

- Removed emoji package: as of this date emaji.sty is not included in apt tex-live installation (may concern Linux users).
- Removed microtype option "disable=false"
- Removed biblatex package
- Added babel package and \bibliographystyle{ieeetr}


