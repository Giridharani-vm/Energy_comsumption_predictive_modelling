# Predictive modelling for house hold energy consumption
## 🧩 Problem Statement

Accurately forecasting household energy consumption helps both consumers and energy providers to manage usage efficiently, reduce costs, and plan better. This project aims to develop predictive models based on historical energy usage data to estimate future consumption.

---

## 🔧 Process Followed

1. **Data Preprocessing**
   - Handled missing values and outliers  
   - Extracted features from datetime  
   - Scaled and normalized relevant features  

2. **Exploratory Data Analysis (EDA)**
   - Visualized trends, correlations, and seasonality in usage  

3. **Model Building**
   - Built and trained models using:
     - Linear Regression with Ridge Optimization  
     - Random Forest Regressor with Hyperparameter Tuning  
     - Gradient Boosting Regressor with GridSearchCV  

4. **Model Evaluation**
   - Used evaluation metrics like R² Score and RMSE  
   - Compared model performance visually to select the best one
