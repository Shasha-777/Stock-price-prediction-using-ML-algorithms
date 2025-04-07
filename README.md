# Stock-price-prediction-using-ML-algorithms
# 📈 Time Series Forecasting of AAPL Stock Prices

## 🧠 Project Overview

This project focuses on predicting future stock prices of Apple Inc. (AAPL) using time series forecasting techniques. It simulates a real-world financial modeling scenario for investment analysis, risk management, and algorithmic trading strategies.

---

## 📊 Dataset Description

The dataset includes daily stock data from **April 2023 to April 2024**, containing:
- `Date`: Trading day
- `Open`, `High`, `Low`, `Close`: Price metrics
- `Adj Close`: Adjusted closing price
- `Volume`: Trading volume

A total of **252 trading days** were used, making it suitable for annual financial forecasting.

---

## 🎯 Objective

To forecast **future closing prices** (`Close`) of AAPL using ARIMA models and provide strategic insights for production deployment.

---

## 🔍 Process Overview

1. **Exploratory Data Analysis (EDA)**
   - Distribution checks, correlation matrix, trend visualization
2. **Feature Engineering**
   - Created predictors and ensured proper transformations
3. **Modeling**
   - Used ARIMA for its interpretability and time-series capability
4. **Evaluation**
   - Validated using Mean Squared Error (MSE)
5. **Production Suggestions**
   - Outlined deployment guidelines with monitoring advice

---

## 📌 Key Findings

- **Trading Volume** showed bimodality → Suggests inconsistent activity
- **ARIMA** could detect general trends but not rapid volatility
- **Box plots** showed trading outliers, aiding in identifying abnormal trading days

---

## 📉 Model Summary

- **Type**: Univariate Time Series Forecasting
- **Model**: ARIMA
- **Split**: 80/20 train-test
- **Metric**: MSE

---

## 📈 Visual Insights

- Histograms of price distributions
- Boxplots highlighting outliers
- Line charts for predicted vs actual prices
- Confidence intervals for forecast uncertainty
- Moving averages for trend smoothing
- Learning curves for training diagnostics

---

## 🔬 Technical Highlights

- Time series preprocessing
- ARIMA parameter tuning
- Visual diagnostics of fit vs residuals
- Confidence band visualization

---

## 🏁 Future Directions

- Include **external factors** (e.g., news sentiment, macroeconomic indicators)
- Integrate **machine learning models** like LSTM, XGBoost
- Build a **Streamlit app** for real-time forecasting

---

## 👤 Author

**Shashanka Oruganti**  
Data Science Graduate | Forecasting & Analytics Enthusiast  
📫 orugantishashanka@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/shashanka-oruganti-136710293)

---

