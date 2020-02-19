# Bigram-Language-Model

This program reads in a training set to create a word-word co-occurrence matrix with bigram probabilities.
It can then be used to calculate the probability, probability normalized by sentence length, and perplexity of a text sentence and generate sentences that are possible, but not most probable.

This program requires two input files:
1) training_set.txt - unstructured text. I used a chapter from the Bible.
2) test_set.txt - a few lines you want to test your language model on separated by newlines.

This programs produces an output file output.txt which prints the probability, the probability normalized by sentence length, and the perplexity of text sentences.

It also prints the sampled sentence along with its probability and perplexity.
