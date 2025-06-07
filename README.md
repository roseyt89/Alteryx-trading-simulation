# 📊 Alteryx Trading Simulation Model (Q1 2025)

This repository contains a machine learning-based trading simulation model built in **Alteryx Designer 2025.1.1.27**. The model uses predicted volatility, liquidity indicators, and ranking logic to simulate stock trades across different holding periods (T+1, T+3, T+5) and assess trading performance.

---

## 🚀 Project Summary

This Alteryx workflow:
- Simulates trades using `PriceRank` changes and a custom `BuySignal`
- Predicts trade success based on modeled features like `LitVol` and `HiddenVol`
- Evaluates results using metrics such as MAE, MSE, RMSE
- Categorizes liquidity risk and filters trade candidates
- Outputs a dashboard visualizing average trade success by holding period
