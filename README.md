# Multi-Model Time Series Forecasting of India’s GDP Growth Using Machine Learning

## Overview

This project applies multiple time-series models to forecast India’s GDP growth rate. The analysis combines classical econometric methods with machine learning–inspired approaches to compare accuracy, interpret results, and generate policy-relevant insights.

The work is based on India’s annual GDP growth dataset and evaluates whether different models yield consistent forecasts for India’s near-term growth trajectory.

---

## Data

* Dataset: **India’s annual GDP growth rate (% change)**
* Stored locally in the `data/` folder.
* Used for model training, validation, and forecasting.

---

## Methods Used

1. **Exploratory Data Analysis (EDA)**

   * Time-series plots of GDP growth.
   * Stationarity checks using Augmented Dickey-Fuller (ADF) and KPSS tests.
   * Autocorrelation (ACF) and Partial Autocorrelation (PACF) analysis.

2. **Modeling Approaches**

   * **ARIMA Models:**

     * ARIMA(0,1,1), ARIMA(1,2,1), ARIMA(2,1,1).
   * **OLS Trend Model:**

     * Linear regression with time as predictor.
   * (Optional future extension) **Machine Learning Models:** Prophet, LSTM, Random Forest regression.

3. **Forecasting & Evaluation**

   * Out-of-sample forecasts for 5 years.
   * Model comparison using RMSE, MAE, AIC, and BIC.
   * Scenario-based forecasts (base vs. optimistic vs. pessimistic).

---

## Results Summary

* ARIMA(2,1,1) delivered the lowest RMSE among ARIMA models.
* The OLS trend model produced smooth linear forecasts (approximately 7.1% annual growth).
* ARIMA models captured more short-run volatility compared to OLS.
* Forecasts from all models suggest India’s GDP growth stabilizing in the 6–7% range over the next five years.

---

## Project Structure

```
├── data/                     # Contains India GDP growth dataset
├── scripts/                  # R/Python notebooks for modeling
├── results/                  # Model summaries, forecasts, plots
└── README.md                 # This file
```

---

## How to Run

1. Ensure the GDP growth dataset is stored in the `data/` directory.
2. Open the R script or notebook.
3. Run stationarity checks, build ARIMA models, and compare with OLS trend.
4. Generate 5-year forecasts and plots.

---

## Key Takeaways

* A multi-model approach reduces model risk in economic forecasting.
* Comparative forecasts provide more reliable inputs for strategic planning.
* Forecast outputs can be integrated into macroeconomic dashboards for decision-making.

