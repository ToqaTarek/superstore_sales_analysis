# 🛒 Superstore Sales Analysis

**Dataset:** Sample Superstore (9,994 orders · 2014–2017)
**Tools:** Python · Pandas · Plotly · NumPy
**Goal:** Clean, explore, and extract actionable business insights from retail sales data.

## 📋 Table of Contents

1. Data Loading & Overview
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Business Insights
5. Interactive Visualizations

## 📌 Key Findings

| # | Insight | Impact |
|---|---------|--------|
| 1 | Discounts >50% = 100% loss rate | 🔴 High |
| 2 | Tables sub-category is unprofitable | 🔴 High |
| 3 | West region leads; Central underperforms | 🟡 Medium |
| 4 | Sales growing YoY but margin declining | 🟡 Medium |
| 5 | Q4 is peak season but prone to over-discounting | 🟡 Medium |

## ✅ Recommended Actions

1. **Cap discounts at 40%** — no exception for any category
2. **Review Tables product line** — reprice or discontinue loss-makers
3. **Audit Central region** — understand why margin lags other regions
4. **Q4 strategy** — build inventory, resist discounting (demand is already high)
5. **Double down on Copiers** — highest margin sub-category

## 📂 Dataset

The notebook expects `Sample - Superstore.csv` (the classic Tableau Sample Superstore dataset) in the working directory.

## 🚀 How to Run

1. Clone the repo
2. Install dependencies:
   ```bash
   pip install pandas numpy plotly
   ```
3. Place `Sample - Superstore.csv` in the project folder
4. Open `Superstore_Analysis.ipynb` and run all cells
