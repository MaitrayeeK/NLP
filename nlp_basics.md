# Data preprocessing steps

### Tokenization - Convert sentence into words
### Stopwords - to remove the repeated words like to, of, etc.
### Stemming - process of reducing words to their root word. ex. Going, Goes, Gone -> Go
- Advantage - It is fast
- Disadvantage - Removing the meaning of word
- Usecase - Spam classifier, Review classifier
### Lemmatization - process of reducing words to their meaningful root word
- Advantage - Convert to it meaningful word
- Disadvantage - It is slow
- Usecase - Text summarization, Language translator, ChatBots

### Terminologies in NLP
#### CORPUS - Paragraphs(Combination of all the sentences)
#### Documents - Sentences
#### Vocabulary - Unique words
#### Word

# Conversion of words to vectors

### OHE(One Hot Encoding) 
### Bag of words
- Advantages - Simple
- Disadvantages - Sparsity, Out of vocabulary, Ordering of words, Not able to capture semantic meaning
### TF-IDF(Term Frequency-Inverse Document Frequency)
- TF = No. of word X in sentence / No. of total words in sentence
- IDF = loge(No. of sentences / No. of sentences containing word X)
- TF-IDF of word X = TF*IDF
- Advantage - Intutive, Semantic information capture
- Disadvantage - Sparsity, Out of vocabulary
### Word2Vec
- CBOW - Continuous bag of words
- Skip grams
