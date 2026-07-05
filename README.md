# PRODIGY_ML_01

# House Price Prediction using Linear Regression

## 📌 Project Overview

This project implements a **Linear Regression** model to predict house prices based on house characteristics. The baseline model uses **living area, number of bedrooms, and number of bathrooms** as input features, as specified in the assignment. An additional experiment was also performed by including more relevant features to improve model performance.

---

## 🎯 Objective

To build and evaluate a Linear Regression model that predicts house prices using the House Prices dataset.

---

## 📂 Dataset

* **Dataset:** House Prices - Advanced Regression Techniques (Kaggle)
* **Source:** https://www.kaggle.com/c/house-prices-advanced-regression-techniques

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## 📋 Workflow

1. Imported required libraries.
2. Loaded and explored the dataset.
3. Selected relevant features.
4. Split the data into training and testing sets.
5. Trained a Linear Regression model.
6. Predicted house prices on the test set.
7. Evaluated the model using regression metrics.
8. Compared the baseline model with an improved feature set.

---

## 📊 Evaluation Metrics

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## 📈 Results

### Baseline Model

* Features Used:

  * GrLivArea
  * BedroomAbvGr
  * FullBath
* R² Score: **0.634**

### Improved Model

Additional features included:

* OverallQual
* GarageArea
* GarageCars
* YearBuilt
* TotalBsmtSF

**Improved R² Score:** **0.77**

The experiment shows that adding more relevant features significantly improves prediction performance.

---

## 📷 Project Outputs

The repository includes:

* Actual vs Predicted Scatter Plot
* Residual Plot
* Feature Importance Plot

---

## 📚 Key Learnings

* Data loading and exploration using Pandas
* Feature selection
* Train-test split
* Building a Linear Regression model
* Model evaluation using regression metrics
* Improving model performance through feature engineering

---

## 🚀 Future Improvements

* Handle missing values more effectively.
* Apply feature engineering techniques.
* Compare Linear Regression with advanced algorithms such as Random Forest and XGBoost.
* Perform hyperparameter tuning for better performance.

---

## 👨‍💻 Author

**Prathamesh Kumar**
