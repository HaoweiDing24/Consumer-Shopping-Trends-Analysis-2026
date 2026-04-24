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
- No single dominant customer segment exists; a full-age demographic coverage is therefore required.
- Nearly 90% of consumers prefer in-store shopping, proving that offline experience, immediacy and trust are irreplaceable strengths. Shifting entirely to e-commerce would risk losing most target users.
- Discount sensitivity and impulse buying scores are consistent across all age groups.
- No significant linear relationships exist among the variables. Monthly income shows no correlation with online spending, and has negligible impact on discount sensitivity, impulse buying, and brand loyalty. All consumption behaviors are mutually independent.
- Online and offline spending distributions show no significant difference, with consumers' spending power balanced across both channels.

## 5. How to Run
1.  Ensure Python 3.8+ with `pandas`, `matplotlib`, `seaborn` installed.
2.  Place `Consumer_Shopping_Trends_2026.csv` in the same folder as `acc102.ipynb`.
3.  Open the notebook in Jupyter/VS Code and run all cells.


## 6. Limitations & Next Steps
- **Limitations**: No detailed geographic data; weak correlations suggest synthetic data patterns.
- **Next Steps**: Add regression analysis; build an interactive Streamlit dashboard.

---
*ACC102 Mini Assignment*
