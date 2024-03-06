# Makemore

Makemore is an AI project where i aim to deepen my understanding of the different approaches in language models. In a nutshell makemore takes one text file as input, where each line is assumed to be a training sample and generates more things like it.

In the first place we started by building a simple Bigram Language Model for the previouse mentioned porpouses. In a Bigram Language Model, we find bigrams, which are two words coming together in the corpus(the entire collection of words/sentences). To build this model we followed to approaches with the same exact results, first of all with a look-up table that stored the relative frequencies for all the bigrams and also a simple one-layered neural network model.
