# 📈 Stock Price Prediction using LSTM

This project implements a deep learning model using LSTM (Long Short-Term Memory) networks to predict stock prices. The data used is historical stock data from **Apple Inc. (AAPL)**, collected using the `yfinance` library.

---

## 🔍 Project Overview

- **Goal**: Predict the closing price of AAPL stock using past 60 days’ historical data.
- **Model Used**: LSTM (a type of Recurrent Neural Network)
- **Tools**: Python, Google Colab, Keras, TensorFlow, Matplotlib, yfinance

---

## 📊 Dataset

- **Source**: [Yahoo Finance](https://finance.yahoo.com/)
- **Ticker**: AAPL
- **Time Frame**: 2015-01-01 to 2024-12-31
- Downloaded using `yfinance.download()`.

---

## 🧠 Model Architecture

- Input: Last 60 days' stock prices
- LSTM layers with dropout
- Dense output for predicting next day's price

---

## 🔗 How to Use

1. Clone the repo or open the `.ipynb` file in Google Colab.
2. Run the notebook step by step.
3. Graphs and predictions will be displayed at the end.

---

## 📁 Files Included

- `Stock_Price_Prediction_LSTM.ipynb`: Full implementation and model
- `README.md`: Project description

---

## ✅ Result

- The LSTM model effectively learned trends from historical stock data and predicted the next closing price.
- A line plot shows actual vs predicted prices.

---

## 📬 Contact

Created by **Devesh Dwivedi**  
GitHub: [Devesh7758](https://github.com/Devesh7758)
