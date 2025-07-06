# 🧠 Insurance Charges Prediction using Linear Regression

## 📌 Project Overview

This project aims to predict medical insurance charges based on demographic and lifestyle factors such as:

- Age  
- Sex  
- BMI (Body Mass Index)  
- Number of children  
- Smoking status  
- Region of residence  

The goal is to demonstrate data-driven decision-making using statistical modeling and data science techniques.

---

## 📊 Dataset

- **Source**: Publicly available dataset (e.g., Kaggle)
- **Features Used**:
  - `age`: Age of the individual
  - `sex`: Gender
  - `bmi`: Body Mass Index
  - `children`: Number of children covered by insurance
  - `smoker`: Smoking status
  - `region`: Residential area in the US
  - `charges`: Target variable (insurance cost)

---

## 🧪 Techniques Applied

### ✅ Exploratory Data Analysis (EDA)
- Uncovered patterns and outliers using:
  - Histograms, boxplots, pairplots
  - Correlation heatmaps
- Analyzed the distribution and relationship of features with charges.

### ✅ Feature Engineering
- Converted categorical features using **Label Encoding / One-Hot Encoding**
- Checked multicollinearity and variable importance

### ✅ Model Used
- **Linear Regression** (baseline model)
- Evaluated with metrics like:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - R² Score

---

## 🧠 Key Insights

- **Smoking** significantly increases insurance charges
- **Age** and **BMI** are positively correlated with cost
- Feature selection and encoding played a key role in model performance

---

## 🚀 Outcome

- Built an interpretable model to predict insurance charges with reasonable accuracy
- Showcased the power of EDA and regression in real-world cost estimation scenarios

---

## 📂 Files

- `insurance_prediction.ipynb`: Jupyter notebook containing the full workflow
- `README.md`: Project overview

---

## 👨‍💻 Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- Jupyter Notebook

---

## 🔗 Ideal For

- Demonstrating **data science fundamentals**
- Showcasing **analytical thinking**
- Highlighting **communication and interpretation of data**

---
