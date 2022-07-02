
README.txt
Initially prepared by C. Pinon (cjpinon@implicature.xyz) for EISS 13 (see
https://implicature.xyz/eiss13/)
2020-12-30 v3.2a
2020-02-02 v3.2
Modified by B. Crysmann and G. Schaden for EISS 14.
2022-07-02 v. 3.3


This is a LaTeX template package for EISS, for either pdflatex, xelatex or
lualatex as the typesetting engine (we recommend the use of xelatex). As of EISS 14, latex with dvi output is no longer supported. 

This package consists of 11 files:

README.txt
lppl.txt
eiss.sty
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

eiss13_logo_blank.pdf is a file containing a blank logo. It is inserted by AUTHOR_master.tex. It may be easiest to keep this file in the same
directory as your TEX files.

gl-authoryear-comp.cbx and biblatex-gl.bbx are biblatex style files from the journal Glossa (see https://www.glossa-journal.org/). They provide the bibliographic style that you should use. These files are also available at:

https://github.com/guidovw/Glossalatex

(The files is included as a convenience. It is not clear what their license
is.)

main.tex, AUTHOR_body.tex, AUTHOR_refs.tex, AUTHOR_bib.bib --
these four files are to be edited for your paper:

  - main.tex is the file in which you set 12 parameters for your
  paper, as well as for loading any additional packages that you
  need. Please follow the instructions in it (it's intended to be
  self-explanatory). This is the file that you compile. The name has been choses for ease of integration with Overleaf. While you work
  on Overleaf, do not rename it (but before submitting, change its
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
unicode-aware TeX engine, such as xelatex, but pdflatex is still supported. You can then directly use a wide range of Latin, Greek, and Cyrillic characters in your document, as well as the IPA.

Before sending the source files for your paper to the editors, please
make certain that you've paid attention to the points mentioned at
https://implicature.org/eiss14/latex_bibtex_advice .

If you have any questions, please don't hesitate to ask. Happy LaTeXing!
