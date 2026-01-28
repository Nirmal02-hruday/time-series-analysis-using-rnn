# time-series-analysis-using-rnn
Hybrid time series forecasting using ARIMA and RNN (GRU)

## 📌 Project Overview
This project focuses on time series forecasting using a hybrid modeling approach
that combines ARIMA and Recurrent Neural Networks (GRU) to predict future trends
from historical time-dependent data.

## 🎯 Problem Statement
Traditional models like ARIMA handle linear trends well but fail with non-linear
patterns, while RNNs require large datasets and high computation.
This project combines both to improve accuracy and efficiency.

## 🧠 Proposed Solution
- ARIMA captures linear trends and seasonality
- GRU learns non-linear temporal dependencies
- Final prediction is a hybrid of ARIMA and GRU outputs

## 🏗 System Architecture
1. Data preprocessing and stationarity testing
2. ARIMA model fitting and prediction
3. Residual extraction
4. GRU training on residuals
5. Hybrid forecast generation

## ⚙️ Models Used
- ARIMA
- GRU (Recurrent Neural Network)

## 📈 Evaluation Metrics
- RMSE
- MAE

## 🛠 Tools & Technologies
Python, Pandas, NumPy, Statsmodels, TensorFlow/Keras, Matplotlib

## 🌍 Applications
Sales forecasting, financial trends, demand estimation, resource planning

## 🔮 Future Scope
Real-time forecasting, multivariate time series, dashboard deployment
