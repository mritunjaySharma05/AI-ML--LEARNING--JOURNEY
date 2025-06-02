# Day 16 – Data Preprocessing: Making Raw Data Model-Ready

**Date:** June 2, 2025

---

## 🔍 Why It Matters

Before any machine learning model can shine, the data must be clean, consistent, and numerical.  
Today’s session was all about preparing real-world data for powerful ML algorithms.

---

## 🧰 Core Preprocessing Skills Learned

| Task                   | Purpose                                                       |
|------------------------|---------------------------------------------------------------|
| Handle Missing Values  | Used `mean()` and `median()` to fill in missing `Age` and `Salary` |
| Encode Categorical     | Transformed `Gender` using `LabelEncoder` (Male = 1, Female = 0)   |
| Scale Features         | Applied `StandardScaler` to normalize `Age` and `Salary`         |

---

## 🧪 Hands-On Workflow

- Loaded a messy dataset with NaNs and text labels
- Imputed missing values
- Encoded text features to numbers
- Scaled numerical values to bring them on the same level

---

## 💡 Key Insight

> Garbage in, garbage out.  
Even the best algorithm can’t fix bad data.  
Preprocessing is the foundation of every great ML model.

---

## 💬 Extra Tips

- For multi-category columns: use `OneHotEncoder`
- To keep values between 0 and 1: try `MinMaxScaler`
- Always explore with `.info()` and `.isnull().sum()` first

---

📓 Code & practice: [`day16.ipynb`](day16.ipynb)
