# Bank Customer Churn Dashboard

## Project Overview
Analyzed customer churn using the Kaggle Bank Churners dataset and built an interactive Tableau dashboard that highlights who leaves, why, and when. Stakeholders can explore churn patterns by demographics, engagement, and tenure.

## Dataset
- Source: Kaggle "Bank Churners"
- Records: 10,127 customers
- Key features: Age, Gender, Marital Status, Education Level, Income Category, Card Category, Months on Book, Transactions, Utilization Ratio, Credit Limit, Total Revolving Balance
- Target: Attrition_Flag (Existing vs Attrited)

## Preprocessing
- Cleaned data and handled missing values in Excel
- Removed unnecessary columns
- Derived new calculated fields (ChurnFlag, Churn Rate, Utilization)
- Exported cleaned CSV: `BankChurners_preprocessed.csv`

## Dashboard Highlights
- KPI tiles: Churn Rate, Total Customers, Average Utilization
- Churn by Age Group: Stacked bar chart with demographic filters
- Transactions vs Churn: Relationship between engagement and churn
- Utilization vs Churn: Dual-line chart showing credit stress effect
- Tenure vs Churn: Dual-axis line chart highlighting peak churn periods
- Interactivity: Global filters, tooltip customization, trend lines

## Tools Used
- **Excel**: Data cleaning and preprocessing
- **Tableau Public**: Dashboard creation and visualization
- **Kaggle**: Dataset source

## Key Insights
- Overall churn rate ~16%
- Highest churn in 40–59 age group
- Customers with <40 transactions/year are at higher risk
- Both low and high credit utilization linked to churn
- Mid-tenure customers (~36 months) most likely to churn

## Future Improvements
- Incorporate behavioral data (payments, rewards)
- Develop predictive churn model using Python or Tableau Analytics
