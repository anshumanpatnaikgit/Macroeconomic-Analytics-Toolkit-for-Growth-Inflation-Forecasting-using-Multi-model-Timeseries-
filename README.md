# 🌍 Macroeconomic Forecasting Toolkit  

This repository contains two complementary research projects applying **time-series forecasting techniques in R** to major macroeconomic indicators:

1. **India’s GDP Growth Forecasting (ARIMA + OLS Regression in R)**  
2. **USA’s Inflation Forecasting (ARIMA + Time-Series Models in R)**  

Together, these projects demonstrate how econometric modeling can support **policy analysis, investment decision-making, and strategic planning**.  

---

## 📂 Repository Structure  

```bash
Macroeconomic-Forecasting/
│
├── 📜 scripts/                           # All analysis scripts
│   ├── 📊 india_gdp_forecasting.R        # R script for India's GDP growth
│   ├── 📊 usa_inflation_forecasting.Rmd  # RMarkdown script for USA inflation
│
├── 📂 dataset/                           # All datasets
│   ├── 📈 india_gdp_growth.csv           # 69 years of India's GDP data
│   ├── 📈 usa_inflation_cpi.csv          # CPI-based USA inflation data
│
├── 📊 results/                           # Forecast outputs, plots, diagnostics
│   ├── 📉 india_gdp_forecast.png
│   ├── 📉 usa_inflation_forecast.png
│
└── 🏠 README.md                          # Combined documentation
```
---

## 🔍 Project 1: India’s GDP Growth Forecasting  

- **Dataset**: 69 years of India’s annual GDP growth data.  
- **Models**: ARIMA(0,1,1), ARIMA(1,2,1), ARIMA(2,1,1), and OLS regression with a time-trend.  
- **Validation**:  
  - Stationarity checks: ADF & KPSS tests  
  - Residual diagnostics: Ljung-Box, Breusch-Pagan, Durbin-Watson  
- **Metrics**: AIC, BIC, RMSE, MAE, MAPE  
- **Key Insight**: ARIMA(2,1,1) achieved the best predictive performance, outperforming the OLS time-trend model.  

---

## 🔍 Project 2: USA’s Inflation Forecasting  

- **Dataset**: Historical U.S. CPI-based inflation rates (monthly/quarterly).  
- **Models**: ARIMA-based time-series forecasting in R (`forecast` + `tseries` libraries).  
- **Validation**:  
  - Stationarity test: Augmented Dickey-Fuller (ADF)  
  - Residual diagnostics to ensure model adequacy  
- **Metrics**: AIC, BIC, RMSE, MAE  
- **Key Insight**: ARIMA models effectively captured short-term inflation cycles, producing reliable forecasts for policy and investment strategy.  

---

## 📊 Tools & Libraries (R)  

- `forecast` – ARIMA model fitting & forecasting  
- `tseries` – Stationarity tests (ADF, KPSS) & diagnostics  
- `lm()` (base R) – OLS regression with time-trend  
- `ggplot2` – Visualization of time-series & forecasts  
- `dplyr` – Data manipulation & cleaning  
- `Metrics` – Forecast accuracy metrics (RMSE, MAE, MAPE)  

---

## 📊 Results & Applications  

- **India GDP Forecasting** → Supports macroeconomic planning, policy evaluation, and investor risk assessment in emerging markets.  
- **USA Inflation Forecasting** → Useful for central banks, investors, and businesses monitoring price stability and monetary policy.  

---

## 🚀 Future Extensions  

- Expand to **multivariate forecasting models** (VAR, VECM) including trade, fiscal, and monetary indicators.  
- Compare with **machine learning models** (XGBoost, LSTM) for potential accuracy improvements.  
- Develop an **interactive R Shiny dashboard** for real-time macroeconomic forecasting.  

---

## 👤 Author  

**Anshuman Patnaik**  
M.Sc. Economics | Strategy & Data Science | Consulting & Policy Research  
📧 [anshumanpatnaik777@gmail.com](mailto:anshumanpatnaik777@gmail.com)  

---

## ⭐ Acknowledgments  

This work integrates **econometric modeling in R** with applied macroeconomic analysis to highlight the role of **data-driven forecasting** in shaping economic planning.  
