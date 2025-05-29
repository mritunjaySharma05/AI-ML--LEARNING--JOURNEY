# 🌲 Day 14 – Random Forest Classifier

**Date:** May 30, 2025

---

## 📘 What I Learned

### 🔹 Random Forest Classifier

Random Forest is an **ensemble learning** technique that builds multiple **decision trees** and combines their outputs to improve performance.

- Uses **bagging** (Bootstrap Aggregation)
- Makes decisions through **majority voting**
- More robust and less prone to overfitting than individual trees
- Useful for both **classification** and **regression**

---

## 🧠 Key Concepts

| Concept           | Meaning                                                                 |
|-------------------|-------------------------------------------------------------------------|
| Ensemble Learning | Combining multiple models to get better performance                    |
| Bagging           | Sampling data with replacement to build different trees                |
| n_estimators      | Number of trees in the forest (more = better, but slower)              |
| Majority Voting   | Class with most votes becomes the final prediction                     |

---

## 🛠️ Steps You Performed in Code

1. Loaded and cleaned your dataset  
2. Converted target labels (Pass/Fail) to binary (1/0)  
3. Split the dataset into training and testing sets  
4. Trained a `RandomForestClassifier` with 100 trees  
5. Evaluated the model using `accuracy_score`  
6. Visualized the predictions using **Seaborn** scatter plot

---

## 📊 Typical Output

- ✅ Accuracy: ~100% on clean/simple datasets  
- 📉 Visualized predictions with color-coded results  
- 💪 Robust to noise, performs better than a single decision tree

---

## 📓 Notebook

*My practice and notes are saved in:* [`day14.ipynb`](day14.ipynb)
