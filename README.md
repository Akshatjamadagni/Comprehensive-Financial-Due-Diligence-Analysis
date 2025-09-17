# 📊 Comprehensive Financial Due Diligence Analysis

This project performs **comprehensive financial due diligence** and **portfolio optimization** on a selected universe of technology stocks.  
It integrates **fundamental analysis**, **quantitative modeling**, and **portfolio benchmarking** against the S&P 500.

---

## 🚀 Project Overview

- Extracts and processes financial data (market cap, valuation ratios, risk metrics).
- Computes composite **recommendation scores** and investment signals.
- Constructs an **optimized portfolio** using calculated weights.
- Benchmarks portfolio performance against the **S&P 500** using Sharpe ratio, CAGR, and drawdown analysis.
- Provides a **professional PDF report** with results, tables, and inferences.

---

## 📂 Repository Structure

```
├── recommendation_scores.csv   # Composite scores and Buy/Hold/Sell recommendations
├── optimal_weights.csv         # Optimized portfolio weights for each stock
├── fundamentals_summary.csv    # Financial ratios and health score summary
├── PROJECT_REPORT_FA.pdf       # Final project report (LaTeX compiled)
├── PROJECT_FA.ipynb            # Jupyter Notebook with full analysis
└── README.md                   # Project documentation
```

---

## 📑 Key Results

- **Top Recommendation:** GOOGL  
- **Optimized Portfolio Weights:** Concentrated in GOOGL and NVDA  
- **Portfolio CAGR:** 78.7% vs. Benchmark CAGR: 19.3%  
- **Sharpe Ratio:** 1.43 (strong risk-adjusted performance)  

---

## ⚙️ Requirements

- Python 3.9+
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `yfinance`, `scikit-learn`

---

## 📘 Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/Akshatjamadagni/Comprehensive-Financial-Due-Diligence-Analysis.git
   cd Comprehensive-Financial-Due-Diligence-Analysis

   ```

2. Open the notebook:
   ```bash
   jupyter notebook PROJECT_FA.ipynb
   ```

3. Explore results or view the precompiled PDF report:
   ```
   PROJECT_REPORT_FA.pdf
   ```

---

## 📈 Inference

The portfolio significantly outperformed the S&P 500 on a risk-adjusted basis, with a higher CAGR and Sharpe ratio, despite moderate drawdowns.
This suggests the optimization framework is effective in identifying superior investment opportunities in the tech sector.
