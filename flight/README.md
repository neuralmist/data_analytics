# ✈️ Flight Price Prediction using Machine Learning

## 📌 Overview

This project focuses on predicting airline ticket prices using machine learning techniques. The model is trained on a large dataset of flight details such as airline, departure time, number of stops, duration, and days left before departure.

The goal is to build an accurate regression model that can estimate ticket prices based on these features.

---

## 📊 Dataset

The dataset used for this project is publicly available on Kaggle:

🔗 https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction

* Total Records: ~300,000+
* Features include:

  * Airline
  * Source & Destination Cities
  * Departure & Arrival Time
  * Stops
  * Duration
  * Days Left
  * Ticket Price (Target)

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Scikit-learn

---

## 🧠 Machine Learning Approach

### 1. Data Preprocessing

* Removed irrelevant/constant columns
* Handled categorical variables using One-Hot Encoding
* Split dataset into training and testing sets

### 2. Model Used

* Random Forest Regressor

### 3. Evaluation Metrics

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

---

## 📈 Model Performance

| Metric   | Value  |
| -------- | ------ |
| MAE      | ~1070  |
| MSE      | ~7.49M |
| R² Score | 0.985  |

### 🔍 Interpretation

* The model explains ~98.5% of variance in ticket prices.
* Average prediction error is around ₹1000, which is ~5% of the average ticket price (~₹20,000).


---

## 📌 Key Insights

* Ticket prices increase as departure date approaches
* Flights with more stops are generally cheaper
* Duration and airline significantly impact pricing

---

## 🔮 Future Improvements

* Implement XGBoost for better performance
* Hyperparameter tuning
* Deploy model using Streamlit
* Add more real-world features (seasonality, demand, holidays)

---
