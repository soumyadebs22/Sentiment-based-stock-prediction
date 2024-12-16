# Sentiment-based Stock Prediction

This project utilizes **Natural Language Processing (NLP)** techniques to analyze news sentiment and predict stock prices. By training a **Neural Network** on historical stock data and sentiment scores, the model provides future stock price predictions based on the sentiment of news articles.

## Data
- **Stock Price Data:** Scraped from **Yahoo Finance API** (1st Jan 2015 to 1st Jan 2016) for ticker **ADBE**.
- **News Sentiment Data:** Collected from various news sources during the same period. Sentiment scores are generated using NLP techniques.

## Methodology
1. **Sentiment Score Calculation:** Sentiment scores of news articles related to stock tickers are computed using NLP.
2. **Neural Network Model:** Sentiment scores and the corresponding date are used as inputs to the model.
3. **Prediction:** The trained model is then used to predict future stock prices based on the sentiment scores.

## Work Remaining
- **Optimized Portfolio Management:** Implementing a portfolio management system considering multiple tickers. The goal is to develop an efficient allocation of assets using predicted stock prices and sentiment scores.
- **Model Optimization:** Improving the neural network model for better performance.
- **Documentation Update:** The `README.md` file will be updated to reflect the project's progress and future plans.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sentiment-stock-prediction.git
   cd sentiment-stock-prediction
