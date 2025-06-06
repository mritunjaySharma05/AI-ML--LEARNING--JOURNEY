# Day 18 – Cross-Validation & Model Reliability

**Date:** June 6, 2025

---

## 🔍 Why It Matters

A model that performs well on one split might fail elsewhere.  
Today you explored **cross-validation**, a technique to test your model’s performance across multiple subsets of data — making your evaluation more reliable.

---

## 🔧 Concepts Covered

| Concept               | Purpose                                                |
|-----------------------|--------------------------------------------------------|
| Cross-Validation      | More accurate model evaluation by using multiple splits |
| K-Fold CV             | Divides data into K parts to reduce overfitting risk   |
| `cross_val_score()`   | Automates training and testing over K folds            |
| Mean Accuracy         | Gives final performance estimate over all folds        |

---

## 🛠️ What You Practiced

- Used `cross_val_score` from `sklearn.model_selection`
- Applied **K-Fold cross-validation** (e.g., 5 folds)
- Used **KNN/SVM classifier** on your dataset
- Printed accuracy from each fold
- Calculated **mean accuracy** as final performance

---

## 💡 Key Takeaway

> “Don’t trust a single score.”  
Cross-validation helps ensure your model is **robust and generalizes well** across different data.

---

## 📎 Bonus Tips

- Use `StratifiedKFold` when dealing with **imbalanced classes**
- Increase `n_splits` (K) for more robustness but longer time
- Combine with **grid search** for better hyperparameter tuning

---

📓 Practice Notebook: [`daily_logs/day18.ipynb`](daily_logs/day18.ipynb)
