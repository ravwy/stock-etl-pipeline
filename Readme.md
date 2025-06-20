# 📈 Stock ETL Pipeline & Visualization

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)](https://www.python.org/)
[![matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?logo=plotly)]
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Last Updated](https://img.shields.io/badge/Updated-2025-green)]()

This project fetches real-time stock data using `yfinance`, processes it to compute 7-day moving averages, and visualizes the top 10 most active stocks in beautiful subplots — perfect for trend spotting and portfolio nerding. 📊🚀


## 🔄 What It Does

- **Extract**: Pulls 1 month of daily price data for 10 major stocks from Yahoo Finance.
- **Transform**: Calculates the 7-day moving average of closing prices to smooth out volatility.
- **Load & Visualize**: Generates a stylized 2x5 grid plot comparing each stock’s price against its moving average, and saves the output image for use in reports or dashboards.




---

## ⚙️ Features

- 📥 Real-time data fetching with `yfinance`
- 🔄 ETL pipeline to extract, transform, and visualize
- 📉 Trend charts with 7-day moving averages
- 🎨 Colorful grid-style comparison of 10 tickers
- 💾 Saves your chart for sharing or dashboarding

---

##  📈 Stock ETL Pipeline & Visualization

> Visualization of 7-day moving averages across 10 major tech stocks:

![Top 10 Stocks](https://raw.githubusercontent.com/ravwy/stock-etl-pipeline/main/visualizations/top10_stocks.png)




This project extracts live stock market data using `yfinance`, processes it by calculating 7-day moving averages, and visually compares the top 10 most active stocks in a grid of subplots. It's perfect for spotting trends at a glance and showcasing real-time financial analytics using Python.

---
