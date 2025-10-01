# 📈 Stock Price Analysis with Moving Average Crossover Strategy

This project implements a simple **trading strategy** based on moving average crossovers.  
It uses Python to fetch stock price data, calculate moving averages, and visualize **buy/sell signals**.

---

## 🔹 Features
- Fetches **6 months of stock price data** from Yahoo Finance.
- Calculates:
  - **20-day Simple Moving Average (SMA-20)**
  - **50-day Simple Moving Average (SMA-50)**
- Implements a **crossover strategy**:
  - **Buy Signal (▲)** when SMA-20 crosses above SMA-50.
  - **Sell Signal (▼)** when SMA-20 crosses below SMA-50.
- Visualizes:
  - Stock closing price
  - Moving averages
  - Buy/Sell signals on the chart

---

## 📊 Example Output
- **Plot 1:** Closing price with SMA-20 and SMA-50  
- **Plot 2:** Buy/Sell signals shown on crossover points  

Please Note :- *(Default ticker: `AAPL` — Apple Inc.)*  , Can be obtained for other stocks as well . 

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

Install required libraries:
pip install pandas yfinance matplotlib seaborn

Launch Jupyter Notebook:
jupyter notebook

Open the notebook file and run the cells to see the results.
📦 Requirements
Python 3.8+
pandas
yfinance
matplotlib
seaborn

📝 License

This project is open-source and free to use for learning and research purposes.
