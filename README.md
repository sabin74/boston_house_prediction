# Boston Housing Price Prediction

## Project Overview

This project aims to predict the median value of owner-occupied homes in Boston suburbs using various machine learning regression models.

Multiple regression techniques were applied, including Linear Regression, Decision Tree, Random Forest, Gradient Boosting and dimensionality reduction with PCA. Hyperparameter tuning was performed to improve the model’s accuracy.


## Tools & Technologies

- **Language:** Python 3.x
- **Libraries:**  
  - numpy, pandas  
  - scikit-learn  
  - matplotlib, seaborn  
  - joblib (for saving/loading models)

## Project Roadmap

1. **Data Loading & Exploration**  
   Loaded the dataset, explored basic statistics and feature relationships.

2. **Data Preprocessing**  
   Handled missing values , scaled features using StandardScaler.

3. **Feature Engineering & Dimensionality Reduction**  
   Applied PCA to reduce feature dimensionality while preserving 95% variance.

4. **Model Building**  
   Trained various regression models:
   - Linear Regression  
   - Decision Tree Regressor  
   - Random Forest Regressor  
   - Gradient Boosting Regressor (best performing)  
   - Lasso & Ridge Regression (regularized models)

5. **Model Evaluation**  
   Evaluated models using MAE, MSE, and R² score.

6. **Hyperparameter Tuning**  
   Performed GridSearchCV on Gradient Boosting Regressor for optimal hyperparameters.

7. **Model Saving & Deployment**  
   Saved the best model along with scaler and PCA objects using joblib for future predictions.
