# 📊 Portfolio Tracker – UCLA AIM Project

This project was developed as part of the **Advanced Investment Management (AIM)** course during my semester abroad at **UCLA** (Spring 2025).

## 🎯 Objective
To design, optimize, and evaluate a **multi-asset portfolio** with a $10 million virtual capital using real market data and advanced Python modeling techniques.

## 📌 Assets Included
- Tech Equities: Palo Alto Networks, CrowdStrike, Nvidia, Palantir
- Defense & Industry: Lockheed Martin
- Currencies: EUR/USD, Swiss Franc
- Commodities: Platinum
- Fixed Income: US 5-Year Treasury Yield (^FVX)

## 🧠 Strategy & Analytics
- **Data Source**: Yahoo Finance API (via `requests`)
- **Performance Metrics**: Annual return, volatility, Sharpe ratio
- **Optimization**: Allocation bounded between 5%–20%, using `scipy.optimize` to maximize the Sharpe ratio
- **Tracking**: Daily portfolio value exported via CSV
- **Simulation**: Monte Carlo forecast over 252 trading days
- **Visualization**: Matplotlib plots for portfolio evolution, asset prices, allocations

## 📁 Key Files
- `Portfoliov2.ipynb`: Main notebook with full code logic
- `historical_prices_cleaned_2.csv`: Cleaned time series for selected assets
- `static_portfolio_tracking.csv`: Daily portfolio evolution
- `README.md`: Project overview (you are here)

## 📊 Outputs
- Optimal portfolio weights & 60-day forward expectations
- Portfolio tracking line chart with baseline
- Asset price comparison chart
- Monte Carlo simulation with percentiles and confidence bands

## 🛠 Technologies
- Python 3, Jupyter (Anaconda)
- Libraries: `pandas`, `numpy`, `matplotlib`, `scipy`, `requests`

## 💡 Author
Project by **Ludmila Aboud**, during her exchange semester at **UCLA**, Spring 2025.  
GitHub: [@ludmila-abd](https://github.com/ludmila-abd)

