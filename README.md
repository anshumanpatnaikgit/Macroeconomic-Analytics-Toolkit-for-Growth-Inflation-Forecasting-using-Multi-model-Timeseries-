# 🌍 Macroeconomic Forecasting Toolkit
This repository contains two complementary research projects applying **time-series forecasting techniques** to major macroeconomic indicators:

1. **India’s GDP Growth Forecasting (ARIMA + OLS Regression)**  
2. **USA’s Inflation Forecasting (ARIMA + Time-Series Models in R)**  

Together, these projects demonstrate how econometric modeling can support **policy analysis, investment decision-making, and strategic planning**.

---

## 📂 Repository Structure

Macroeconomic-Forecasting/
│
├── india-gdp-forecasting/ # Project 1: India's GDP Growth
│ ├── data/ # Historical GDP dataset (69 years)
│ ├── notebooks/ # Python notebooks
│ ├── models/ # Saved ARIMA/OLS models
│ └── results/ # Forecasts, plots, diagnostics
│
├── usa-inflation-forecasting/ # Project 2: USA Inflation
│ ├── data/ # CPI / Inflation dataset
│ ├── scripts/ # RMarkdown (.Rmd) scripts
│ ├── models/ # Trained ARIMA models
│ └── results/ # Forecast outputs & charts
│
└── README.md # Combined documentation

---

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

## ⚙️ Tools & Libraries

### For India GDP Forecasting (Python)
- `pandas`, `numpy` – Data handling  
- `statsmodels` – ARIMA, OLS regression, diagnostics  
- `matplotlib`, `seaborn` – Visualization  
- `scikit-learn` – Forecast accuracy metrics  

### For USA Inflation Forecasting (R)
- `forecast` – ARIMA model fitting & forecasting  
- `tseries` – Time-series diagnostics (ADF test, etc.)  
- `ggplot2` – Data visualization  
- `dplyr` – Data manipulation  

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
