# 📈 Linear Regression — House Price Prediction Project

A complete **regression project using Scikit-learn** where historical housing data from a Kaggle dataset was analyzed and used to build a **Linear Regression model** that predicts house sale prices based on multiple numerical features.

---

## 📁 Project Files

The project is organized in the `house-price-regression/` folder and includes:

- `Linear Regression.ipynb`: Jupyter Notebook containing the full code, analysis, and model evaluation  
- `house_prices.csv`: Original dataset from Kaggle's House Prices competition (loaded in Kaggle environment)  
- `README.md`: This documentation file with complete details of the project  
- `requirements.txt`: List of required Python packages (optional if using Kaggle)

---

## 🎯 Project Objectives

- Apply **Linear Regression** to a real-world dataset of house prices  
- Learn how to select features, handle missing values, and train a regression model  
- Evaluate model performance using metrics like RMSE and R² Score  
- Visualize actual vs predicted values to assess accuracy  

---

## 🔍 Dataset Overview

The dataset used is from the Kaggle competition:  
👉 **[House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)**

We used the `train.csv` file and selected a few key numerical features for this project:
- `GrLivArea`: Above ground living area (sq ft)  
- `OverallQual`: Overall material and finish quality (1–10 scale)  
- `GarageCars`: Number of cars the garage can hold  
- `TotalBsmtSF`: Total basement square footage  

Target variable: `SalePrice`

---

## 🧠 Modeling Steps in `house_price_regression.ipynb`

1. **Import Libraries**  
   Import essential packages like `pandas`, `scikit-learn`, `matplotlib`, and `seaborn`.

2. **Load Dataset**  
   Read the CSV file using pandas and explore key statistics.

3. **Feature Selection & Cleaning**  
   Choose numerical features and drop missing rows for simplicity.

4. **Train-Test Split**  
   Split the dataset into training and testing sets (80/20).

5. **Train Linear Regression Model**  
   Use `LinearRegression` from scikit-learn to fit the model.

6. **Predict & Evaluate**  
   - Predict `SalePrice` on test data  
   - Evaluate using RMSE and R² score  
   - Plot Actual vs Predicted prices for visualization

---

## 📊 Sample Output

```text
✅ RMSE: 34322.65  
✅ R² Score: 0.7485
