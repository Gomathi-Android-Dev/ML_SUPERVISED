# House Price Prediction using Machine Learning Regression Algorithms

## Project Overview

This project predicts house prices using multiple Machine Learning regression algorithms. The objective is to compare the performance of different regression models and identify the best-performing algorithm based on evaluation metrics.

The dataset contains housing-related features such as crime rate, number of rooms, tax rate, accessibility to highways, and other factors influencing house prices.

---

## Dataset Information

* Dataset: Housing Price Dataset
* Problem Type: Regression
* Target Variable: `MEDV` (Median House Value)

### Features

* CRIM
* ZN
* INDUS
* CHAS
* NOX
* RM
* AGE
* DIS
* RAD
* TAX
* PTRATIO
* B
* LSTAT

Target:

* MEDV (House Price)

---

## Data Preprocessing

### Steps Performed

* Data Exploration
* Feature Selection
* Train-Test Split (80:20)
* Model Training
* Performance Evaluation

---

## Machine Learning Algorithms Implemented

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor
5. Support Vector Regressor (SVR)
6. K-Nearest Neighbors Regressor (KNN)

---

## Evaluation Metrics

The models were evaluated using:

* Mean Absolute Error (MAE)
* R² Score
* Train R² Score
* Test R² Score
* Actual vs Predicted Visualization

---

## Model Performance Comparison

| Algorithm                   | MAE  | R² Score |
| --------------------------- | ---- | -------- |
| Linear Regression           | 3.15 | 0.659    |
| Decision Tree Regressor     | 2.62 | 0.841    |
| Random Forest Regressor     | 2.02 | 0.899    |
| Gradient Boosting Regressor | 1.89 | 0.900    |
| Support Vector Regressor    | 3.13 | 0.587    |
| KNN Regressor               | 3.85 | 0.596    |

---

## Best Performing Model

### Gradient Boosting Regressor

Results:

* Mean Absolute Error: 1.888
* R² Score: 0.900
* Train R²: 0.978
* Test R²: 0.900

### Why Gradient Boosting Performed Best

* Lowest prediction error
* Highest R² Score
* Strong generalization performance
* Minimal overfitting

---

## Model Results

### Linear Regression

* MAE: 3.150
* R² Score: 0.659

### Decision Tree Regressor

* MAE: 2.621
* R² Score: 0.841

### Random Forest Regressor

* Train R²: 0.973
* Test R²: 0.899

### Gradient Boosting Regressor

* MAE: 1.888
* R² Score: 0.900

### Support Vector Regressor (SVR)

* MAE: 3.132
* R² Score: 0.587

### K-Nearest Neighbors Regressor (KNN)

* MAE: 3.849
* R² Score: 0.596

---

## Visualizations

### Confusion Matrix

![Confusion Matrix](screenshots/graph1.webp)

### Precision Recall Curve

![Precision Recall Curve](screenshots/graph2.webp)

### ROC Curve

![ROC Curve](screenshots/graph3.webp)

---

## Key Findings

* Ensemble methods outperformed traditional regression models.
* Gradient Boosting achieved the highest predictive accuracy.
* Random Forest and Gradient Boosting produced very similar results.
* Linear Regression was limited by non-linear relationships in the data.
* KNN and SVR performed worse than tree-based ensemble methods.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## Future Improvements

* Hyperparameter Tuning
* Cross Validation
* XGBoost Regressor
* LightGBM Regressor
* Feature Engineering

---

## Conclusion

Among all regression algorithms tested, Gradient Boosting Regressor achieved the best performance with an R² Score of 0.900 and the lowest MAE of 1.888. This demonstrates the effectiveness of ensemble learning techniques for house price prediction.

---

## Author

Gomathi Selvakumar

Machine Learning Regression Portfolio Project
