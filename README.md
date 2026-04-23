# Consumer Shopping Trends Analysis 2026

## 1. Problem & User
This project analyzes consumer shopping behavior patterns to identify key trends in spending habits, channel preferences, and demographic correlations. Insights can help retailers optimize product and marketing strategies.

## 2. Data
- **Source**: Kaggle `dsfscfds/consumer-shopping-trend-analysis-2026`
- **Key Fields**:
  - Demographics: `age`, `monthly_income`, `city_tier`
  - Spending: `avg_online_spend`, `avg_store_spend`
  - Preferences: `shopping_preference`, `discount_sensitivity`, `impulse_buying_score`

## 3. Methods
1.  Load and clean data (check missing/duplicate values, filter age range)
2.  Create derived features (`total_spend`, `age_group`)
3.  Generate visualizations: histograms, pie charts, boxplots, correlation heatmap, scatter plots
4.  Interpret results for business insights

## 4. Key Findings
- 86.9% of consumers prefer in-store shopping, with only 10% preferring online-only.
- Age distribution is evenly spread across 18–80 years old.
- No strong correlation between monthly income and online spending.
- Discount sensitivity and impulse buying scores are consistent across all age groups.
- Online and offline spending show nearly identical distributions.

## 5. How to Run
1.  Ensure Python 3.8+ with `pandas`, `matplotlib`, `seaborn` installed.
2.  Place `Consumer_Shopping_Trends_2026.csv` in the same folder as `acc102.ipynb`.
3.  Open the notebook in Jupyter/VS Code and run all cells.

## 6. Product link / Demo
- GitHub Repository: *[Paste your repo link here]*
- Notebook: `acc102.ipynb` (included in this repo)

## 7. Limitations & Next Steps
- **Limitations**: No detailed geographic data; weak correlations suggest synthetic data patterns.
- **Next Steps**: Add regression analysis; build an interactive Streamlit dashboard.

---
*ACC102 Mini Assignment*
