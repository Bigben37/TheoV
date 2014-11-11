TheoV
=====
Lecture notes from "Theroetische Physik V - Thermodynamik und Statistik"

Style - Guide
=============

Visual Style
------------
  - units in equations as normal text (use `\text{}`), use a half space between number and dimension (`\,`)
  - total differential `d` with `\textrm{d}` or use command `\difd`
  - `const.` in equations as text, use command `\const` (dot included)
  - Finish captions of images, tables, ... with a `.` (dot).

Words with multiple ways of writing
-----------------------------------
  - Potential
  - Differential

Source Code Style
-----------------
  - Indentation with 4 spaces, all environments are to be indented. 
    Setup for TeXlipse in `Settings->Texlipse->Editor->Indentation`
  - for labes use following identifiers: `eq, img, tab, sec, sub, subsub, par, subpar`

New Commands
------------
Following new commands are provided in the main file `TheoV.tex`:
  - `\difd`: total differential d
  - `\const`: const.
  - `\pd`: partial derivative (`\frac{\partial #1}{\partial #2}`)
  - `\pdi`: partial derivate with constant variables (`\left( \pd{#1}{#2} \right)_{#3}`)

Templates
---------
Templates for Eclipse can be found in `./templates/`. Currently there are templates for:
  - `eq`: equation environment
  - `eqs` equation environment with split environment
  - `int`: integral with borders
  - `sum`: sum with borders
  - `br`: round braces
  - `matrix`: pmatrix environment
  - `text`: text in math mode
