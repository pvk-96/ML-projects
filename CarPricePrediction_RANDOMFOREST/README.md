# 🚗 Car Price Prediction – Random Forest

A machine learning project that predicts the price of a car based on its specifications using the **Random Forest Regression** algorithm.

### 🔹 What the model does

* Takes numerical car features (like horsepower, engine size, curb weight, wheelbase, etc.)
* Trains a Random Forest model to learn patterns in pricing
* Predicts the **car price** for unseen data

### 🔹 Steps in the project

1. Load dataset and remove unwanted column (`car_ID`)
2. Select only **numerical features**
3. Apply **feature scaling**
4. Split data into **train and test**
5. Train using **RandomForestRegressor**
6. Evaluate model using **R² Score**

### 🔹 Output

* Returns the **predicted price** of a car (continuous value, not classification)

### 🔹 Libraries Used

`pandas`, `scikit-learn`, `google.colab`

---

This project demonstrates a simple end-to-end **regression pipeline** — from preprocessing to training and evaluation — using the Random Forest algorithm.

