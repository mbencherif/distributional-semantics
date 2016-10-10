# Distributional Semantics
Distributional Semantics with Random Indexing

Optional LSA-like vectors (vocabulary*vocabulary co-occurrence matrix), no dimensionality reduction as of yet.

CBOW to determine contexts. Default sliding window size is 1, can be changed.

Commands:
* "sim <word> <word>" similarity between two words
* "top <word>" top 3 similar words
* "lsasim <word> <word>" LSA-like similarity between two words
* "info" information about the data
* "info <word>" information about a word
* "save <name>" save current data
* "load <name>" to load saved data
* "update <path>" update current data with a new data
