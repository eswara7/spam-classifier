# 📱  Spam Classifier 

A machine learning project to classify messages as **Spam** or **Ham** (not spam) using Natural Language Processing (NLP) techniques. This classifier leverages popular NLP and machine learning algorithms to analyze text data and identify spam patterns in messages. This project serves as a practical introduction to NLP, text processing, and model building in Python.

## 🛠️ Project Overview

In this project, we classify messages by training a machine learning model to detect spam messages based on word patterns and usage. The classifier is trained on labeled data to predict whether a new message is spam or ham, using various machine learning algorithms and feature extraction methods.

## 🔍 Data Processing

The data preprocessing stage includes the following steps:

1. **Data Cleaning**: Removing noise such as punctuation, special characters, and converting text to lowercase for consistency.
2. **Text Preprocessing**:
   - **Tokenization**: Splitting messages into individual words or tokens.
   - **Stop Words Removal**: Filtering out commonly used words (e.g., "and," "the") that do not contribute meaningfully to spam detection.
   - **Stemming**: Using `PorterStemmer` to reduce words to their base form (e.g., "running" becomes "run").

## 🧩 Feature Engineering

To convert the text data into a machine-readable format, we employ feature engineering techniques:

- **CountVectorizer**: Converts text into a matrix of token counts to capture word frequency.
- **TF-IDF (Term Frequency-Inverse Document Frequency)**: Measures word importance within the text, balancing each word's frequency against its rarity in the dataset.

## 🤖 Model Building

We train and evaluate several machine learning algorithms to find the best model for classifying messages. The algorithms include:

- **Multinomial Naive Bayes**
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Decision Trees**

Each model is compared for performance and accuracy, enabling us to select the most effective approach for spam detection.

## 📊 Evaluation and Results

To assess each model’s performance, we use several evaluation metrics:

- **Accuracy**: The percentage of correctly classified messages.
- **Precision**: The percentage of messages classified as spam that are truly spam.
- **Recall**: The percentage of actual spam messages that are correctly identified.
- **F1 Score**: The harmonic mean of precision and recall, balancing both metrics.

By comparing these metrics, we identify the best model for classifying messages effectively.

## 🚀 Skills Developed

This project builds hands-on skills in:

- **Python Programming** 🐍
- **Machine Learning** 🤖
- **Natural Language Processing (NLP)** 🧠
- **Data Analysis** 📈
- **Feature Engineering** 🛠️
