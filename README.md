# 🏠 House Price Prediction using Linear Regression

This project is a simple **Machine Learning house price predictor** built using **Linear Regression** in Python.

The goal of this project is to understand the basics of:
- data preprocessing  
- feature selection  
- model training  
- prediction  
- evaluation  

---

## 📌 Project Overview

The model predicts house prices based on features such as:

- Area  
- Bedrooms  
- Bathrooms  
- Stories  
- Parking  
- Main road access  
- Guest room  
- Basement  
- Air conditioning  
- Preferred area  

---

## 🧠 Algorithm Used

- **Linear Regression**

This is a baseline machine learning model used to understand relationships between features and house prices.

---

## 🛠 Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## 📂 Dataset

- **Housing.csv**
- Contains both numerical and categorical features
- Categorical values were encoded before training

---

## ⚙️ Steps Performed

1. Loaded the dataset  
2. Cleaned and preprocessed data  
3. Converted categorical values (yes/no → 1/0)  
4. Selected relevant features  
5. Split data into training and testing sets  
6. Trained Linear Regression model  
7. Evaluated using **R² score**  
8. Visualized **Actual vs Predicted prices**

---

## 📊 Model Evaluation

- **Metric Used:** R² Score  
- Linear Regression achieved moderate accuracy, which is expected since house prices have non-linear patterns.

---

## 📈 Visualization

The project includes an **Actual vs Predicted Price graph**, where:

- Points closer to the diagonal line indicate better predictions.

---

## 🚀 How to Run

```bash
pip install pandas numpy matplotlib scikit-learn

