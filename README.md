# 📊 Multiple Linear Regression Model

This project demonstrates how to implement a **Multiple Linear Regression** model using Python, `scikit-learn`, and data preprocessing with `StandardScaler`. The goal is to predict outcomes based on multiple input features.

---

## 🚀 Project Overview

- **Algorithm Used:** Linear Regression
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn
- **Key Features:**
  - Data preprocessing
  - Train-test split
  - Feature scaling with `StandardScaler`
  - Model training and evaluation
  - Performance visualization

---

## 📁 Notebook File

- [`Multiple Linear Regression.ipynb`](./Multiple%20Linear%20Regression.ipynb): Main notebook demonstrating all steps including data loading, model training, evaluation, and visualization.

---

## ⚙️ How It Works

1. **Load the dataset**
2. **Preprocess the features**
   - Handle missing values (if any)
   - Scale features using `StandardScaler`
3. **Split the data** into training and testing sets
4. **Train a Linear Regression model** on the training set
5. **Evaluate performance** using R² score
6. **Convert score to percentage** for better readability

```python
score = model.score(X_test_scaled, y_test)
print(f"Model Accuracy: {round(score * 100, 2)}%")

