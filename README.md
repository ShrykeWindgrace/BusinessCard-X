BusinessCard-X
==============

This is a template for creating business cards in with XeLaTeX (available in all TeX distributions).
The style follows (mostly) the guidelines of visual style of Ecole Polytechnique.

In order to use the style, install the provided fonts, then modify the file "CarteFinale.tex" accordingly: Given name, Family name, phone, etc.

If you don't want to use the logo of the lab, simply comment the corresponding lines in the *.tex file (see notes in that file).

If want to use another logo:
  put your logo in a format understandable by XeLaTeX in the same folder as *.tex file. PNG, JPG, EPS work well. Say, it has the name "LogoOfYourLab.eps". In the file "CarteFinale.tex" replace the mention of 'LogoCMLSTZ.png' by 'LogoOfYourLab.eps' (without quotes). Adjust the positioning of you image accordingly (see the notes inside the TeX file and the documentation for 'textpos' package).

Afterwards, compile with XeLaTeX. Enjoy.
