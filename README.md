# Sentiment Analysis Project

This repository contains the code and resources for a sentiment analysis project created as a part of **Computer Linguistics** program at the **Higher School of Economics (HSE), 2023-2024**. The goal of this project is to classify the sentiment of text data into positive or negative categories.

## Introduction

Sentiment analysis, also known as opinion mining, is a natural language processing (NLP) technique used to determine the sentiment expressed in a piece of text. This project aims to develop a sentiment analysis model using machine learning techniques.

## Dataset

The dataset used for this project consists of 86,000 film reviews which I scraped from IMDb. The reviews are labeled with sentiment categories (positive, negative). The dataset provides a rich source of text data for training and evaluating the sentiment analysis model.

## Methodology

The sentiment analysis model was developed using the following steps:

1. **Data Collection:**
    - Scraped 86,000 film reviews from IMDb using web scraping techniques.

2. **Data Preprocessing:**
    - Tokenization
    - Removing stop words
    - Lemmatization/Stemming
    - Vectorization (Word2Vec)

3. **Model Training:**
    - Selection of machine learning algorithms (bagging)
    - Training the model on the preprocessed data

4. **Model Evaluation:**
    - Evaluating the model's performance
      
5. **Hyperparameter Tuning:**
    - Tuning the model parameters to improve performance

This project is licensed under the terms of the MIT license. See the [LICENSE](https://github.com/olyapetrukhina/sentiment_analysis/blob/main/LICENSE) file for details.
