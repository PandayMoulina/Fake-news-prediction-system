# Fake News Detection System

A machine learning-based system to identify whether a given news article is **real** or **fake** using Natural Language Processing (NLP) and Logistic Regression.

## Project Overview

With the increasing spread of misinformation, it's crucial to develop tools that can detect fake news effectively. This project uses text classification techniques to determine the authenticity of news content.

- **Accuracy**: 97%+
- **Algorithm Used**: Logistic Regression
- **Libraries**: `scikit-learn`, `nltk`, `pandas`, `numpy`, `re`

## Dataset

The dataset consists of labeled news articles as either **"FAKE"** or **"REAL"**. It is preprocessed using NLP techniques before training the model.

> Source: Kaggle 

## Technologies & Tools

- **Language**: Python
- **Libraries**:
  - `pandas` for data manipulation
  - `numpy` for numerical operations
  - `nltk` for natural language processing
  - `scikit-learn` for model building
  - `re` for regex operations

## How It Works

1. **Data Preprocessing**
   - Lowercasing
   - Removing punctuation and stopwords
   - Tokenization and stemming

2. **Vectorization**
   - `CountVectorizer` or `TF-IDF Vectorizer` to convert text into numerical format

3. **Model Training**
   - Logistic Regression classifier is trained on the vectorized data

4. **Evaluation**
   - Accuracy, Precision, Recall, F1 Score
   - Confusion Matrix

