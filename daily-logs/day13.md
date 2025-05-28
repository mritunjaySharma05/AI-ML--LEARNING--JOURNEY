# Day 13 – Decision Tree Classifier

**Date:** [May 28, 2025]

---

## 📘 What I Learned Today

### 🔹 Decision Tree Classifier
A supervised learning algorithm that mimics human decision-making.

- Represents decisions as a tree structure
- Nodes ask questions (e.g., Marks > 60?)
- Leaves give predictions ("Pass" or "Fail")

---

## 🧠 Key Concepts

| Concept       | Meaning                                       |
|---------------|-----------------------------------------------|
| Root Node     | First decision based on a feature             |
| Internal Node | Follow-up feature-based conditions            |
| Leaves        | Final class predictions                       |
| Entropy/Gini  | Metrics used to choose best split             |

---

## 🛠️ Steps I Performed

- Loaded CSV with "Marks" and "Result"
- Converted labels ("Pass"/"Fail") into 1s and 0s
- Split the dataset with `train_test_split()`
- Trained `DecisionTreeClassifier()`
- Evaluated predictions and accuracy
- Visualized the full tree with `plot_tree()`

---

## 📊 Output

Achieved high accuracy due to clean, simple data.

**Sample Rule:**  
- If Marks ≤ 58.5 → Predict "Fail"  
- Else → Predict "Pass"

---

## 📓 Notebook

Notebook with code & examples: [`day13.ipynb`](day13.ipynb)
