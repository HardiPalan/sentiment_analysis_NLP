# Sentiment Analysis using NLP

This project focuses on using Natural Language Processing (NLP) techniques to perform sentiment analysis on text data. The goal is to classify text into positive, negative, or neutral sentiment using various NLP methods, including text preprocessing, vectorization, and machine learning models.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Text Preprocessing](#text-preprocessing)
- [Modeling](#modeling)
- [Results](#results)

## Project Overview

Sentiment analysis is a key application of NLP that is widely used in business, politics, and social media to assess public opinion. This project uses machine learning models to classify text as having positive, negative, or neutral sentiment by implementing several preprocessing techniques and comparing model performance.

## Dataset

The dataset used for this project consists of text data, often sourced from movie reviews, social media posts, or product reviews. Each entry in the dataset is labeled with the corresponding sentiment (positive, negative, or neutral).

- **Text**: The text body for sentiment analysis.
- **Sentiment**: The sentiment label, usually positive, negative, or neutral.

## Text Preprocessing
Before building the sentiment classification models, the following preprocessing steps are applied:

- **Lowercasing**: Converting all text to lowercase.
- **Tokenization**: Splitting text into individual words or tokens.
- **Vectorization**: Converting text into numerical format using methods like TF-IDF or Count Vectorizer.

## Modeling
Several machine learning models were implemented for sentiment classification:

1. **Logistic Regression**: A simple yet effective classification model.
2. **Support Vector Machine (SVM)**: A robust model for high-dimensional data.
3. **Random Forest Classifier**: An ensemble method that enhances accuracy by using multiple decision trees.
The models are evaluated using common metrics such as accuracy, precision, recall, and F1-score.

## Results
The final model performances are as follows:

- **Accuracy**: 85%
- **Precision**: 82%
- **F1-score**: 83%
The Support Vector Machine (SVM) model provided the best performance with an accuracy of 85%.
