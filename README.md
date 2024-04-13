# credit-risk-classification
# Loan Status Prediction using Machine Learning

This repository contains a machine learning project that predicts loan status based on historical financial data. The project utilizes a K-Nearest Neighbors classifier to distinguish between loans that are likely to be repaid and those that are not.

## Overview

The objective of this project is to apply machine learning techniques to make predictions about the risk associated with bank loans. By analyzing a dataset of past loans, we build a model that can predict the `loan_status` based on various attributes such as the borrower's job, education, balance, and history of past payments.

## Dataset

The dataset used in this project contains various financial attributes along with a label indicating loan repayment status. The attributes include personal information about clients and details about their financial behavior.

## Files in the Repository

- `lending_data.csv`: The dataset file containing the loan information.
- `credit_risk_classification.ipynb`: Jupyter notebook with the full analysis and predictive modeling process.
- `requirements.txt`: A list of Python dependencies for reproducing the analysis environment.

## Workflow

1. **Data Preprocessing**: Clean the dataset and handle categorical variables using encoding.
2. **Feature Engineering**: Select relevant features and scale the data.
3. **Model Training**: Train a K-Nearest Neighbors classifier using the training subset of the data.
4. **Model Evaluation**: Evaluate the model's performance on a testing subset using accuracy, precision, recall, and F1-score.
5. **Prediction**: Make predictions using the trained model on new data.

## Installation

To set up the project environment, follow these steps:

```bash
git clone https://github.com/your-username/loan-status-prediction.git
cd loan-status-prediction
pip install -r requirements.txt

## Usage
Open the credit_risk_classification.ipynb notebook in a Jupyter environment to view the analysis and prediction process. Run all the cells to train the model and make predictions.

## Results
The classifier achieved the following performance metrics:
Model 0
Accuracy: 99%
Precision: 100%
Recall: 99%
F1-Score: 100% 

Model 1
Accuracy: 99%
Precision: 85%
Recall: 91%
F1-Score: 88%

## Contributing
Nick Nath

## License
edX Boot Camps LLC


