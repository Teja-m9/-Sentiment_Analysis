# Sentiment Analysis on Tweets

## Overview
This project performs sentiment analysis on tweets using the dataset provided in `tweets.csv`. The goal is to classify the sentiment of tweets as positive, negative, or neutral based on their text content.

## Contents
- Data Exploration
- Data Cleaning and Preprocessing
- Sentiment Analysis

## Dataset
The dataset used in this project is `tweets.csv`, which contains the following columns:
- `tweet_id`: Unique identifier for each tweet
- `tweet_text`: The text content of the tweet
- `created_at`: Timestamp of when the tweet was created
- `user`: User who posted the tweet
- `sentiment`: The sentiment label (e.g., positive, negative, neutral)

## Data Exploration
In this section, the dataset is explored to understand:
- The distribution of sentiment labels.
- Basic statistics about the tweets.

## Data Cleaning and Preprocessing
Data cleaning includes:
- Removing duplicates and irrelevant columns.
- Handling missing values.
- Normalizing text (lowercasing, removing punctuation, etc.).
- Tokenization and lemmatization.

## Sentiment Analysis
The sentiment analysis is conducted using:
- Natural Language Processing (NLP) techniques.
- A pre-trained sentiment analysis model (e.g., VADER, TextBlob) or a custom model using machine learning.

## Requirements
To run this project, you'll need the following libraries:
- Pandas
- NumPy
- Scikit-learn
- NLTK or TextBlob (depending on your analysis method)

You can install these using pip:

```bash
pip install pandas numpy scikit-learn nltk textblob
