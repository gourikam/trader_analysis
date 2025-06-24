# Junior Data Scientist – Trader Behavior Insights

This repository contains my completed data science assignment for the **Junior Data Scientist** role. The goal was to analyze trader behavior in relation to **Bitcoin market sentiment** (Fear/Greed Index) using historical trade execution data.

---

## Repository Contents

- `analysis.ipynb` – Jupyter notebook with data cleaning, exploration, ML modeling, and insights.
- `historical_data.csv` – Hyperliquid trader execution dataset.
- `fear_greed_index.csv` – Bitcoin market sentiment dataset (Fear/Greed classification).
- `README.md`, `LICENSE`

---

## Objective

To explore the relationship between **market sentiment** and **trader performance**, identify patterns across traders, and develop data-driven insights that could power smarter trading strategies.

---

## Key Highlights

- **Data Integration**: Merged sentiment data with timestamped trade logs by date.
- **EDA**:
  - Closed PnL and win rate distributions across sentiment types.
  - Trader-wise breakdowns of performance under "Fear" vs "Greed".
- **Machine Learning**:
  - Built a Random Forest Classifier to predict profitable trades.
  - Achieved ~`84.48% accuracy` using execution price, size, and sentiment as features.
- **Visuals**:
  - Trend line of average PnL over time.
  - Feature importance in trade profitability.

---

## How to Run This Notebook

1. Clone the repo:
   ```bash
   git clone https://github.com/gourikam/trader_analysis.git
   cd trader_analysis
