# Predictive Modeling of CO2 Emissions

An exploratory data analysis and regression modeling project aimed at predicting CO2 emissions based on geographic and demographic features (Area and Population).

## 📌 Project Overview
This project explores the relationship between country-level predictors and CO2 emissions. It compares multiple regression approaches, from simple linear regression to complex polynomial models, to find the optimal balance between bias and variance.

## 🛠️ Tech Stack
* **Language:** Python
* **Machine Learning:** Scikit-Learn (LinearRegression, PolynomialFeatures)
* **Data Manipulation:** Pandas, NumPy
* **Data Visualisation:** Matplotlib, Seaborn

## 📈 Key Findings & Results
* Evaluated simple linear, multiple linear, and polynomial regression models (degrees 1 through 9).
* Used KDE plots for distribution comparison and residual plots to analyze heteroscedasticity.
* **Optimal Model:** Selected a **7th-degree polynomial model** as the best fit, which significantly improved performance, achieving an **$R^2$ score of >0.97** and minimizing MSE, without unnecessary computational overhead.

## 🚀 How to Run
1. Clone the repository.
2. Ensure `clean_data.csv` is in the `data/` folder.
3. Install dependencies and run the main notebook to view the regression analysis and visualizations.
