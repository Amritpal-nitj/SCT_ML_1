# SCT_ML_1
TASK1:Implement a linear regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms.
# 🏡 House Price Prediction using Linear Regression

This project demonstrates how to use a **Linear Regression model** to predict house prices based on features like **square footage**, **number of bedrooms**, and **number of bathrooms**.

---

## 📌 Objective

To build a simple yet effective regression model that estimates the price of a house using core features commonly available in real estate data.

---

## 📁 Dataset

- The dataset includes:
  - `Square Footage` — Total living area
  - `Bedrooms` — Number of bedrooms
  - `Bathrooms` — Number of bathrooms
  - `Price` — Target variable



---

## 🔧 Technologies Used

- Python 3
- NumPy & Pandas
- scikit-learn (`LinearRegression`, `train_test_split`)
- Matplotlib / Seaborn (for visualizations)

---

## 🧠 Workflow

1. **Data Importing & Exploration**
2. **Feature Selection** (Square footage, Bedrooms, Bathrooms)
3. **Train-Test Split**
4. **Model Training** using Linear Regression
5. **Prediction & Evaluation**
   - Mean Squared Error
   - R² Score
6. **Model Interpretation**
   - Coefficients for each feature
   - Intercept (baseline price)

---
## 📈 Sample Output

```text
Coefficients: [100.0, 10000.0, 15000.0]
Intercept: 50000.0
R² Score: 0.95
