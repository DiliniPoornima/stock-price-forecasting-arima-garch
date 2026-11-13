# Stock Price Forecasting and Volatility Analysis Using ARIMA-GARCH

## Project Overview
This project focuses on forecasting stock prices and analyzing financial market volatility using ARIMA and hybrid ARIMA-GARCH models. Daily adjusted closing stock prices of Unilever PLC (UL) from 2015 to 2025 were analyzed using R.

## Objectives
- Analyze historical stock price movements.
- Identify suitable ARIMA models for short-term forecasting.
- Investigate volatility clustering using ARCH tests.
- Develop a hybrid ARIMA-GARCH model.
- Compare forecasting accuracy using MAE, RMSE, and MAPE.

## Methodology
1. Data collection from Yahoo Finance.
2. Exploratory data analysis and visualization.
3. Log transformation and stationarity testing using ADF and KPSS.
4. ARIMA model identification using ACF and PACF.
5. Model selection using information criteria.
6. Volatility analysis using ARCH LM tests and GARCH(1,1).
7. Forecasting and model performance evaluation.

## Results

| Model | MAE | RMSE | MAPE |
|---|---:|---:|---:|
| ARIMA(2,1,2) | 0.87 | 1.00 | 1.31% |
| ARIMA-GARCH | 0.90 | 1.06 | 1.36% |

**Key Finding:** ARIMA(2,1,2) achieved better short-term forecasting accuracy, while the hybrid ARIMA-GARCH model provided additional insights into time-varying volatility and financial risk.

## Tools and Technologies
- R Programming
- Time Series Analysis
- ARIMA and GARCH Models
- Statistical Hypothesis Testing
- Financial Forecasting
- Data Visualization

## Conclusion
The study highlights the importance of selecting forecasting models based on analytical objectives. ARIMA is suitable for short-term point forecasting, whereas ARIMA-GARCH offers a more comprehensive framework when volatility analysis is also required.

## Data Source
Yahoo Finance — Unilever PLC (UL), 2015–2025.
