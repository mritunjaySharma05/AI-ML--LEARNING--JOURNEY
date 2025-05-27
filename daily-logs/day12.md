# Day 12 – Support Vector Machine (SVM) Classifier

**Date:** May 27, 2025  
**#learninginpublic**

---

## 📘 What I Learned Today

### 🔹 Support Vector Machine (SVM)
- A powerful supervised learning algorithm used for classification.
- Finds the **optimal hyperplane** that best separates the classes.
- Maximizes the **margin** between support vectors of each class.
- Supports both **linear and non-linear** data through different **kernels**.

---

## 🧠 Key Concepts

| Concept     | Meaning                                                                 |
|-------------|-------------------------------------------------------------------------|
| Hyperplane  | The decision boundary that separates the two classes                   |
| Margin      | Distance between the hyperplane and the closest data points            |
| Kernel      | Function to map input data to a higher dimension (linear, RBF, poly)   |

---

## 🛠️ Steps I Performed

1. Loaded a dataset with **Marks** and **Result**.
2. Converted labels: `"Pass"` → 1, `"Fail"` → 0.
3. Split the data into **training and test sets**.
4. Trained a **Support Vector Classifier** with `SVC(kernel='linear')`.
5. Predicted results and calculated **accuracy**.
6. Visualized the decision boundary using **matplotlib**.

---

## 📊 Output Example

- **Accuracy** was close to **100%** due to clean, linearly separable data.
- Visual output showed a green line as the **decision boundary**.

---

## 📓 Notebook

Full practice notebook: [`day12_svm.ipynb`](day12_svm.ipynb)
