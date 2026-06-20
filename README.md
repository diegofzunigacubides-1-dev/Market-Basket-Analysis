# E-commerce Market Basket Analysis (Apriori Algorithm)

This project implements a **Market Basket Analysis** using the **Apriori Algorithm** on an e-commerce transactional dataset specialized in batteries and power components. The primary objective is to discover hidden product association rules, optimize product placement, and design data-driven cross-selling and up-selling strategies.

## 📊 Business Questions & Hypotheses
The project was structured to address four core business hypotheses:
1. Which products are most frequently bought together?
2. Which items are most commonly purchased as single/isolated products?
3. What concrete opportunities exist to drive cross-selling and up-selling initiatives?
4. What other actionable data-driven insights can support overall business growth?

---

## 📁 Project Architecture

```text
├── data/
│   ├── raw/         # Original, unmodified Kaggle dataset
│   └── processed/   # Cleaned, standardized dataset ready for modeling
├── notebooks/
│   └── market_basket_analysis.ipynb  # Main Jupyter Notebook (EDA & Modeling)
└── README.md        # Project documentation