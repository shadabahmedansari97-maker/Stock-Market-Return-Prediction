Stock Market Next-Day Return Prediction
Predicted next-day adjusted close return and price for AAPL stock using an ensemble of machine learning models.
Project Overview
Built a system that predicts whether AAPL stock will go up or down the next day using three sources of information — the stock itself, the overall market (QQQ), and sector peers.
Models Used
Elastic Net
Random Forest
Gradient Boosting
Ensemble (average of all three)
Dataset
Kaggle: Stock Market Dataset (NASDAQ) — daily OHLCV data ending April 2020
Results (Test Period: Jan-Mar 2020, COVID Crash)
Model
MAE
RMSE
Sign Accuracy
Elastic Net
0.0292
0.0420
43.5%
Random Forest
0.0295
0.0433
54.8%
Gradient Boosting
0.0291
0.0428
50.0%
Ensemble
0.0290
0.0423
53.2%
Tech Stack
Python, scikit-learn, pandas, numpy
Note
This project is for educational purposes only and does not constitute investment advice.
