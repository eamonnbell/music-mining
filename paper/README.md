## Paper structure

- musical function and statistical methods
- high-level overview of word2vec
- methodology
- is the embedding space plausible
- result 1: large corpus gives major chords arranged in circle of fifths
  - should also show counterexample
- result 2: when broken out by composer, circle loses distinctiveness
- discussion:
  - of result 1: why should this come about
  - of result 2: discuss confounding factors?
- further work/are there lessons for NLP in musical corpus study?

## Using `latexmk`

- `latexmk -C` clean pwd of all output files
- `latexmk -pdf ycac2vec.tex` create a pdf output
- `latexmk -c` clean pwd of intermediate TeX files leaving .pdf 
- `latexmk -pdf -pvc ycac2vec.tex` watch .tex file for changes and compile when the file changes and open latest output pdf in xpdf

Sections are `\input{}` includes from the contents of the sections/ directory
