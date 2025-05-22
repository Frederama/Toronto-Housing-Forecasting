# 🏠 Toronto Housing Market Forecasting

## 🎯 Objective
Forecast the average home prices and number of home sales in the City of Toronto using historical data and time-series modeling techniques. The goal is to support better planning and decision-making in the real estate sector by understanding housing trends.

## 📊 Dataset
- **Source:** Toronto Regional Real Estate Board (TRREB)
- **Time Range:** January 2009 – December 2024
- **Features:** Monthly average home prices, number of home sales

## 🧠 Approach
This project involved building a full end-to-end time series forecasting pipeline:

- Conducted **exploratory data analysis (EDA)** to understand seasonality, trends, and anomalies
- Tested for **stationarity** using ADF test
- Performed **differencing** to stabilize variance
- Evaluated multiple models:  
  - **Exponential Smoothing**  
  - **AR**  
  - **ARIMA**  
  - **SARIMA** (Selected final model)
- Performed **forecasting** through 2024 using best-fit SARIMA model
- Assessed model performance using metrics such as **MAPE** and visual inspection of residuals

## 📈 Results
- **Best Model:** SARIMA  
- **Forecast Accuracy:** MAPE of 5.19% for prices and 37.87% for sales on test set  
- Captured key seasonal patterns and long-term upward trends  
- Generated reliable forecasts to inform housing affordability and investment planning

## 🛠 Tools Used
`Python` · `Pandas` · `Matplotlib` · `Seaborn` · `Statsmodels` · `pmdarima` · `Jupyter Notebook`

## 📎 References
- Toronto Regional Real Estate Board (TRREB)
- [pmdarima Documentation](https://alkaline-ml.com/pmdarima/)
- Forecasting Principles and Practice by Rob J Hyndman

---

📁 *Check out the full code and notebook in this repository!*
