# Module 20 Report

# Overview of the Analysis

The purpose of this analysis was to develop and evaluate machine learning models to predict the loan status based on financial data. The goal was to identify the model that provides the most accurate prediction in order to inform decision-making.

## Financial Information and Prediction

The data used in this analysis can be found in the Credit-Risk Resources file under the name 'lending_data.csv.' The primary objective was to predict the 'loan-status' that indicated wether a loan was a healthy-loan (0) or a high-risk loan (1).

## Key Variables

- 'loan_size': The size of the loan.
- 'interest_rate': The interest rate of the loan.
- 'borrower_income': The income of the borrower.
- 'debt_to_income': The ratio of the borrower's debt to their income.
- 'num_of_accounts': The number of accounts the borrower has.
- 'derogatory_marks': The number of derogatory marks on the borrower's credit report.
- 'total_debt': The total debt of the borrower.

## Machine Learning Process

1. **Data Preprocessing**: Reading in and reviewing the data. Seperating labels and features.
2. **Data Splitting**: Splitting the data into training and testing sets.
3. **Model Training**: Training Logistic Regression model using the training data.
4. **Model Evaluation**: Evaluating the model's preformance using a confusion matric and classification report.

## Methods Used
- **Logistic Regression**: Logisitc regression model was trained and evaluated.

# Results

## Logistic Regression Model

### Accuracy, Precision, and Recall Scores

-**Accuracy:** 99%

-**Precision for class 0 (healthy loan):** 100%

-**Recall for class 0 (healthy loan):** 99%

-**Precision for class 1 (high-risk loan):** 85%

-**Recall for class 1 (high-risk loan):** 91%

# Summary

The logistic regression model performed exceptionally well with an overall accuracy of 99%. The model showed a very high precision (100%) and recall (99%) for predicting healthy loans (class 0). For high-risk loans (class 1), the precision was 85% and recall was 91%.

Based on the preformance metric, the logistic regression is reccomended to predict loan status. This model preforms best in pedicting healthy loans accurately, which is crucial for minimizing financial risk. Although the model's preformance in predicting high-risk loans is slightly lower, it still maintains a good balance between precision and recall, making this a reliable choice.


