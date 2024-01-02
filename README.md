# CSSP Proceedings

A LaTeX template package for EISS, for either pdflatex, xelatex or lualatex as the typesetting engine (we recommend the use of lualatex). As of EISS 14, latex with dvi output is no longer supported. 

This package consists of 12 files:
- README.md
- lppl.txt
- eiss.sty
- cgloss.sty
- eiss15_logo_blank.pdf
- cat.png
- gl-authoryear-comp.cbx
- biblatex-gl.bbx
- main.tex
- AUTHOR_body.tex
- AUTHOR_bib.bib
- main.pdf


*lppl.txt* contains the package license (the LaTeX Project Public License Version 1.3c).

*eiss.sty* is the LaTeX style file for EISS 15. Please do not modify it.

*cgloss.sty* is a LaTeX style file for glossing. Please do not modify it.

*eiss15_logo_blank.pdf* is a file containing a blank logo. It is inserted by main.tex. 
It may be easiest to keep this file in the same directory as your TEX files.

*cat.png* provides a sample cat picture demonstrating how images can be included. This file can 
safely be removed, and should not be resubmitted.

*gl-authoryear-comp.cbx* and *biblatex-gl.bbx* are biblatex style files from the journal Glossa (see https://www.glossa-journal.org/). They provide the bibliographic style that you should use. These 
files are also available at:

https://github.com/guidovw/Glossalatex

(These files are included as a convenience. It is not clear what their license is.)

## Usage 

*main.tex*, *AUTHOR_body.tex* and *AUTHOR_bib.bib* are the files to be edited for your paper:

- main.tex is the file in which you set 11 parameters for your
  paper, as well as for loading any additional packages that you
  need. Please follow the instructions in it (it's intended to be
  self-explanatory). This is the file that you compile. The name has 
  been chosen for ease of integration with Overleaf. While you work
  on Overleaf, do not rename it (but before submitting, change its
  name to "AUTHOR_main" with your last name, e.g.,
  roussarie_main.tex).

- AUTHOR_body.tex is the file for the body of your paper. This is
  where you should write your main text. It's also advised to rename
  this file (by replacing "AUTHOR" with your last name).

- AUTHOR_bib.bib will contain your bibliographical references. 
  You can input utf-8 directly.

We encourage the use of unicode. For that, please make sure your source files use UTF-8 encoding. 
To compile your document, you should use a unicode-aware TeX engine, such as xelatex or lualatex, 
but pdflatex is still supported. You can then directly use a wide range of Latin, Greek, and 
Cyrillic characters in your document, as well as the IPA.

Before sending the source files for your paper to the editors, please make certain that you've paid 
attention to the points mentioned at https://implicature.org/eiss14/latex_bibtex_advice, and which remain valid for EISS 15.

If you have any questions, please don't hesitate to ask. Happy LaTeXing!

## Changelog

- Created by Christopher Piñon for EISS 13
- Modified by Gerhard Schaden & Berthold Crysmann for EISS 14
- Modified by Gerhard Schaden for EISS 15
