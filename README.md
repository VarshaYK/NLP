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
     
  3. Stopword removal
     
  5. Stemming: coverting the words into root / base word, may or maynot be meaningful
     
       - It is really fast in terms of text processing but it removes the meaning of the word
       - use cases: spam classification, review classification
         
  6. Lemmatization: convert the word into the meaningful word.
     
       - It gives meaningful words but it is slow
       - use case: text summarization, language translation, chatbots etc
    
Word Embeddings 


    1. Count or frequency
        a. OHE (One hot encoding)
        b. BOW (Bag of words)
        c. TF-IDF (Term frequency - Inverse document frequency)
      
    2. Deep learning Model
        a. Word2Vec
            i. CBOW (continuous bag of words)
            ii. Skip Gram
         
II. Convert Words to Vectors


  1. OHE (One hot encoding)
     
       Advantage:
           1. Simple to implement and intuitive
     
       Disadvantage:
           1. create a really sparse matrix
           2. it also create an issue of out of vocabulary (can not handle if an)
           3. Not fixed size
           4. semantic meaning between words is not                                      captured
    
  3. BOW (Bag of words)
     
       Advantage:
           1. Simple and intuitive
     
       Disadvantage:
           1. Sparsity
           2. Out of Vocabulary
           3. Ordering of words will change
           4. semantic meaning will be lost
     
  5. Ngrams (bigram, trigram, .., ngram)
     
  7. TF-IDF (Term frequency - Inverse document frequency)

       Advantage:
           1.Intuitive
           2. Word importance is getting captured

     Disadvantage:
           1. Sparsity
           2. Out of vocabulary

  8. Word2Vec
     
     It represents each and every feature (word) as a vector of limited dimensions. It captures semantic and syntactic relationships between words based on their co-occurrence patterns in a large corpus of text.

     
       a. CBOW - continuous bag of words
     
       b. skip gram


     Key Takeaways:

     
         1. Word2Vec learns word embeddings, dense vector representations of words.
         2. sparsity is reduced
         3. It analyzes co-occurrence patterns in a text corpus to capture semantic relationships.
         4. Word embeddings enable word similarity calculations.
         5. They can be used as features in various NLP tasks.
         6. Word2Vec requires a large training corpus for accurate embeddings.
         7. It does not capture word sense disambiguation.
         8. Word order is not considered in Word2Vec.
         9. Out-of-vocabulary words may pose challenges.
         10. Despite limitations, Word2Vec has significant applications in NLP.
     


     
