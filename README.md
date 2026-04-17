# 📈 Stock Price Prediction (Short-Term)

Predicting the next day's closing price using Machine Learning models with historical stock market data.

---

## 📌 Project Overview

This project uses historical stock data fetched from Yahoo Finance to predict the next day's closing price. The goal is to compare different regression models and analyze their performance.

---

## 🎯 Objective

- Predict next day's closing price of a stock  
- Use Open, High, Low, Volume as input features  
- Train and compare Linear Regression and Random Forest models  
- Evaluate performance using error metrics and R² score  

---

## 🧰 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- yfinance  

---

## 📥 Data Collection

Stock data is collected using the `yfinance` API.

```python
import yfinance as yf

df = yf.download("AAPL", start="2020-01-01", end="2024-01-01")
df.head()
