# Customer Churn Prediction Models

<img width="1366" height="768" alt="Screenshot (174)" src="https://github.com/user-attachments/assets/61249bca-cca0-4a52-95c8-c2d83a1dc543" />


## Data Cleaning & Feature Engineering

- Handled missing values
- Converted categorical features into numerical ones
- Standardized numerical columns
- Created dummy variables for modeling

  ## Exploratory Data Analysis (EDA)
  
Plotted distributions and relationships (e.g., how contract type affects churn)
Found that:
- Customers on monthly contracts churn more
- Higher monthly charges correlate with higher churn
- Shorter tenure (new customers) = more likely to churn

## Model Building
Used machine learning models to predict churn:
* Logistic Regression
* Random Forest
* Support Vector Machine (SVM)
* XGBoost

## Evaluated each model with metrics:
* Accuracy
* Precision
* Recall
* F1 Score
* ROC AUC

- Best performing model likely to be XGBoost or Random Forest based on typical churn datasets.

## Results (Expected or Typical)

- Accuracy: Often around 80–85%
- Recall: High for churners to avoid losing customers
- Feature Importance: Contract type, tenure, internet service, and monthly charges are strong predictors

