# 🌸 Iris Classification & Polynomial Regression  
Machine Learning Mini Project  

## 📌 Project Overview

This project demonstrates fundamental **Supervised Machine Learning techniques** using:

- 🌼 Iris Dataset (Classification Problem)
- 📈 Synthetic Polynomial Data (Regression Problem)

The goal of this project is to understand:

- Data preprocessing
- Feature scaling
- Model training and evaluation
- Overfitting & underfitting
- Bias–Variance tradeoff
- Polynomial feature transformation

---

---

# 🧠 Part 1: Classification on Iris Dataset

## 📊 Dataset

The Iris dataset contains 150 samples of flowers categorized into three species:

- Setosa  
- Versicolor  
- Virginica  

Each sample includes four features:

- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

---

## 🔍 Steps Performed

### 1️⃣ Data Exploration
- Loaded dataset using `sklearn`
- Converted to Pandas DataFrame
- Checked:
  - Shape
  - Summary statistics
  - Class distribution
- Created scatter plots for feature comparison

### 2️⃣ Data Preprocessing
- Train-Test Split (80% training / 20% testing)
- Feature scaling using `StandardScaler`

### 3️⃣ Models Implemented

- ✅ Logistic Regression
- ✅ K-Nearest Neighbors (KNN)
- ✅ Decision Tree Classifier

---

## 📈 Model Evaluation

Each model was evaluated using:

- Accuracy Score
- Classification Report
- Training vs Testing Accuracy Comparison

---

## 🏆 Model Comparison Summary

| Model | Strength | Weakness |
|-------|----------|----------|
| Logistic Regression | Simple & fast | Assumes linear boundary |
| KNN | Flexible & accurate | Sensitive to scaling |
| Decision Tree | Highly interpretable | Can overfit |

---

## 📌 Key Observations

- Petal length & petal width are the most informative features.
- KNN performs well with proper K selection.
- Decision Trees may overfit if depth is too large.
- Logistic Regression handles multi-class problems using One-vs-Rest or Softmax.

---

# 📈 Part 2: Polynomial Regression

## 🎯 Objective

To understand:

- Linear vs Non-linear relationships
- Underfitting & Overfitting
- Bias-Variance tradeoff

---

## 🔢 Data Generation

Synthetic data generated using:
---


Gaussian noise was added to simulate real-world data.

---

## 🧪 Experiments Conducted

### 1️⃣ Linear Regression on Non-linear Data
- Poor fit
- High MSE
- Example of **Underfitting**

### 2️⃣ Polynomial Regression
Models trained with:
- Degree 2
- Degree 3
- Degree 10

---

## 📊 Results Analysis

| Degree | Behavior |
|--------|----------|
| 1 | Underfitting |
| 2 | Best Fit |
| 10 | Overfitting |

---

## ⚖ Bias-Variance Tradeoff

- Low degree → High bias → Underfitting  
- High degree → High variance → Overfitting  
- Moderate degree → Balanced model  

---

# 🛠 Technologies Used

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# ⚙ Installation

## 1️⃣ Create Virtual Environment (Recommended)

```bash
python -m venv ml_env
source ml_env/bin/activate  # Mac/Linux
ml_env\Scripts\activate     # Windows
