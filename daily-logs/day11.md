# Day 11 – K-Nearest Neighbors (KNN) Classifier

**Date:** May 26, 2025  

---

## 🔍 What I Learned Today

### 🔹 K-Nearest Neighbors (KNN)
- A **lazy learning algorithm**: no training happens during `.fit()`.
- Classifies based on the **majority class** among its **K nearest neighbors**.
- Works well for **small and clean datasets**.

---

## 🛠️ Steps Practiced

| Step                 | Description                                                             |
|----------------------|-------------------------------------------------------------------------|
| 📥 Libraries Used     | `pandas`, `sklearn`, `KNeighborsClassifier`                             |
| 📊 Dataset           | Included `Marks` and `Result` columns                                   |
| 🔄 Preprocessing     | Split into features `X` and labels `y`                                   |
| 🤖 Model Training    | Used `KNeighborsClassifier(n_neighbors=3)`                              |
| 📈 Evaluation        | Used `accuracy_score` for measuring performance                         |
| 🖼️ Visualization     | Plotted the decision boundary to understand how KNN classifies data     |

---

## 📊 Output & Accuracy

- The model drew a **clear decision boundary** between Pass/Fail.
- **Accuracy** was high due to:
  - Clean, separable data
  - Proper K-value selection

---

## 🧠 Notebook

Check full implementation here: [`day11_knn.ipynb`](day11notes.ipynb)
