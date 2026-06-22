# 🧬 Breast Cancer Diagnosis Prediction using Logistic Regression

## 📌 Overview

This project uses Machine Learning to classify breast tumors as **Malignant (M)** or **Benign (B)** using the Breast Cancer Wisconsin (Diagnostic) Dataset.

A **Logistic Regression** model is trained to predict whether a tumor is cancerous based on numerical features extracted from cell nuclei images.

---

## 📊 Dataset

**Dataset:** Breast Cancer Wisconsin (Diagnostic)
- Source: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data/

### 🧪 Features include:

-  Radius
-  Texture
-  Perimeter
-  Area
-  Smoothness
-  Compactness
-  Concavity
-  Concave Points
-  Symmetry
-  Fractal Dimension

Each feature is provided as:
- Mean (`_mean`)
- Standard Error (`_se`)
- Worst (`_worst`)

### 🎯 Target:
-  **B** = Benign (non-cancerous)
-  **M** = Malignant (cancerous)

---

## 🧹 Data Preprocessing

Steps applied:

- ❌ Removed unnecessary columns:
  - `id`
  - `Unnamed: 32`
- 🔁 Encoded labels:
  - M → 1
  - B → 0
---

## 📊 Exploratory Data Analysis (EDA)

The dataset was explored to understand patterns and relationships between variables.

---

## 🤖 Model

### Algorithm:
- 📉 Logistic Regression
---
### 🧾 Classification Report:

```text
              precision    recall  f1-score   support

           0       0.95      0.99      0.97        71
           1       0.97      0.91      0.94        43

    accuracy                           0.96       114
