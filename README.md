# Bank Loan Analysis Dashboard

## Project Overview
This Power BI dashboard analyzes a comprehensive dataset of 82,000+ bank loans to identify key risk factors and lending patterns. The dashboard provides actionable insights into loan performance, borrower characteristics, and default risk indicators to support data-driven lending decisions.

## Dataset
The dataset contains detailed information about bank loans including:
- Loan status (fully paid vs charged off)
- Credit scores
- Loan amounts
- Income information
- Home ownership status
- Loan purpose
- Credit history
- Employment information
- Debt information

## Key Features
- **Loan Status Overview**: Visual breakdown of fully paid (77%) vs charged off loans (23%)
- **Credit Score Analysis**: Correlation between credit scores and default risk
- **Purpose Analysis**: Default rates by loan purpose, highlighting debt consolidation loans
- **Financial Metrics**: Debt-to-income ratios, credit utilization rates, and optimal loan amounts
- **Interactive Filtering**: Segment loan performance by borrower and loan characteristics

## Dashboard Insights
![image](https://github.com/user-attachments/assets/72cfe479-c1ee-48b4-b5d2-1e14d60468e1)

*Distribution of loan statuses showing 77% fully paid and 23% charged off loans*

![image](https://github.com/user-attachments/assets/3b4833d9-aa91-4c04-8266-256244c18ef7)

*Analysis of loan purpose showing debt consolidation as highest risk category*

![image](https://github.com/user-attachments/assets/f80f638c-15e3-401d-99fb-1c57c7dcc5da)

*Correlation between credit scores and default rates*

![image](https://github.com/user-attachments/assets/04e1f5cf-47a3-41e8-85c4-b39dc651d73c)

*Monthly debt distribution across different loan statuses*

## Custom DAX Measures
The dashboard incorporates several advanced DAX measures including:
- Default Rate by Purpose
- Debt-to-Income Ratio
- Credit Utilization Rate
- Risk Score Calculation
- Optimal Loan Amount

## Business Impact
This dashboard enables stakeholders to:
- Identify high-risk borrower profiles
- Optimize lending criteria
- Improve loan portfolio performance
- Make data-driven decisions on lending strategies

## Technical Implementation
- **Data Source**: Kaggle Bank Loan Status Dataset
- **Tool**: Microsoft Power BI
- **Data Transformation**: Power Query Editor
- **Calculations**: DAX measures and calculated columns
- **Visualizations**: Interactive charts, tables, and KPI cards
