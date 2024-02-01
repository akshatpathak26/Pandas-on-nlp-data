# Sentiment Analysis of IMDB Movie Reviews

This notebook performs sentiment analysis on the IMDB movie review dataset to classify reviews as positive or negative. 

## Data Cleaning and Preprocessing
- Lower cased the text
- Removed HTML tags, whitespace, URLs and punctuation
- Expanded contractions and abbreviations
- Corrected spelling mistakes
- Tokenized text into words
- Removed stopwords

## Exploratory Data Analysis
- Compared positive and negative review length distributions  
- Looked at frequency of most common bigrams and trigrams
- Created wordclouds to visualize most common words in positive and negative reviews

## Feature Extraction
- Bag of words representation with ngram range of 1-3 words
- Reduced dimensionality with PCA 
- Plotted PCA projections of positive and negative reviews

The notebook provides a good baseline processing and analysis of the data. Additional steps could include training a classifier model using the extracted features or word embeddings from the text.
