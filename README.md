# Tweet-sentiment

## Overview

Welcome to the "Tweete Sentiment Analysis" project! This data science project focuses on analyzing and predicting the sentiment of tweets using machine-learning techniques. This tool can be valuable for social media analysis, brand monitoring, and sentiment tracking.

**Explore the project directly on Google Colab:** [Twitter Sentiment Analysis](https://colab.research.google.com/drive/1-5Q3Jvlw-aR_Fh1yrj2NA15Q6FWytcM8)

## Feature
Classifies tweets into three sentiment categories: Positive, Negative, and Neutral
Uses Natural Language Processing (NLP) and machine learning techniques
Supports a range of models such as Logistic Regression
Preprocessing pipeline for tokenization, stop-word removal, and lemmatization
Visualization of sentiment analysis results

### Installation

1.clone respository
$ cd /path/to/directory
$ git clone https://github.com/aditya001s/tweet-sentiment/tree/main

2.Install the required dependency
!pip install -q transformers tweepy matplotlib wordcloud

## Project Description

Twitter (Now X) sentiment analysis is a crucial task for understanding public opinion and sentiment towards various topics, brands, or events. This project utilizes machine-learning models to classify tweets based on their sentiment polarity, helping businesses, researchers, and individuals gauge public sentiment effectively.

## Dataset

The dataset used in this project is the Sentiment140 dataset from Kaggle, which consists of 1.6 million tweets extracted using the Twitter API. Each tweet is labelled with its sentiment polarity (0 for negative, 2 for neutral, and 4 for positive), making it suitable for sentiment analysis tasks.

**Dataset Link:** [Sentiment140 Dataset on Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140)

## Models Used

1. **Logistic Regression:**
   - Logistic Regression is a classic classification algorithm that models the probability of a binary outcome. It's widely used for text classification and sentiment analysis tasks.

## Evaluation Metrics

The performance of the sentiment analysis models was evaluated using the following metrics:

- **Accuracy:** Measures the overall correctness of the classification.
- **F1-Score:** Harmonic mean of precision and recall, useful for imbalanced datasets.
- **ROC-AUC Score:** Area under the Receiver Operating Characteristic (ROC) curve, which measures the model's ability to distinguish between positive and negative classes.

## Usage
To run the project and explore the sentiment analysis models:

1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/aditya001s/tweet-sentiment
   ```

2. Run the main script or Jupyter Notebook to train and evaluate the models on the Sentiment140 dataset.

3. Analyze the results and predictions generated by each model to gain insights into tweet sentiments.

Feel free to customize and extend the project as needed for your specific use case or dataset.
