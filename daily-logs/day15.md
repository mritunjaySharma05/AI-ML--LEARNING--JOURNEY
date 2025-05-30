# 🔍 Day 15 – Model Evaluation & Comparison

**Date:** May 31, 2025

---

## 📘 What I Learned

Today was all about **comparing machine learning models** to understand which one performs best.  
I explored evaluation metrics that go beyond just accuracy to make more informed decisions.

---

## 🛠️ Models Compared

- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Decision Tree**
- **Random Forest**

---

## 📊 Evaluation Metrics Used

| Metric            | Meaning                                                                 |
|------------------|-------------------------------------------------------------------------|
| Accuracy          | Overall correctness (Correct predictions / Total predictions)           |
| Confusion Matrix  | Shows TP, TN, FP, FN — helps understand where your model fails          |
| Precision         | Out of predicted positives, how many are actually correct               |
| Recall            | Out of actual positives, how many were caught by the model              |
| F1 Score          | Harmonic mean of Precision & Recall                                     |
| Cross-Validation  | Evaluates model performance across multiple splits of the dataset       |

---

## ✅ Steps You Performed

1. Loaded the **Marks & Result** dataset  
2. Preprocessed target labels (Pass → 1, Fail → 0)  
3. Trained **4 different models**  
4. Measured accuracy using `accuracy_score`  
5. Used `classification_report` for **precision, recall, and F1-score**  
6. Visualized performance using **confusion_matrix**  
7. Used `cross_val_score()` to see average model accuracy across **5 folds**

---

## 📊 Typical Output

- All models may show **high accuracy** on a small, clean dataset  
- **Random Forest** & **Decision Tree** might show up to **100% accuracy**  
- **Cross-validation** helps detect **overfitting** or **data dependency**

---

## 📌 Takeaway

Accuracy is just one piece of the puzzle —  
**Real evaluation starts when you dig deeper into precision, recall, and F1-score.**

---

**Notebook:** [`day15.ipynb`](day15.ipynb)
