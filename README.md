# NLP
Welcome to the Natural Language Processing (NLP) Repository! This repository is dedicated to providing a comprehensive collection of resources, tools, and examples to help us get started with NLP and to advance your skills in this exciting field.

Terminologies in NLP
  1. Corpus - paragraph (combination of all the sentences)
  2. Documents - sentences
  3. Vocabulary - total number of unique words
  4. words - words in the sententece
     
Important steps involved:
I. Text Cleaning
  1. Tokenization: breaking the sentences into words
  2. Stopword removal
  3. Stemming: coverting the words into root / base word, may or maynot be meaningful
       - It is really fast in terms of text processing but it removes the meaning of the word
       - use cases: spam classification, review classification
  5. Lemmatization: convert the word into the meaningful word.
       - It gives meaningful words but it is slow
       - use case: text summarization, language translation, chatbots etc
         
II. Convert Words to Vectors
  1. OHE (One hot encoding)
       Advantage: Simple to implement and intuitive
       Disadvantage: 1. create a really sparse matrix 2. it also create an issue of out of vocabulary (can not handle if an) 3. Not fixed size 4. semantic meaning between words is not                                      captured
  3. BOW (Bag of words)
       Advantage: Simple and intuitive
       Disadvantage: 1. Sparsity 2. Out of Vocabulary 3. Ordering of words will change 4. semantic meaning will be lost
  4. Ngrams (bigram, trigram, .., ngram)
  5. TF-IDF (Term frequency - Inverse document frequency
  6. Word2Vec 


     
