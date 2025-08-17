# 🌍 Macroeconomic Forecasting Toolkit
This repository contains two complementary research projects applying **time-series forecasting techniques** to major macroeconomic indicators:

1. **India’s GDP Growth Forecasting (ARIMA + OLS Regression)**  
2. **USA’s Inflation Forecasting (ARIMA + Time-Series Models in R)**  

Together, these projects demonstrate how econometric modeling can support **policy analysis, investment decision-making, and strategic planning**.

---

## 📂 Repository Structure

Macroeconomic-Forecasting/
│
├── scripts/                            # All analysis scripts
│   ├── india_gdp_forecasting.ipynb     # Python notebook for India's GDP growth
│   ├── usa_inflation_forecasting.Rmd   # RMarkdown script for USA inflation
│   └── utils.py                        # (optional) helper functions
│
├── dataset/                            # All datasets
│   ├── india_gdp_growth.csv            # 69 years of India's GDP data
│   ├── usa_inflation_cpi.csv           # CPI-based USA inflation data
│   └── README.md                       # Dataset descriptions
│
├── results/                            # Forecast outputs, plots, diagnostics
│   ├── india_gdp_forecast.png
│   ├── usa_inflation_forecast.png
│   ├── india_model_diagnostics.txt
│   └── usa_model_diagnostics.txt
│
└── README.md                           # Combined documentation


## 🔍 Project 1: India’s GDP Growth Forecasting

- **Dataset**: 69 years of India’s annual GDP growth.  
- **Models**: ARIMA(0,1,1), ARIMA(1,2,1), ARIMA(2,1,1), and OLS regression with time-trend.  
- **Validation**:
  - Stationarity checks: ADF & KPSS tests  
  - Residual diagnostics: Ljung-Box, Breusch-Pagan, Durbin-Watson  
- **Metrics**: AIC, BIC, RMSE, MAE, MAPE  
- **Key Insight**: ARIMA(2,1,1) achieved the best fit and predictive performance, outperforming OLS regression.  

---

## 🔍 Project 2: USA’s Inflation Forecasting

- **Dataset**: Historical U.S. CPI-based inflation rates (monthly/quarterly).  
- **Models**: ARIMA-based time-series forecasting in R (using `forecast` and `tseries` libraries).  
- **Validation**:
  - Stationarity tests (ADF)  
  - Residual diagnostics to ensure model adequacy  
- **Metrics**: AIC, BIC, RMSE, MAE  
- **Key Insight**: ARIMA models captured short-term cyclical inflation trends, producing reliable forecasts for policy and investment strategy.  

---

Got it 👍 thanks for catching that!
If your **India GDP Growth Forecasting** is done in **R (not Python)**, then the tools section should be rewritten accordingly.

Here’s the corrected version:

---

### 📊 Tools & Libraries

#### For India GDP Forecasting (**R**)

* `forecast` – ARIMA model fitting & forecasting
* `tseries` – Stationarity tests (ADF, KPSS) and diagnostics
* `lm()` (base R) – OLS regression with time-trend
* `ggplot2` – Visualization of time-series and forecasts
* `dplyr` – Data manipulation & cleaning
* `Metrics` – Forecast accuracy metrics (RMSE, MAE, MAPE)

#### For USA Inflation Forecasting (**R**)

* `forecast` – ARIMA model fitting & forecasting
* `tseries` – ADF test, residual diagnostics
* `ggplot2` – Visualization
* `dplyr` – Data wrangling

---

## 📊 Results & Applications

- **India GDP Forecasting** → Supports macroeconomic planning, policy evaluation, and investor risk assessment in emerging markets.  
- **USA Inflation Forecasting** → Useful for central banks, investors, and businesses monitoring price stability and monetary policy.  

---

## 🚀 Future Extensions
- Expand to **multivariate forecasting models** (VAR, VECM) including trade, fiscal, and monetary variables.  
- Compare **machine learning models** (XGBoost, LSTM) with classical econometrics.  
- Build a **dashboard** to visualize forecasts interactively.  

---

## 👤 Author
**Anshuman Patnaik**  
M.Sc. Economics | Strategy & Data Science | Consulting & Policy Research  
📧 [anshumanpatnaik777@gmail.com](mailto:anshumanpatnaik777@gmail.com)  

---

## ⭐ Acknowledgments
These projects integrate econometric modeling with applied macroeconomic analysis to demonstrate the value of **data-driven forecasting for strategy, policy, and consulting use cases**.
