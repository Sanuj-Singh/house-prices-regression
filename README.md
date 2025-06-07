# House-prices-regression
House Prices Regression : Built an XGBoost model to predict house prices (R² = 0.91). Cleaned and encoded data, handled missing values, performed feature selection and hyperparameter tuning. Evaluated with RMSE/MAE. Developed a modular, reusable Jupyter Notebook.
## 📌 Problem Statement
Predict the final price of each house in the Ames Housing dataset. The dataset contains 79 explanatory variables describing (almost) every aspect of residential homes.

## 🔧 Tools & Technologies
- Python, Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, XGBoost


## 📊 Workflow Overview

1. **Data Cleaning**  
   - Imputed missing values (context-aware: 'None' vs 0)  
   - Removed outliers and inconsistencies  

2. **Feature Engineering**  
   - Label encoding of categorical features  
   - Handled skewed distributions for better model accuracy  

3. **Modeling**  
   - Implemented `XGBRegressor`  
   - Tuned hyperparameters for optimal performance  
   - Evaluated using RMSE, MAE, and R² metrics  

4. **Model Explainability**  
   - Visualized feature importances to understand key drivers of house prices 

## 📈 Results
- **R² Score:** 0.91
- **RMSE:** ~25,740  
- **MAE:** ~16,518

