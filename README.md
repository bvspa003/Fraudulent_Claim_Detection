# Insurance Fraud Detection

This repository contains a machine learning project focused on predicting insurance fraud using classification models.

## Project Overview

Insurance fraud is a significant concern for insurance companies, leading to billions in losses annually. This project develops and compares machine learning models to detect potentially fraudulent insurance claims, helping companies reduce financial losses and improve operational efficiency.

## Repository Contents

- `Insurance_Fraud_Detection.ipynb`: Jupyter notebook containing the complete data analysis, preprocessing, model development, and evaluation
- `Insurance_Fraud_Report.pdf`: Comprehensive technical report detailing the methodology and findings
- `Insurance_Fraud_Presentation.pdf`: Executive presentation summarizing key insights and recommendations

## Models Developed

1. **Logistic Regression**
   - Feature selection using RFECV
   - Hyperparameter optimization
   - Performance evaluation with various metrics

2. **Random Forest**
   - Feature importance analysis
   - Anti-overfitting techniques
   - Hyperparameter tuning using GridSearchCV

## Key Findings

- Logistic Regression achieved 86.01% accuracy on validation data
- Random Forest achieved 81.82% accuracy on validation data
- Both models effectively detect fraud with different strengths:
  - Logistic Regression: Better overall accuracy and precision
  - Random Forest: Better at identifying actual fraud cases (higher recall)

## Feature Importance

The most significant predictors of insurance fraud include:
- Major damage indicator
- Insured's hobbies
- Education level
- Time of day
- Occupation

## Technologies Used

- Python 3.x
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - statsmodels

## How to Use

1. Clone this repository
2. Install required dependencies: `pip install -r requirements.txt`
3. Open and run the Jupyter notebook: `jupyter notebook Insurance_Fraud_Detection.ipynb`

## Future Work

- Explore ensemble methods combining multiple models
- Implement cost-sensitive learning
- Develop a monitoring system for model performance
- Expand the dataset with additional features
