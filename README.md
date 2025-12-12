# End-to-End Telco Customer Churn Prediction

[Click here to view the Dashboard](https://public.tableau.com/views/TelcoCustomerChurnPrediction_17655298877500/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## 1. Business Problem The client faced a 27% churn rate, losing approximately $40k/month in revenue. The goal was to identify at-risk customers and key drivers of attrition to enable targeted retention campaigns.

## 2. Solution

Built an XGBoost Classifier with 78% Recall, prioritizing the identification of churners over simple accuracy.

Implemented Cost-Sensitive Learning (scale_pos_weight) to handle severe class imbalance.

Developed an interactive Tableau Dashboard for the marketing team to visualize high-risk cohorts.

## 3. Key Findings

The "Contract Trap": Month-to-month users have a 42% churn rate, while 2-year contract users have <3%.

Fiber Optic Issues: High-paying Fiber Optic users are the most likely to leave, signaling a price/value mismatch.

## 4. Impact

Identified $40,461 in monthly revenue at risk.

Projected annual savings of ~$70k assuming a 50% success rate in retention offers.
