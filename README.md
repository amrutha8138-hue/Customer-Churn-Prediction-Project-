# Telco Customer Churn Prediction

Predicting customer churn using the IBM Telco dataset.

## Key Insights
- Customers on **Month-to-month contracts** churn significantly more.
- **Fiber optic** internet service has higher churn rates.
- **Low tenure** (new customers) and lack of services like Online Security/Tech Support increase churn risk.
- Top predictive features: Contract, Tenure, MonthlyCharges, InternetService.

## Models
- **Logistic Regression**: Accuracy 80.2%, ROC-AUC 0.85
- **Decision Tree**: Accuracy 79.2% (provides clear feature importance)

## Requirements
- Python 3
- pandas, numpy, matplotlib, seaborn, scikit-learn

## Notebook
Run the Jupyter notebook `Customer_Churn_Prediction.ipynb` in Google Colab or locally.
