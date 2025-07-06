# ✈️ Flight Ticket Price Prediction

This project analyzes and predicts flight ticket prices based on various features such as airline, source city, destination, departure time, travel class, number of stops, and booking window. The goal is to explore factors influencing ticket pricing and build regression models to make accurate predictions.

---

## 📂 Dataset Overview

- **Total Rows:** 300,153  
- **Total Columns:** 12  
- **Target Variable:** `price`

### 📄 Feature Descriptions

| Feature           | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| Airline           | Name of the airline company                                                 |
| Flight            | Plane's flight code                                                         |
| Source City       | City from which the flight takes off                                        |
| Departure Time    | Time of Departure                                                           |
| Stops             | Number of stops between the source and destination cities                   |
| Arrival Time      | Time of Arrival                                                             |
| Destination City  | City where the flight will land                                             |
| Class             | Contains information on seat class (Economy/Business)                      |
| Duration          | Total time taken to travel between cities (in hours)                        |
| Days Left         | Days between booking date and travel date                                   |
| Price             | Ticket price (target variable)                                              |

---

## 📊 Exploratory Data Analysis (EDA)

EDA was performed to understand key trends:
- **Airline vs Price**
- **Days Left vs Price**
- **Price distribution across Classes and Airlines**

These visualizations helped identify pricing patterns and seasonality.

---

## 🧹 Data Preprocessing

- Dropped unused columns: `Unnamed: 0`, `flight`
- Handled missing values
- Converted categorical features as needed

---

## 🤖 Machine Learning Models

Multiple regression models were trained:
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**

### 🔍 Evaluation Metrics:
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 📈 Results

Predictions were compared visually and numerically to evaluate model performance. Decision Trees and Random Forests performed best in capturing price patterns.

---

## 🛠️ Tech Stack

- Python (Pandas, NumPy)
- Seaborn, Matplotlib (EDA)
- Scikit-learn (Modeling & Evaluation)
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/snehamangtani/flight-price-prediction.git
