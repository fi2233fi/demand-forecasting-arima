# 📦 Demand Forecasting Using ARIMA

This project applies traditional time series forecasting techniques to predict daily order demand for a logistics company. Using ARIMA (AutoRegressive Integrated Moving Average), we analyze patterns and forecast demand over a short-term horizon to help businesses optimize operations and planning.

## 📊 Project Overview

- **Objective:** Forecast daily total orders for 10 future days
- **Model:** ARIMA(1, 0, 1)
- **Tools:** Python, Pandas, Matplotlib, Statsmodels
- **Dataset:** Daily demand orders from a Brazilian logistics company

## 📁 Files

- `demand_forecasting.ipynb` – Jupyter Notebook with full analysis and ARIMA model
- `Daily_Demand_Forecasting_Orders.xlsx` – Dataset used

## 🧠 Key Steps

1. Load and explore the data
2. Visualize trends in daily order volume
3. Check stationarity using Augmented Dickey-Fuller test
4. Train and evaluate ARIMA(1, 0, 1)
5. Forecast next 10 days of demand and plot results

## 📈 Output

> The ARIMA model captured short-term trends well and produced a realistic 10-day forecast, valuable for logistics operations and resource planning.

## 🚀 Future Improvements

- Compare ARIMA to Prophet or LSTM
- Add holiday/seasonality features
- Convert to an interactive Streamlit app

---

## 👩‍💻 Author

**Fatima Iqbal**  
Data Science & Machine Learning Portfolio  
[GitHub: fi2233fi](https://github.com/fi2233fi)

