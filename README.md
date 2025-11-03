# Stock-Prediction-with-ARIMA
This project forecasts Thai stock prices DELTA.BK using the ARIMA model.

## 🔍 Overview
- Data Source: Yahoo Finance (`yfinance`)
- Model: ARIMA(5,1,0)
- Forecast Horizon: 30 days ahead
- Evaluation Metrics: MAE, RMSE, Accuracy (%)

## 📊 Result
The model predicts that the stock will remain stable in the next 30 days.

<img width="868" height="471" alt="output_stock" src="https://github.com/user-attachments/assets/325a6a66-54aa-4708-8931-749ac3e5eb87" />

## 🧠 How to Run
1. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib statsmodels yfinance
2. Run notebook
   ```bash
   jupyter notebook stock_delta.ipynb
