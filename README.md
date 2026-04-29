# 📊 Portfolio Risk & Return Analysis (NSE Stocks)

## 🚀 Project Overview

This project performs a comprehensive **Portfolio Risk & Return Analysis** using historical stock data from the Indian stock market.

The goal is to evaluate:

* Risk vs Return trade-offs
* Portfolio optimization strategies
* Diversification benefits
* Performance comparison against benchmark (**NIFTY 50**)

This project is built to simulate real-world financial analysis used in asset management and investment research.

---

## 📁 Dataset

* **Source:** `yfinance` Python library
* **Market:** NSE (India)
* **Time Period:** Jan 2020 – Dec 2025
* **Frequency:** Daily adjusted closing prices

### 📌 Stocks Used (Ticker-Based Naming)

* HDFC (`HDFCBANK.NS`)
* ICICI (`ICICIBANK.NS`)
* TCS (`TCS.NS`)
* INFY (`INFY.NS`)
* RELIANCE (`RELIANCE.NS`)
* MARUTI (`MARUTI.NS`)
* LT (`LT.NS`)
* HUL (`HINDUNILVR.NS`)
* Benchmark: NIFTY50 (`^NSEI`)

---

## ⚙️ Tools & Technologies

* **Python**
* **pandas & numpy** → Core calculations
* **matplotlib & seaborn** → Data visualization
* **plotly** → Interactive charts
* **yfinance** → Data extraction

---

## 🔍 Methodology

### 1. Data Collection & Cleaning

* Extracted adjusted close prices
* Handled missing values using forward fill
* Structured dataset for analysis

### 2. Return Analysis

* Daily returns using `pct_change()`
* Cumulative returns for long-term growth comparison

### 3. Risk Analysis

* Annualized Volatility & Variance
* Beta (vs NIFTY50 benchmark)
* Value at Risk (VaR 95%)

### 4. Correlation & Diversification

* Correlation matrix across all stocks
* Identification of diversification opportunities

### 5. Portfolio Construction

* Equal-weight portfolio
* Monte Carlo Simulation (10,000 portfolios)
* Risk vs Return distribution

### 6. Efficient Frontier

* Sharpe Ratio calculation (Rf = 6.5%)
* Identification of:

  * Maximum Sharpe Portfolio (Optimal)
  * Minimum Volatility Portfolio (Safest)

### 7. Rolling Analysis

* 30-day & 90-day rolling volatility
* Rolling correlation with benchmark

### 8. Drawdown Analysis

* Maximum drawdown calculation
* Downside risk visualization

---

## 📊 Key Insights

* 📈 **Best Performing Stock:** (Highest Annual Return)
* 🛡️ **Least Risky Stock:** (Lowest Volatility)
* ⚖️ **Best Risk-Adjusted Stock:** (Highest Sharpe Ratio)
* 🔄 **Most Diversifying Stock:** (Lowest correlation with portfolio)
* 🧠 **Optimal Portfolio:** Derived using Monte Carlo Simulation

---

## 📈 Visualizations

* Cumulative Returns Comparison
* Correlation Heatmap
* Efficient Frontier (Interactive)
* Monte Carlo Portfolio Simulation
* Rolling Volatility Trends
* Drawdown Analysis

---

## 🧠 Conclusion

This project demonstrates how quantitative techniques can be applied to:

* Optimize portfolio allocation
* Measure and manage financial risk
* Identify diversification opportunities

It reflects practical skills used in:

* Portfolio Management
* Equity Research
* Financial Data Analysis

---

## 🛠️ How to Run the Project

```bash
pip install yfinance pandas numpy matplotlib seaborn plotly
```

```bash
jupyter notebook
```

Run all cells sequentially.

---

## 📌 Future Improvements

* Add transaction costs & rebalancing strategy
* Integrate macroeconomic indicators
* Build dashboard using Power BI / Streamlit
* Apply machine learning for return prediction

---

## 👤 Author

**[Shubham Roy]**
Aspiring Data Analyst 

---

## ⭐ If you found this useful

Give this repo a star ⭐ and feel free to connect!
