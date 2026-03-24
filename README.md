# portfolio-optimization-equalweight-minvar-riskparity
# Portfolio Construction and Risk Analysis

## 📌 Project

This project explores different ways to build a portfolio and manage risk.

I compare three allocation methods:
- Equal Weight
- Minimum Variance
- Risk Parity

The goal is to understand whether more advanced strategies actually improve performance compared to a simple approach.

---

## 📊 Data

I used real market data from ETFs:

- SPY (US equities)
- QQQ (tech equities)
- EFA (international equities)
- IEF (bonds)
- GLD (gold)

- Source: yfinance  
- Period: 2015–2025  

---

## ⚙️ Method

Steps followed:

1. Download price data  
2. Compute log returns  
3. Estimate covariance matrix  
4. Build portfolios:
   - Equal Weight
   - Minimum Variance (optimization)
   - Risk Parity  
5. Backtest performance  
6. Analyze risk and return  

---

## 📈 Results

All three strategies produced very similar results in a static framework.

This shows that when market conditions are stable, more complex models do not necessarily outperform simple strategies.

---

## 🧠 What I learned

- portfolio optimization basics  
- role of covariance  
- how to build a backtesting model  
- limits of static models  

---

## 🚀 Next steps

- implement rolling (dynamic) portfolios  
- improve the model  
- test robustness  

---

## 🛠️ Tools

- Python  
- pandas / numpy  
- scipy  
- matplotlib  
- yfinance  

---

## 📄 Report

The full report is available in this repository.

---

## 👤 Author

Rayan Nasloubi
