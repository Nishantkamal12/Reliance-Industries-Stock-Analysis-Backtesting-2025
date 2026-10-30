# 📈 Reliance Industries Stock Analysis & Backtesting (2025)

A Python-based quantitative financial analytics project analyzing **Reliance Industries (`RELIANCE.NS`)** 2025 stock data.

## 🛠️ Tech Stack & Libraries
* **Python** 
* **Pandas** (Data manipulation & time-series) 
* **NumPy** (Vectorized conditions) 
* **yfinance** (Data extraction) 
* **Matplotlib** (Visualizations)

## 📊 Features & Workflow
1. **Data Collection:** Fetches daily `Date`, `Open`, `High`, `Low`, `Close`, `Adj Close`, and `Volume` via Yahoo Finance.
2. **Returns & Metrics:** Calculates daily price differences and fractional returns using Pandas lagging (`.shift()`).
3. **Trend Classification:** Uses **NumPy** and native Python **List Comprehensions** to label market directions.
4. **Technical Indicators:** Computes 20-Day Simple Moving Average (SMA), Exponential Moving Average (EMA), and 10-Day Volatility.
5. **Algorithmic Strategy:** Backtests a Moving Average crossover strategy against a standard **Buy & Hold** benchmark.
6. **Visualizations:** Plots price trends, strategy wealth growth curves, and daily P&L distribution charts
