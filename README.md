# Stock Market Next-Day Return Prediction

Predicted next-day adjusted close return and price for AAPL stock using an ensemble of machine learning models.

## Project Overview
Built a system that predicts whether AAPL stock will go up or down the next day using three sources of information — the stock itself, the overall market (QQQ), and sector peers.

## Models Used
- Elastic Net
- Random Forest
- Gradient Boosting
- Ensemble (average of all three)

## Dataset
Kaggle: Stock Market Dataset (NASDAQ) — daily OHLCV data ending April 2020

## Results (Test Period: Jan-Mar 2020, COVID Crash)
- Elastic Net — MAE: 0.0292, RMSE: 0.0420, Sign Accuracy: 43.5%
- Random Forest — MAE: 0.0295, RMSE: 0.0433, Sign Accuracy: 54.8%
- Gradient Boosting — MAE: 0.0291, RMSE: 0.0428, Sign Accuracy: 50.0%
- Ensemble — MAE: 0.0290, RMSE: 0.0423, Sign Accuracy: 53.2%

## Tech Stack
Python, scikit-learn, pandas, numpy

## Note
This project is for educational purposes only and does not constitute investment advice.
