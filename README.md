# Fraud Detection on Credit Card Transactions 

## Dataset
- Source: [https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data](#)
- Features: Transactions made by credit cards in September 2013 by European cardholders, flags if Fraud, Fraud, etc.
- Target: Binary classification (fraudulent or non-fraudulent transactions)

## Approach
1. **Data Preprocessing:**
   - Checked for missing values and performed necessary cleaning.
   - Explored class imbalance in the dataset.
2. **Model Selection & Evaluation:**
   - Implemented Logistic Regression, Decision Tree, and Random Forest classifiers.
   - Initially, models returned high accuracy (0.99) but performed poorly on other metrics.
3. **Handling Class Imbalance:**
   - Applied Random Oversampling to balance the dataset.
   - Improved precision, recall, and F1-score.
4. **Final Model Evaluation:**
   - Re-evaluated models on the balanced dataset.
   - Achieved better overall performance across all metrics.
