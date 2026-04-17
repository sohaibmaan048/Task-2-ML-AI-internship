# 📈 Stock Price Prediction (Short-Term)  

Predicting next day closing prices using Machine Learning models.

---

## 📌 Overview  

This project focuses on predicting the **next day's closing stock price** using historical data.  
The dataset is fetched using the `yfinance` API, and models are trained using regression techniques.

---

## 🎯 Objective  

- Use historical stock data  
- Predict next day's closing price  
- Compare model performance  

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

```python
import yfinance as yf

df = yf.download("AAPL", start="2020-01-01", end="2024-01-01")
