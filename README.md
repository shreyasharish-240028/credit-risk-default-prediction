# Credit Risk Default Prediction (Machine Learning Project)

## Business Problem
Financial institutions must determine whether a customer is likely to repay or default before approving credit. Incorrect predictions increase financial loss, damage portfolio quality, and lead to poor lending decisions.

This project builds a predictive machine learning model to estimate customer default risk using behavioral and financial attributes.

## Objective
Develop a classification model that predicts the probability of credit default and helps lenders make better approval and risk management decisions.

## Dataset
The dataset contains anonymized customer financial and behavioral features commonly used in real-world credit risk modeling.

Due to GitHub file size limitations, the full raw dataset is not included. A processed sample dataset is provided to reproduce the workflow and modeling process.

## Methodology
- Data cleaning and preprocessing
- Handling missing values
- Feature encoding and feature engineering
- Exploratory Data Analysis (EDA)
- Feature selection
- Model training using XGBoost and Neural Networks
- Hyperparameter tuning using Grid Search
- Model evaluation using AUC and classification metrics

## Tools & Technologies
- Python
- Pandas & NumPy
- Scikit-Learn
- XGBoost
- TensorFlow / Keras
- Matplotlib & Seaborn
- Jupyter Notebook

## Results
The trained model successfully identified high-risk customers and demonstrated strong predictive performance using AUC as the primary evaluation metric. Feature importance analysis helped identify key factors contributing to customer default.

## Business Impact
Banks and financial institutions can use this model to:
- Reduce credit default risk
- Improve loan approval decisions
- Adjust credit limits for high-risk customers
- Improve portfolio risk management

## Repository Structure
credit-risk-default-prediction/
data/           → Sample dataset for reproducibility
notebooks/      → Jupyter notebook containing analysis and modeling
docs/           → Project presentation/report
models/         → Saved trained models (optional)
README.md       → Project documentation

## Note
This project is for educational and demonstration purposes and uses anonymized data. The workflow replicates real-world credit risk modeling pipelines used in banking and fintech analytics.