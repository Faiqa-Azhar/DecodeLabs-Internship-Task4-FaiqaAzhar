# NLP & Sentiment Analysis using Machine Learning

## Project Overview

This project focuses on building a Natural Language Processing (NLP) based Sentiment Analysis system that can automatically analyze human-written reviews and classify them into Positive or Negative sentiments.

The model performs text preprocessing, converts unstructured text into numerical data using TF-IDF Vectorization, and trains a Machine Learning classifier using Naive Bayes to predict sentiment.


## Objective

The main goal of this project is to teach a machine how to understand and mathematically categorize human text data.

The system can analyze customer reviews and determine whether the expressed opinion is positive or negative.



## Dataset Information

Dataset contains customer review text with sentiment labels.

### Features:

- Sentence → Review text
- Sentiment → Target class

### Classes:

- Positive
- Negative

Neutral reviews were removed to perform binary sentiment classification.


# Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn


# NLP Preprocessing Pipeline

The text data was cleaned using:

### Tokenization
Breaking sentences into individual words.

### Stop Word Removal
Removing unnecessary words such as:


### Noise Removal

Removed:

- Special characters
- Numbers
- Unnecessary symbols

# Feature Extraction

## TF-IDF Vectorization

TF-IDF converts text into numerical values that machine learning algorithms can understand.

It calculates:

- Term Frequency (TF)
- Inverse Document Frequency (IDF)

The output is a mathematical feature matrix.


# Machine Learning Model

## Multinomial Naive Bayes

Naive Bayes classifier is used for text classification because it performs well on high-dimensional text datasets.

The model learns patterns from reviews and predicts sentiment.


# Model Evaluation

The trained model is evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Classification Report
- Confusion Matrix


# Prediction Example

Input:
"This product is amazing, I really love it"

Output:
Positive



# Future Improvements

- Use Deep Learning models
- Implement LSTM / Transformers
- Add real-time review analysis
- Deploy using Streamlit
- Improve accuracy using hyperparameter tuning



# Author

Faiqa Azhar
