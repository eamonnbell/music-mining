# music-mining

Borrowing new techniques from NLP and stat learning to attack music

Eamonn Bell <epb2125@columbia.edu>, Jaan Altosaar <altosaar@princeton.edu>

## word2vec on reduced chord tokens

### Process YCAC.ipynb

Parse the [Yale Classical Archives Corpus](http://ycac.yale.edu/downloads) (not included in the repo) into binary pitch-class tokens (e.g. <100100000000> = {C, E}) and join to metadata for binning by date of composition.

## PCA plots from YCAC files.ipynb

Train word embedding models for main corpus and subcorpora and perform dimensionality reduction
