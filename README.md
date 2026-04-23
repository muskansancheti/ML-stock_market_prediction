This project focuses on predicting the next-day stock price direction (UP/DOWN) using Machine Learning models trained on historical stock market OHLCV data.

The objective is to classify whether the stock closing price will increase or decrease on the next trading day using technical indicators such as daily return, moving average ratio, volatility, momentum, and price range.

The project compares four classical machine learning models:

Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Logistic Regression
Random Forest

Since stock markets are highly influenced by the Efficient Market Hypothesis (EMH), achieving extremely high accuracy is unrealistic. Therefore, this project uses F1 Score as the primary evaluation metric instead of raw accuracy.

Random Forest emerged as the best-performing model due to its ability to handle noisy financial data using ensemble learning.

This project also includes:
Feature Engineering
Chronological Train-Test Split
Data Leakage Prevention
Confusion Matrix Visualization
Model Performance Comparison
All-Company Final Comparison
Next-Day Stock Movement Prediction

This project is built for academic research purposes and should not be used for real financial trading decisions.
