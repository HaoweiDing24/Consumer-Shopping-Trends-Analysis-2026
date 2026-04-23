#Consumer Shopping Trends Analysis
A Python-based data analysis project focused on exploring consumer shopping behaviors, uncovering correlations between demographics, spending patterns, and channel preferences to support retail business decisions.

#Problem Statement
This project aims to address core retail business questions:
1.Explore the relationship between age distribution and consumer shopping behaviors
2.Compare preferences and spending differences between online/offline shopping channels
3.Analyze correlations among key metrics: monthly income, discount sensitivity, impulse buying, and brand loyalty
4.Identify actionable insights for retail operations and marketing strategies

#Core Questions
•Do consumers prefer online or offline shopping? What are the spending power differences between channels?
•Do age and income significantly impact consumption habits and decision-making?
•Are there group differences in behaviors like discount sensitivity and impulse buying?

#Data Description
•Dataset: Consumer_Shopping_Trends_2026.csv from Kaggle

#Methods & Workflow
This project adopts a standard data analysis pipeline implemented in Python:
#1. Dependencies
•pandas: Data loading, cleaning, and preprocessing
•matplotlib / seaborn: Data visualization
•jupyter notebook: Interactive code execution
#2. Analysis Steps
1.Data Loading & Exploration: Inspect data structure and basic statistics
2.Data Cleaning: Deduplication, outlier handling, and missing value validation
3.Univariate Analysis: Age distribution and shopping channel proportion statistics
4.Multivariate Comparison: Age group vs. consumer behavior; online vs. offline spending
5.Correlation Analysis: Heatmaps and scatter plots to identify variable relationships
6.Visualization: Histograms, pie charts, box plots, and scatter plots for insight presentation


#Key Findings
1.Channel Preference: Offline shopping dominates with 86.9% of preferences; offline spending median is slightly higher than online
2.Age Characteristics: User age follows a normal distribution, concentrated between 30-70 years, ensuring strong sample representativeness
3.Behavioral Commonality: Discount sensitivity and impulse buying scores show no significant differences across age groups—these are universal consumer traits
4.Weak Correlations: Monthly income has a weak positive correlation with online spending; discount sensitivity shows nearly no linear correlation with other consumption metrics
5.Spending Patterns: High-income and middle-to-older age groups tend to have higher online spending, though overall correlation remains weak


#How to run
Ensure Python 3.7+ is installed, then install dependencies:
pip install pandas matplotlib seaborn
