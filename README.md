# Enhancing Stock Market Prediction through Historical Prices and Sentiment Analysis: A Deep Learning Approach

## Overview
This project uses an approach for stock market prediction leveraging historical price data and sentiment analysis of news headlines. We propose a model that integrates Long Short-Term Memory (LSTM) neural networks with sentiment analysis to forecast stock price movements. Our methodology involves scraping relevant news articles, extracting sentiment features, and combining them with historical price data for stocks and training the LSTM model. Results indicate promising predictive performance, demonstrating the efficiency of our approach in capturing the relationship between news sentiment and stock price dynamics.

![image](https://github.com/user-attachments/assets/a476cbd9-f89b-4857-b00f-44015638ba28)

## Features

- Integration of LSTM neural networks for sequential data analysis.
- Sentiment analysis of news headlines to gauge market sentiment.
- Comprehensive dataset creation from historical stock prices and news articles.

## Methodology

1. **Data Acquisition**: 
   - Historical stock prices are retrieved using the Yahoo Finance API.
   - Relevant news articles are scraped from reputable sources to gather sentiment data.

2. **Data Preprocessing**: 
   - News headlines are refined using advanced natural language processing techniques to extract sentiment features.
   - A unified dataset is created by combining historical price data with sentiment features.

3. **Model Training**: 
   - The LSTM neural network is trained on the cohesive dataset to learn the complex interplay between historical prices and market sentiment.

4. **Evaluation**: 
   - The model's performance is evaluated using metrics such as Root Mean Square Error (RMSE) and accuracy.

