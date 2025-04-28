# NLP1 Project: Jailbreak Detection

## Steps

1. Presentation of the dataset 2.5 pts
2. Preprocessing of the dataset (normalization and tokenization) and exploratory analysis (descriptive statistics on documents, classes, tokens, etc.) 2.5 pts
3. Benchmark on classification models (naive bayes, logistic regression, tf-idf, word2vec, feedforward neural networks, recurrent neural networks, transformer) 5 pts
4. Benchmark on text generation models (n-gram, tf-idf and word2vec, feedforward neural networks, recurrent neural networks, transformer) 5 pts

## Approaches

Approaches choosen (at least 3)

- Combine multiple datasets and evaluate their impacts on performance
- Create an application (for example, developing a graphical interface)
- Combine multiple models together with at least two different methods (bagging, stacking, hierarchical models)

Other possible approaches:

- Create your own dataset (for example, through scraping)
- Data augmentation (at least three different methods, with and/or without language models) and evaluate their impacts on performance
- Interpret the models with at least two different methods
- Perform unsupervised learning with at least two different methods (for example, dimensionality reduction followed by clustering and/or topic modeling)

## TODO

- [x] Dataset analysis
  - [x] Compare distribution of classes
  - [x] Compare length of documents
  - [x] Compare vocabulary size and characteristics
  - [x] Exploratory data analysis (visualization of common patterns in jailbreak prompts)
- [x] Preprocessing
  - [x] Normalized text data
  - [x] Tokenized text data
  - [x] Removed stopwords
  - [x] Performed lemmatization
  - [x] Removed special characters and digits
- [x] Classification models
  - [x] Naive Bayes with TF-IDF
  - [x] Naive Bayes with Word2Vec
  - [x] Logistic Regression with TF-IDF
  - [x] Logistic Regression with Word2Vec
- [x] Text generation models
  - [x] N-gram model
  - [ ] TF-IDF and Word2Vec
  - [ ] Feedforward Neural Network
  - [ ] Recurrent Neural Network
  - [ ] Transformer
- [ ] Create a graphical application
