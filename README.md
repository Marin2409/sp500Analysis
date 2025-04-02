# StockMovementAnalysis

# 📈 Do Stocks Move Together? Industry Trends in the S&P 500

> Data Science Project Exploring Stock Price Correlations  
> By: Jose Marin

## 🚀 Project Overview

This project investigates whether stocks across different industries and within the same industries exhibit similar movement patterns, using data from the **S&P 500**. As one of the most renowned financial benchmarks globally, the S&P 500 tracks 500 large U.S. companies, with over $5.4 trillion in assets tied to its performance (as of December 31, 2020). Our analysis dives into stock price trends, volatility, and returns to uncover what drives performance similarities and differences.

We aim to answer: *Do industry factors dominate stock movements, or are there broader market forces at play?* This project explores time series modeling, stock performance metrics, and the challenges of predicting financial data.

---

## 📊 Dataset

- **Source:** [Kaggle S&P 500 Stocks Dataset](https://www.kaggle.com/datasets/andrewmvd/sp-500-stocks/versions/950?select=sp500_stocks.csv)  
- **Files:**
  - `sp500_companies.csv` - Company details
  - `sp500_stocks.csv` - Daily stock prices
  - `sp500_index.csv` - Index performance
- **Key Features:**
  - Stock prices (Open, High, Low, Close)
  - Volume
  - Company industry/sector
  - Date

---

## 🧠 How to Use This Dataset

- Build a **time series regression model** to predict S&P 500 index values or individual stock prices.
- Analyze **returns, volatility, and correlations** across industries and companies.
- Identify **high and low-performing stocks** within the S&P 500.

---

## 🔍 Key Insights

- Stock price prediction is inherently challenging due to market noise and external factors.
- Feature engineering (e.g., moving averages, volatility measures) can improve model performance incrementally.
- Success in stock analysis requires balancing data-driven insights with realistic expectations about predictability.

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy)
- Jupyter Notebook
- Matplotlib / Seaborn (for visualization)
- Scikit-learn (optional, if modeling is implemented)

---
