# Telecom Customer Churn Analysis
## Optimizing Retention Strategies Through Exploratory Data Analysis

## Project Overview
Customer retention is one of the primary growth drivers in the telecommunications 
industry. Acquiring a new customer costs significantly more than retaining an 
existing one. This project analyzes customer demographics, account characteristics, 
and service usage patterns to uncover the root causes of customer attrition (churn).

## Dataset
[Telco Customer Churn (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- 7,043 rows × 21 columns
- Source: IBM Sample Dataset via Kaggle

## Key Findings
1. **Overall churn is 26.54%** — more than 1 in 4 customers leave
2. **High-value customers are leaving** — churned customers pay $74.44/month 
   vs $61.27/month for retained customers
3. **Contract length drives churn:**
   - Month-to-month: ~43% churn
   - 1-year contracts: ~11% churn
   - 2-year contracts: ~3% churn
4. **Early tenure is the danger zone** — churned customers are heavily 
   concentrated in the first 6 months

## Tools Used
- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

## Skills Demonstrated
- Data loading & inspection
- Missing value detection & handling
- Exploratory Data Analysis (EDA)
- Groupby, value_counts, pivot tables
- Data visualization (countplot, boxplot, histplot, heatmap)

## How to View
Open `Telco_data_Visuals.ipynb` to see the full analysis with code, 
visualizations, and findings.
