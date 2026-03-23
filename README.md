
# JPY/USD: The Uncovered Interest Rate Parity (UIP) Puzzle

Does the theory of **Uncovered Interest Rate Parity** actually hold up in the real world, or is it just a textbook fantasy? 

This project analyzes 15 years of JPY/USD data to see if interest rate differentials can actually predict currency movements—or if the "Carry Trade" is just a trap for the unwary.

---

## 🔍 What’s Inside?

This repository contains a full end-to-end analysis, from raw data to trading simulations:

* **The Data:** 12-Month Money Market rates and JPY/USD spot prices.
* **The Math:** OLS regressions testing the relationship across daily and monthly frequencies.
* **The "Fama Puzzle":** A deep dive into why the theory often flips on its head.
* **Rolling Regressions:** Visualizing how the "Beta" of the market shifts through different economic regimes (2012–2025).
* **The Strategy:** A backtest of a "Pure Carry Trade" to see if a $\beta = 0$ environment is actually "free money" or a "black swan" waiting to happen.

---

## 📈 The Big Questions
1.  Does UIP work better if you zoom out from daily to monthly data?
2.  What happens to a trading strategy when a "low-rate" currency suddenly becomes "high-rate"?
3.  Is the exchange rate a random walk, or is there a signal in the noise?

---

### How to use
Download the html file with all our analysis
Read the PDF assignment
Simply clone the repo and run the notebook to see the results of the regression and whether the trading strategy survived the 2024-2025 regime shift.

---
