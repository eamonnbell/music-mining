Use `latexmk`

- `latexmk -C` clean pwd of all output files
- `latexmk -pdf ycac2vec.tex` create a pdf output
- `latexmk -c` clean pwd of intermediate TeX files leaving .pdf 
- `latexmk -pdf -pvc ycac2vec.tex` watch .tex file for changes and compile when the file changes and open latest output pdf in xpdf

Sections are `\input{}` includes from the contents of the sections/ directory
