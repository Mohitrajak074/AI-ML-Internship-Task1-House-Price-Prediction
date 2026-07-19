# 🏠 House Price Prediction using Linear Regression

## 📖 Overview

This project is part of my Artificial Intelligence & Machine Learning Internship Task 1.

The objective of this project is to build and evaluate a Linear Regression model using the California Housing Dataset. The project demonstrates the complete Machine Learning workflow, including data loading, exploratory data analysis (EDA), model training, evaluation, and prediction.

---

## 🎯 Project Objectives

* Load and explore the California Housing Dataset
* Perform Exploratory Data Analysis (EDA)
* Visualize important patterns and correlations
* Train a Linear Regression model
* Evaluate model performance using standard metrics
* Save the trained model for future predictions

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 📊 Dataset Information

The California Housing Dataset is provided by Scikit-Learn and contains housing-related information collected from California districts.


# 📸 Project Screenshots

## Dataset Preview

> Insert Screenshot Here

<img width="940" height="289" alt="Screenshot 2026-06-04 145521" src="https://github.com/user-attachments/assets/d18149e4-d92b-4aee-b7ae-4bf611d1bf9b" />

---

## Correlation Heatmap

### Purpose

Shows the relationship between all features and the target variable.

> Insert Heatmap Screenshot Here

<img width="1026" height="736" alt="Screenshot 2026-06-04 143442" src="https://github.com/user-attachments/assets/7a34b16d-5e58-4ddf-87e7-4b6fe12cb1fa" />


---

## House Price Distribution

### Purpose

Shows how house prices are distributed throughout the dataset.

> Insert Distribution Graph Here

<img width="617" height="434" alt="Screenshot 2026-06-04 143458" src="https://github.com/user-attachments/assets/d9868a51-2db7-4ebf-aa25-0ee246247c1d" />


---

## Actual vs Predicted House Prices

### Purpose

Compares model predictions against actual house prices.

> Insert Prediction Graph Here

<img width="746" height="571" alt="Screenshot 2026-06-04 143531" src="https://github.com/user-attachments/assets/7dbb4719-9a8b-4e25-a5f2-051b694e6e65" />




## Model Performance

| Metric   | Value               |
| -------- | ---------------     |
| MAE      | 0.533200130495656   |
| RMSE     | 0.7455813830127764  |
| R² Score | 0.5757877060324507  |


## PDF Report

📄 Complete project report is available in:


### Features

| Feature    | Description          |
| ---------- | -------------------- |
| MedInc     | Median Income        |
| HouseAge   | Median House Age     |
| AveRooms   | Average Rooms        |
| AveBedrms  | Average Bedrooms     |
| Population | Population of Block  |
| AveOccup   | Average Occupancy    |
| Latitude   | Latitude Coordinate  |
| Longitude  | Longitude Coordinate |

### Target Variable

* Median House Value

---

## 🔍 Exploratory Data Analysis

The following analyses were performed:

* Dataset overview
* Statistical summary
* Missing value analysis
* Correlation analysis
* Feature visualization

### Visualizations

* Correlation Heatmap
* House Price Distribution
* Actual vs Predicted Scatter Plot

---

## 🤖 Model Development

### Algorithm

Linear Regression

### Data Split

* Training Data: 80%
* Testing Data: 20%

### Training Process

The model was trained using Scikit-Learn's Linear Regression implementation to learn relationships between housing features and house prices.

---

## 📈 Model Evaluation

The model performance was evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score



## 📂 Project Structure

```text
House-Price-Prediction-Linear-Regression/
│
├── task1_ml_linear_regression.ipynb
├── report.pdf
├── predict.py
├── house_price_model.pkl
├── requirements.txt
├── README.md
│
└── screenshots/
    ├── heatmap.png
    ├── distribution.png
    └── prediction.png
```

---

## 🔮 Future Improvements

* Feature Engineering
* Hyperparameter Tuning
* Random Forest Regressor
* Gradient Boosting
* XGBoost
* Cross Validation

---

## 👨‍💻 Author

**Mohit Rajak**

B.Tech Computer Science & Engineering

Artificial Intelligence & Machine Learning Intern

---

## ⭐ Acknowledgements

* Scikit-Learn Documentation
* California Housing Dataset
* MainCrafts AI & ML Internship Program
