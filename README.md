# 💻 Task 4 – Logistic Regression Classifier

---

## 🧠 Objective  
This task focuses on building a **binary classification model** using **Logistic Regression** to predict whether a tumor is **malignant (0)** or **benign (1)** using the **Breast Cancer Wisconsin Dataset**.

---

## 🔧 Tools & Libraries  
- Python  
- `pandas`, `numpy`  
- `scikit-learn`  
- `matplotlib`, `seaborn`  

---

## 📁 Dataset  
- Source: `sklearn.datasets.load_breast_cancer()`  
- No download required – directly loaded via scikit-learn  
- Features: 30 numeric features  
- Target classes: 0 (malignant), 1 (benign)

---

## 📌 Workflow Overview

1. **Loaded the dataset** using `sklearn.datasets`
2. **Split** into training and testing sets (80/20)
3. **Standardized features** using `StandardScaler`
4. **Trained a logistic regression model**
5. **Evaluated** the model with:
   - Classification report
   - Confusion matrix (heatmap)
   - ROC-AUC score and ROC curve
6. **Visualized** the Sigmoid function for conceptual understanding

---

## 📊 Results

- ✔️ Model trained successfully
- 📈 ROC-AUC Score: *~0.98* (may vary slightly)
- 📉 Confusion matrix and ROC curve plotted
- 🧠 Sigmoid function visualized to explain probability mapping

---

## ✨ Bonus Insight  
The **sigmoid function** transforms raw prediction scores into probabilities between 0 and 1 — making logistic regression interpretable and threshold-tunable.

---

> _This task helped demonstrate how logistic regression works not only as a model, but as a concept — from preprocessing to visual evaluation._

---
