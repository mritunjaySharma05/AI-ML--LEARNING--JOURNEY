# Day 17 – Feature Engineering & Selection

**Date:** June 3, 2025

---

## 🔍 Why It Matters

More features don’t always mean better results.  
Today you explored **how to create powerful features** and **filter out the noisy ones** to improve model accuracy and performance.

---

## 🔧 Concepts Covered

| Concept            | Explanation                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| Feature Engineering| Creating new features from existing ones (e.g., BMI = Weight / Height²)     |
| Encoding           | Converting categorical data (Gender, Sport) into numeric values             |
| Feature Selection  | Choosing only the most useful features using methods like correlation or `SelectKBest` |

---

## 🛠️ What You Practiced

- Created new features manually from existing ones (e.g., combining Height & Weight into BMI)
- Encoded text columns using LabelEncoder and OneHotEncoder
- Identified useful features using `.corr()`, SelectKBest, and domain knowledge
- Reduced noise by dropping irrelevant or redundant columns

---

## 💡 Key Takeaway

> "Better data beats fancier algorithms."  
Feature engineering and selection can drastically improve model performance, even before you train!

---

## 📎 Bonus Tips

- Try PolynomialFeatures for non-linear models  
- Be cautious: too many engineered features may cause overfitting  
- Use `heatmap()` to visualize correlation between features  

---

📓 Practice Notebook: [`day17.ipynb`](day17.ipynb)
