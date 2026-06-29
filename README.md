# Retail Sales Forecasting Using ARIMA and LSTM Models

## Overview

This project forecasts retail sales using historical sales data to improve inventory planning, staffing, and business decisions.

## Objective

* Analyze sales trends and seasonality
* Build ARIMA and LSTM forecasting models
* Compare prediction accuracy using RMSE

## Tools Used

* Python
* Google Colab
* Pandas, NumPy, Matplotlib
* Statsmodels
* TensorFlow / Keras

## Dataset

* Records: ~1,048,575
* Features: Date, Store Number, Product Family, Sales, Promotion

## Results

| Model | RMSE       |
| ----- | ---------- |
| ARIMA | 143,873.24 |
| LSTM  | 119,747.05 |

LSTM outperformed ARIMA with **16.8% lower forecasting error**.

## Conclusion

ARIMA provided a strong baseline, while LSTM performed better in capturing seasonal and nonlinear sales patterns, making it more suitable for retail sales forecasting.
