# PrimeTrade – Sentiment-Driven Trading Behavior Analysis  
### Name: Aravindh R

This repository contains my data analysis and insights for the PrimeTrade trading-sentiment assignment.  
All work follows the required folder structure and was executed in Google Colab.

---

## 📁 Repository Structure

ds_Aravindh_R/  
├── notebook_1.ipynb                # Main analysis notebook (Colab)   
├── csv_files/                      # All data files  
│   ├── historical_data_1.csv  
│   ├── historical_data_2.csv  
│   ├── fear_greed_index.csv  
│   ├── merged_data_1.csv  
│   ├── merged_data_2.csv  
│   ├── merged_data_3.csv  
│   └── daily_metrics_data.csv  
├── outputs/                        # All charts and graphs  
│   └── *.png
├── ds_report.pdf                   # Final summary report  
└── README.md                       # Documentation (this file)

---

## 📌 Objective

To analyze how trading behavior (volume, risk, profitability, buy/sell bias) aligns or diverges from  
market sentiment (Fear ↔ Greed), and to uncover hidden behavioral signals that could support  
smarter trading strategies.

---

## 📊 What This Project Covers  

### **1. Data Preprocessing**
- Loaded trading history & sentiment index  
- Converted timestamps & merged datasets  
- Removed unknown sentiment rows  
- Created daily-level aggregated dataset  

---

### **2. Behavioral Feature Engineering**
Derived features include:

- **Daily Trading Volume (USD)**  
- **Trades per Trader**  
- **Total Trades per Day**  
- **Average Execution Price**  
- **Closed PnL (Daily & Per Sentiment)**  
- **Buy/Sell Ratio**  
- **PnL Volatility (Std Dev)**  

---

### **3. Sentiment-Driven Insights**
Visual analysis includes:

- Trading Volume vs Sentiment  
- Trades per Trader vs Sentiment  
- Execution Price Differences  
- Profitability Trends (by date & sentiment value)  
- Risk/Volatility under different sentiments  
- Buy/Sell bias in Fear vs Greed  
- Volume and PnL vs Sentiment Value (0–100)  

All corresponding graphs are stored in `/outputs/`.

---

## 🔗 Google Colab Notebook Link  
**notebook_1:**  
https://colab.research.google.com/drive/1asm9q4pPjezIGB1mGK6cha3OZJXTChU7?usp=sharing

---

## 📄 Final Report  
A clean PDF summary of methodology and insights is included as:  
`ds_report.pdf`

---

## 🧑‍💻 Contact  
Aravindh R  
Email: *arvindhjeswin@gmail.com*
