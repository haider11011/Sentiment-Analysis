# Sentiment Analysis Project

This project is a beginner's guide to experimenting with various classification techniques and using VADER for sentiment analysis. The main goal is to classify sentiment in a dataset of reviews and explore the performance of different models.

## Introduction
This project aims to perform sentiment analysis on a dataset of reviews. We will explore various classification techniques and use the VADER sentiment analysis tool. This project provides a practical approach to understanding and implementing sentiment analysis using supervised learning methods and natural language processing (NLP) techniques.

## Exploratory Data Analysis (EDA)
### Observation
The EDA reveals class imbalances, with positive reviews (classes 4.0 and 5.0) being more prevalent than negative reviews (classes 0.0, 1.0, 2.0, 3.0). To address this, oversampling techniques are applied to balance the dataset.

### Further Observations
- The data contains neutral words and stop words.
- Preprocessing steps such as tokenization and removing non-alphanumeric characters are essential.

## Data Preprocessing
The preprocessing steps include:
- Converting text to lowercase to ensure consistency.
- Removing stop words using NLTK (Natural Language Toolkit).
- Applying stemming or lemmatization to reduce words to their root form.

## Model Selection and Training
Several machine learning algorithms are evaluated, including:
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- Gradient Boosting

Each model is trained with and without preprocessing techniques to assess the impact on performance. The SVM model achieves the highest average scores across different scenarios.

## Sentiment Analysis with VADER
VADER (Valence Aware Dictionary and sEntiment Reasoner) is used for sentiment analysis, providing a rule-based approach to determine the sentiment polarity of the reviews.

## Evaluation and Observations
### Key Observations
- Preprocessing improves model performance significantly.
- The Support Vector Machine (SVM) model outperforms other models in accuracy.
- VADER provides a simple yet effective way to analyze sentiment in text data.

### Performance Metrics
Evaluation metrics such as accuracy, precision, recall, and F1-score are used to measure model performance. These metrics help in understanding the strengths and weaknesses of each model.
