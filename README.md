# house-prices-regression
House Prices Regression : Built an XGBoost model to predict house prices (R² = 0.91). Cleaned and encoded data, handled missing values, performed feature selection and hyperparameter tuning. Evaluated with RMSE/MAE. Developed a modular, reusable Jupyter Notebook.
## 📌 Problem Statement
Predict the final price of each house in the Ames Housing dataset. The dataset contains 79 explanatory variables describing (almost) every aspect of residential homes.

## 🔧 Tools & Technologies
- Python, Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, XGBoost


## 📊 Workflow
1. **Data Cleaning**: Handled missing values (None vs 0 distinction), outlier removal.
2. **Feature Engineering**: Label encoding for categorical features, skewness handling.
3. **Modeling**: 
   - Used `XGBRegressor` with hyperparameter tuning.
   - Evaluated with `RMSE`, `MAE`, and `R² score` (Achieved R²: **0.91**).
4. **Interpretability**: Feature importance visualization.



## 📈 Results
- **R² Score:** 0.91
- **RMSE:** ~25,740  
- **MAE:** ~16,518

