
README.txt
Prepared by C. Pinon (cjpinon@implicature.xyz) for EISS 13 (see
https://implicature.xyz/eiss13/)
2020-12-30 v3.2a
2020-02-02 v3.2
Modified by B. Crysmann and G. Schaden for EISS 14.


This is a LaTeX template package for EISS 13, for either pdflatex or
latex as the typesetting engine.

This package consists of 12 files:

README.txt
lppl.txt
eiss.sty
eiss13_logo_blank.eps
eiss13_logo_blank.pdf
gl-authoryear-comp.cbx
biblatex-gl.bbx
main.tex
AUTHOR_body.tex
AUTHOR_refs.tex
AUTHOR_bib.bib
main.pdf

You're reading README.txt. :-)

lppl.txt contains the package license (the LaTeX Project Public License
Version 1.3c).

eiss.sty is the LaTeX style file for EISS 14. Please do not modify it.

eiss13_logo_blank.[eps|pdf] are two files containing a blank logo. One
of these files is inserted by AUTHOR_master.tex -- the file inserted
depends on whether xelatex or pdflatex (then the PDF version) or latex
+ dvips (then the EPS version) is used to compile
AUTHOR_master.tex. It may be easiest to keep these files in the same
directory as your TEX files.

glossa.bst is a BibTeX style file from the journal Glossa. This is the
BibTeX style file that you should use. This file is also available at:

https://github.com/guidovw/Glossalatex

(This file is included as a convenience. It is not clear what its license
is.)

AUTHOR_master.tex, AUTHOR_body.tex, AUTHOR_refs.tex, AUTHOR_bib.bib --
these four files are to be edited for your paper:

  - main.tex is the file in which you set 12 parameters for your
  paper, as well as for loading any additional packages that you
  need. Please follow the instructions in it (it's intended to be
  self-explanatory). This is the file that you compile. While you work
  on overleaf, do not rename it (but before submitting, change its
  name to "AUTHOR_main" with your last name, e.g.,
  roussarie_main.tex).

  - AUTHOR_body.tex is the file for the body of your paper. This is
  where you should write your main text. It's also advised to rename
  this file (by replacing "AUTHOR" with your last name).

  - AUTHOR_refs.tex is the file that loads your BIB file. Please follow
  the instructions in it. Please also rename this file accordingly. (In
  the case of EXAMPLE_refs.tex, the BIB file loaded is EXAMPLE_bib.bib.)

  - AUTHOR_bib.bib will contain your bibliographical references. 

We encourage use of unicode. For that, please make sure your source
files use UTF-8 encoding. To compile your document, you should use a
unicode-aware TeX engine, such as xelatex. You can then directly use a
wide range of Latin, Greek, and Cyrillic characters in your document,
as well as the IPA.

Before sending the source files for your paper to the editors, please
make certain that you've paid attention to the points mentioned at
https://implicature.org/eiss14/latex_bibtex_advice .

If you have any questions, please don't hesitate to ask. Happy LaTeXing!
