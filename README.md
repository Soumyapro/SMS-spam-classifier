# SMS Spam Classifier

![SMS spam or not spam??](https://towardsdatascience.com/wp-content/uploads/2020/12/1_igArwmR7Pj_Mu_KUGD1SQ.png)

A machine learning project that accurately identifies spam SMS messages using Natural Language Processing (NLP) techniques and a Multinomial Naive Bayes classifier.

## Overview

This SMS Spam Classifier analyzes text messages and classifies them as either spam or legitimate (ham) with high precision. The model is specifically optimized to minimize false positives, ensuring legitimate messages are not incorrectly flagged as spam.

## Features

- **Text Preprocessing Pipeline**:
  - Lowercase conversion
  - Tokenization
  - Special character removal
  - Stop words and punctuation filtering
  - Word stemming using Porter Stemmer

- **Feature Engineering**:
  - Text vectorization using TF-IDF
  - Text statistics extraction (character count, word count, sentence count)
  - Feature correlation analysis

- **Model Selection and Evaluation**:
  - Comparative analysis of multiple classification algorithms
  - Emphasis on precision metric to minimize false positives
  - Multinomial Naive Bayes selected for optimal precision (100%)

- **Visualization**:
  - Word clouds for spam vs. legitimate messages
  - Frequency distribution of common words
  - Feature importance analysis
  - Class distribution visualization

## Performance Metrics

| Model | Accuracy | Precision |
|-------|----------|-----------|
| Multinomial Naive Bayes | 97.0% | 100% |

## Requirements
numpy==1.20.3
pandas==1.3.4
scikit-learn==1.0.1
nltk==3.6.5
matplotlib==3.4.3
seaborn==0.11.2
wordcloud==1.8.1
xgboost==1.4.2
