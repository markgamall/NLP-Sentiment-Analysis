# NLP-Sentiment-Analysis

## Overview
This project performs sentiment analysis on movie reviews using various machine learning techniques. The goal is to classify reviews as positive (1) or negative (0) based on their textual content. The project includes data preprocessing, feature extraction, model training, and evaluation.

## Datasets Used
### The project utilizes three different sentiment analysis datasets:

- Scale Data: Movie reviews from critics (Dennis Schwartz, James Berardinelli, Scott Renshaw, Steve Rhodes)
- RT-Polarity Data: Movie reviews from Rotten Tomatoes
- Review Polarity: Movie reviews dataset with positive and negative sentiment labels

## Preprocessing Steps
### The text preprocessing pipeline includes:

- Lowercasing
- HTML tag removal
- Punctuation removal
- Number removal
- Emoji handling
- Negation handling
- Spelling correction (optional)
- Stopword removal
- Lemmatization with POS tagging
- Slang replacement

## Feature Extraction
### Two main approaches were used:

- TF-IDF Vectorization (unigrams + bigrams)
- Count Vectorization
- Combined Features (TF-IDF + Count)

## Models Evaluated
- Naive Bayes
- Logistic Regression
- Decision Tree
- Random Forest
- Ensemble Model (Voting Classifier)
