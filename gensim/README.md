## gensim/

Doing word2vec on reduced chords. Uses `gensim`. This was the repo used to generate results for the presentation at the Machine Learning for Music Discovery Workshop at ICML 2016. This code is deprecated in favor of an implementation in TensorFlow. See ../tf/ for more. The corpus parsing code for TensorFlow models will be necessarily different, but the corpus parsing code here is made avaialable for completeness.

### Requirements 

- gensim
- scikit-learn
- music21
- more...

### Process YCAC.ipynb

Parse the [Yale Classical Archives Corpus](http://ycac.yale.edu/downloads) (not included in the repo) into binary pitch-class tokens (e.g. <100010000000> = {C, E}) and join to metadata for binning by date of composition.

### PCA plots from YCAC files.ipynb

Train word embedding models for main corpus and subcorpora and perform dimensionality reduction

### Word Mover's Distance on a specially-trained model.ipynb

Show how WMD improves classifier performance over baseline cosine distance between pieces represented as bag-of-words features.