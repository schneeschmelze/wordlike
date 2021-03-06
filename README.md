# wordlike

## Overview 

This is LaTeX package 'wordlike' for simulating word
processor layout. The package consists of these files:

* wordlike.ins
* wordlike.dtx
* README.md
* wordlike.pdf

These packages are REQUIRED for running 'wordlike':
courier, geometry, helvet, mathptmx.
They are usually installed on a TeX system.

## Installation 

is done in six steps:

 1. move wordlike.ins and wordlike.dtx into the same directory
 2. call latex wordlike.ins -> generates wordlike.sty
 3. call latex wordlike.dtx twice -> generates user guide wordlike.dvi/ *.pdf
 4. move wordlike.sty to texmf-local/tex/latex/wordlike
 5. move wordlike.dvi to texmf-local/doc/latex/wordlike
 6. call mktexlsr/texhash for updating TeX's file name database

## Changes 

 v1.2a  2006/03/29  Broken v1.1 on CTAN replaced by fixed local v1.2a
                    Hint to the arial package added

## Copying 

This is free software. The latest version of the LPPL is
applicable to all parts of this package. Please see

  http://www.latex-project.org/lppl.txt

for details.

Keep TeXing! ;-) 

Juergen Fenn, 
29 March 2006 / 21 April 2018
