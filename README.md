# TSA on Whale Movement

## 📌 Overview
This project implements a **complete Applied Time Series Analysis** workflow on a real-world dataset of **Monthly Movements of Australia’s East Coast Humpback Whales**. The objective is to analyze time series behavior and perform forecasting using **Exponential Smoothing, ARIMA, and SARIMA** models.

## 🧭 Analysis Performed
- Data loading and preprocessing using `pandas`
- Stationarity testing using **ADF** and **KPSS**
- Additive seasonal decomposition
- Forecasting using:
  - Exponential Smoothing (additive trend & seasonality, period = 12)
  - ARIMA
  - SARIMA (seasonal period = 12)
