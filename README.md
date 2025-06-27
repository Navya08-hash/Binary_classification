# 🔍 Binary Classification with Logistic Regression

This project implements a **binary classifier** using **Logistic Regression** to predict whether a tumor is malignant or benign based on the **Breast Cancer Wisconsin Dataset (CSV version)**.

---

## 📌 Objective
To build and evaluate a logistic regression model for binary classification using real-world medical data.

---

## 🧰 Tools & Libraries Used
- Python
- Pandas
- Scikit-learn
- Matplotlib

---

## 📂 Dataset
- **Source**: [Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Format**: CSV
- **Target Variable**: `diagnosis` (M = Malignant, B = Benign)

---

## 🧪 Steps Performed
1. Loaded and cleaned the dataset.
2. Split data into train and test sets.
3. Standardized the feature values.
4. Trained a Logistic Regression model.
5. Evaluated the model using:
   - Confusion Matrix
   - Precision, Recall, F1-Score
   - ROC-AUC Score and ROC Curve
6. Tuned threshold to observe changes in predictions.

---

## 📈 Evaluation Metrics

| Metric              | Description                               |
|---------------------|-------------------------------------------|
| **Confusion Matrix** | True Positives, False Positives, etc.     |
| **Precision**        | How many predicted positives were correct |
| **Recall**           | How many actual positives were detected   |
| **ROC-AUC**          | Area under the ROC Curve                  |

---

## 🧠 Sigmoid Function

Logistic regression uses the sigmoid function to map linear combinations of input features to probabilities between 0 and 1:

\[
\sigma(z) = \frac{1}{1 + e^{-z}}
\]

Changing the threshold value affects classification output.

---

## 📊 Output Example

- ROC AUC: 0.99+
- High Precision & Recall
- Well-balanced performance on unseen data

---

