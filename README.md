# Customer Churn Prediction (Bank Customers)

## Task Objective
Predict which bank customers are likely to leave (churn) using demographic and account information. The goal is to help the bank take preventive actions and improve customer retention.

## Approach
- **Data Understanding & Cleaning:** Explored dataset, checked for missing values and duplicates, encoded categorical variables, and split into training and testing sets.
- **Exploratory Data Analysis (EDA):** Analyzed numerical and categorical features, studied relationships with churn, and observed feature correlations.
- **Model Training & Testing:** Implemented Logistic Regression (baseline) and Random Forest (advanced). Evaluated models using accuracy, precision, recall, and F1-score.
- **Feature Importance & Insights:** Identified key drivers of churn such as Balance, Tenure, and Activity Level. Extracted actionable insights for retention strategies.

## Results & Insights
- **Best Model:** Random Forest
  - Accuracy: 87%
  - Precision (churners): 0.77
  - Recall (churners): 0.46
  - F1-score (churners): 0.57
- **Key Drivers of Churn:**
  - Low balance, short tenure, inactive membership
  - Customers with fewer products are more likely to churn
  - Geographic trends (higher churn in Germany and Spain)
- **Business Recommendations:**
  - Target high-risk customers with engagement campaigns
  - Cross-sell products to increase retention
  - Implement region-specific strategies
- **Limitations & Next Steps:**
  - Dataset lacks behavioral/transactional features
  - Recall for churners can be further improved
  - Future work: Advanced models, hyperparameter tuning, oversampling, and feature engineering

## Author
- Rimsha Iram
- [Check Portfolio](https://www.datascienceportfol.io/rimshairamanalytics)
- Let’s connect on [LinkedIn](https://www.linkedin.com/in/rimsha-iram-analytics)
