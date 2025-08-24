# Medical-Insurance-Claim-Analysis
This project predicts medical insurance charges using machine learning. It involves a complete workflow starting from data cleaning and exploratory analysis to model training and explainability. Multiple regression models are compared, including Linear Regression, Ridge, Lasso, Decision Tree, and Random Forest.

## Project Workflow
1. **Data Loading & Cleaning**
   - Import dataset
   - Handle missing values
   - Outlier detection & treatment  

2. **Exploratory Data Analysis (EDA)**
   - Summary statistics
   - Correlation analysis
   - Distribution plots  

3. **Feature Engineering**
   - Encoding categorical variables
   - Feature scaling
    
#   Test Linear regression Assumptions 

4. **Modeling**
   The following regression models were implemented and compared:
   -  **Linear Regression** → baseline model  
   -  **Ridge Regression** → handles multicollinearity with L2 regularization  
   -  **Lasso Regression** → performs feature selection with L1 regularization  
   -  **Decision Tree** → captures non-linear relationships  
   -  **Random Forest** → ensemble method for better generalization  

5. **Model Evaluation**
   - Metrics: **R², Adjusted R², RMSE, MAE**  
   - Performance comparison across all models  

6. **Model Explainability**
   - **Feature Importance** (from tree-based models)  
   - **SHAP values** for global and local interpretability  

#Results

-Linear Regression: Provided a good baseline.

-Ridge & Lasso: Reduced overfitting, Lasso also performed feature selection.

-Decision Tree: Captured non-linear patterns but prone to overfitting.

-Random Forest: Best generalization among models.

-SHAP & Feature Importance: Helped explain which features (e.g., smoking status, BMI, age) contribute most to insurance charges.

📈 Future Work

* Apply hyperparameter tuning for each model (GridSearchCV, RandomizedSearchCV).

* Try advanced models like XGBoost, LightGBM, CatBoost.

*Deploy the model as a Flask/Streamlit web app for predictions.
