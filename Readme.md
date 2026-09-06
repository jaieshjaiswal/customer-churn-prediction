# Customer Churn Prediction

A machine learning project that predicts whether a telecom customer is likely to churn based on customer information, services, contract details, and billing information.

## Project Objective

Customer churn is an important problem for telecom companies. The goal of this project is to build a machine learning model that can identify customers who are likely to leave the service.

## Dataset

The project uses telecom customer data containing information such as:

- Customer tenure
- Monthly charges
- Total charges
- Contract type
- Internet service
- Streaming services
- Payment method
- Customer dependents
- Other service-related features

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Google Colab

## Machine Learning Models

Three models were evaluated:

1. Logistic Regression
2. Balanced Logistic Regression
3. Random Forest

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC
- ROC Curve

## Results

| Model | Accuracy | ROC-AUC |
|---|---:|---:|
| Logistic Regression | 80.38% | 0.836 |
| Balanced Logistic Regression | 72.64% | 0.835 |
| Random Forest | 78.96% | — |

Logistic Regression achieved the best overall accuracy and was selected as the final model.

Balanced Logistic Regression achieved higher recall for the churn class, which can be useful when identifying more potential churn customers is more important than overall accuracy.

## Important Features

Some of the strongest features identified by the model were:

- Tenure
- Monthly Charges
- Internet Service
- Contract Type
- Total Charges
- Streaming TV
- Streaming Movies
- Multiple Lines
- Payment Method

## Customer Prediction

The final system allows customer information to be entered and predicts:

- Whether the customer is likely to churn
- The estimated churn probability

Example:

```text
Prediction: CUSTOMER WILL NOT CHURN
Churn Probability: 16.65%
