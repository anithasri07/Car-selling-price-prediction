Linear regression model to predict car selling prices based on mileage and age of the car. Includes data preprocessing, model training, and evaluation using Python (pandas, sklearn). Perfect for beginners exploring regression and data analysis concepts.

# Car Price Prediction using Linear Regression

This project demonstrates a simple linear regression model to predict the selling price of a car based on two features:
- Mileage (distance the car has been driven)
- Age (number of years the car has been used)

## Overview
The dataset contains historical data about cars, including their mileage, age, and corresponding selling price. The goal is to train a machine learning model that predicts the selling price of a car given its mileage and age.

---

## Features
- **Mileage:** Distance the car has traveled (in kilometers or miles).
- **Age (yrs):** Number of years the car has been in use.
- **Sell Price ($):** Selling price of the car in dollars (target variable).

---

## Technologies Used
- **Python**: Programming language.
- **pandas**: For data manipulation and preprocessing.
- **scikit-learn**: For model building and evaluation.

---

## How It Works
1. **Data Preprocessing**:
   - Load the dataset using `pandas`.
   - Split the data into features (`Mileage`, `Age`) and target (`Sell Price`).
   - Divide the data into training and test sets.

2. **Model Building**:
   - Use scikit-learn's `LinearRegression` model.
   - Train the model using the training data.
   - Predict selling prices on the test data.

3. **Evaluation**:
   - Compare predicted prices with actual prices from the test set.
   - Metrics like Mean Squared Error (MSE) and R² can be used to evaluate performance.

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/car-price-prediction.git
