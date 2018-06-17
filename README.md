# Ngram_sentgen
Computes N-gram frequency from text and generate a sentence based on the probabilties of a word coming after an N-gram.

First strips a text document of punctuation and then divides it into sentences in the form of a list.

Then it takes the list of sentences and converts it into a list of words or tokens.

The function <span style="color:blue"> ngram </span> returns a list of tuples consisting of (ngram, following word, frequency), and then sorts
them based on alphabetical order.

From this a matrix is then compiled, and then sentences are generated based on probabilities and input phrases/words.


