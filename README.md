# 📈 Stock Price Analysis on GOLDMAN SACHS and Prediction using Machine Learning
## 📌 Project Overview

This project focuses on analyzing historical stock market data and predicting the closing price of a stock using machine learning techniques. Exploratory Data Analysis (EDA) is performed to understand price trends, trading volume, and volatility, followed by predictive modeling using Linear Regression and Polynomial Regression.

## 🎯 Objectives

- To analyze historical stock price behavior using EDA

- To identify trends, volatility, and trading patterns

- To build regression models for predicting stock closing prices

- To compare Linear and Polynomial Regression performance

## 📂 Dataset

The dataset contains historical stock data with the following features:

1. Date

2. Open price

3. High price

4. Low price

5. Close price

6. Adjusted close price

7. Trading volume

The data is cleaned by handling missing values, removing duplicates, and validating price consistency.

## 🧹 Data Preprocessing

1. Converted date column to datetime format

2. Sorted records chronologically

3. Removed duplicate dates

4. Checked invalid OHLC values

5. Created new features:

6. Price Range (High − Low)

7. Daily Return using percentage change

## 📊 Exploratory Data Analysis (EDA)

1. EDA was performed to gain insights into stock behavior:

2. Closing price trend over time

3. Trading volume analysis and spike detection

4. Distribution of daily returns (volatility analysis)

5. Moving average (5-day) trend analysis

6. Correlation analysis between price and volume

7. Bullish vs Bearish market classification

## 🤖 Model Building
### 1️⃣ Linear Regression

1. Features: Open, High, Low, Volume

2. Target: Closing Price

3. Evaluation Metrics:

4. Mean Squared Error (MSE)

5. R² Score

### 2️⃣ Polynomial Regression (Degree 2)

1. Applied polynomial feature transformation

2. Captured non-linear relationships

3. Evaluated using MSE and R² Score

# 📈 Model Comparison
## Model	Performance
1. Linear Regression	Captures general trend but limited accuracy
2. Polynomial Regression	Better fit with lower error and higher R²

### Polynomial Regression performed better due to its ability to model non-linear price patterns.

## ✅ Results & Conclusion

1. Stock prices exhibit non-linear behavior

2. Trading volume shows occasional spikes during high activity periods

3. Polynomial Regression provided more accurate predictions than Linear Regression

4. EDA played a crucial role in understanding stock trends and volatility

## 🛠️ Technologies Used

1. Python

2. Pandas

3. NumPy

4. Matplotlib

5. Scikit-learn

## 🚀 Future Improvements

1. Add technical indicators (RSI, MACD, Bollinger Bands)

2. Use time-series models like ARIMA or LSTM

3. Include external factors such as news sentiment and economic indicators

