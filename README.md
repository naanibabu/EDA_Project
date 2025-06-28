# Paisabazaar Banking Fraud Analysis

## Project Type
Exploratory Data Analysis (EDA)

## Overview

This project presents an exploratory data analysis (EDA) of Paisabazaar’s customer dataset to identify key factors influencing credit scores. Accurate credit score classification is crucial for financial institutions to assess risk, approve loans, and offer personalized products. The dataset contains 100,000 records and 28 features, including demographic, financial, and behavioral variables.

## Objectives

- Identify and analyze the key factors influencing customer credit scores.
- Improve credit assessment and reduce financial risk for Paisabazaar.
- Provide actionable recommendations for business decision-making.

## Dataset

- **File:** [`dataset.csv`](dataset.csv)
- **Rows:** 100,000
- **Columns:** 28 (demographic, financial, behavioral features)

## Key Steps

1. **Data Cleaning:** Checked for missing values and duplicates.
2. **Feature Engineering:** Created new columns such as `Month_Name` and `Age_Group` for better analysis.
3. **Data Transformation:** Aggregated data at the customer level for concise insights.
4. **Univariate & Bivariate Analysis:** Explored distributions and relationships between variables.
5. **Visualization:** Used histograms, boxplots, bar charts, and heatmaps for storytelling.
6. **Business Recommendations:** Provided actionable insights for credit risk management.

## Main Insights

- Higher annual income, fewer bank accounts, and fewer credit cards are linked to good credit scores.
- High outstanding debt, high EMI per month, and high interest rates are associated with poor credit scores.
- Age and income are significant predictors of creditworthiness.
- Occupation and payment behavior showed little correlation with credit score.

## Recommendations

- Prioritize customers with higher income and fewer credit lines.
- Closely monitor those with high debt and EMI.
- Use age and income as primary features in credit assessment models.
- Offer targeted financial advice to high-risk groups (e.g., younger customers, those with multiple credit cards).

## How to Run

1. Clone this repository or download the files.
2. Ensure you have Python 3.x and the following libraries installed:
   - pandas
   - numpy
   - matplotlib
   - seaborn
3. Open [`PaisabazaarAnalysis.ipynb`](PaisabazaarAnalysis.ipynb) in Jupyter Notebook or VS Code.
4. Run the notebook cells sequentially to reproduce the analysis and visualizations.

## File Structure

- [`PaisabazaarAnalysis.ipynb`](PaisabazaarAnalysis.ipynb): Main analysis notebook.
- [`dataset.csv`](dataset.csv): Customer dataset.
- PNG files: Visualizations used in the notebook.

## Conclusion

This EDA provides actionable insights to help Paisabazaar refine its credit assessment process, reduce financial risk, and deliver better, data-driven recommendations to customers, supporting responsible lending and business growth.

---


