# Time Series Analysis

This project presents a time series analysis of two economic and environmental datasets using statistical forecasting methods in R.

## Project overview

The analysis is divided into two parts:

1. **Non-seasonal time series** – analysis of USD/PLN exchange rates.
2. **Seasonal time series** – analysis of greenhouse gas consumption in Italy.

The project compares different forecasting approaches and evaluates their performance using statistical tests, information criteria and forecast error measures.

## Methods

### 1. Non-seasonal time series

The non-seasonal analysis focuses on the USD/PLN exchange rate.

The following methods are applied:

- Exponential Weighted Moving Average (EWMA)
- Holt's exponential smoothing method
- ARIMA models
- Augmented Dickey-Fuller (ADF) test
- KPSS test
- Ljung-Box test
- Box-Pierce test
- Breusch-Godfrey test
- ACF and PACF analysis
- AIC and BIC model comparison
- residual diagnostics

The analysis includes the identification of stationarity, differencing, model estimation, model selection and diagnostic checking.

### 2. Seasonal time series

The seasonal analysis focuses on greenhouse gas consumption in Italy.

The following methods are applied:

- Additive Holt-Winters model
- Multiplicative Holt-Winters model
- Logarithmic transformation
- Seasonal differencing
- ADF stationarity testing
- KPSS test
- Ljung-Box test
- Box-Pierce test
- ACF and PACF analysis
- SARIMA models
- AIC and BIC model comparison
- residual diagnostics

The seasonal component is analysed using monthly observations, with a seasonal period of 12.

## Data

The datasets are stored in the `dane/` directory.

```text
dane/
├── Gworek_ASC_niesezonowe.csv
└── Gworek_ASC_sezonowe.csv
