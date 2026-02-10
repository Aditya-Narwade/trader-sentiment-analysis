# Trader Performance vs Market Sentiment Analysis

## Overview

This project analyzes how trader behavior and profitability change under different market sentiment conditions (Fear / Greed).  
The goal is to uncover behavioral patterns that can inform smarter trading strategies.

This assignment simulates a real-world data science workflow:
data cleaning → analysis → segmentation → actionable insights.

---

## Objective

Analyze the relationship between market sentiment and trader performance on Hyperliquid, and derive strategy recommendations based on observed behavior.

---

## Datasets

1. Bitcoin Market Sentiment (Fear / Greed Index)
2. Historical Trader Execution Data

The datasets were aligned at a daily level and merged to connect trader actions with sentiment conditions.

---

## Methodology

- Cleaned timestamps and handled missing values
- Standardized date formats across datasets
- Merged trader activity with sentiment data
- Created performance metrics (PnL, trade size, frequency)
- Compared behavior across sentiment regimes
- Segmented traders by activity and position size
- Built a simple predictive model (bonus)

---

## Key Insights

- Traders earn the highest average PnL during Greed phases
- Fear markets show lower profitability and higher volatility
- Larger trade sizes amplify both gains and losses
- Frequent traders outperform infrequent traders
- Sentiment influences trading behavior and profitability patterns

---

## Strategy Recommendations

**Rule 1 — Position sizing based on sentiment**

Reduce position size during Fear / Neutral markets to control downside risk.  
Increase exposure selectively during Greed phases when profitability is higher.

**Rule 2 — Trade frequency filtering**

Increase trade activity during Greed sentiment.  
Avoid overtrading in Fear markets where expected returns are lower.

---

## Bonus: Predictive Model

A simple Random Forest classifier was trained to predict profitability bucket using sentiment and behavioral features.

Model accuracy ≈ **62%**

This indicates that trader behavior + market sentiment contain predictive signal that could be improved with advanced modeling.

---

## How to Run

1. Open the notebook in Google Colab or Jupyter
2. Upload datasets to the working directory
3. Run all cells in order

Notebook file:
`trader_sentiment_analysis.ipynb`

---


---

## Conclusion

Market sentiment significantly influences trader behavior and performance.  
Fear vs Greed regimes create measurable differences in risk-taking and profitability, enabling data-driven strategy adjustments.

---

## Author

Aditya Narwade  
Data Science Internship Assignment



