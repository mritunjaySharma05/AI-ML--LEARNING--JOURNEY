# Day 6 – Data Cleaning with Pandas

**Date:** May 21, 2025

---

## What is Data Cleaning?

Data cleaning is the process of preparing raw data by handling missing values, fixing formats, and removing inconsistencies. It’s a crucial first step before any analysis or machine learning.

Using **Pandas**, I learned to clean tabular datasets effectively.

---

## Key Operations I Learned

| Concept                | Example Code                                |
|------------------------|---------------------------------------------|
| Detect Missing Values  | `df.isnull()`                               |
| Drop Missing Rows      | `df.dropna()`                               |
| Fill Missing Values    | `df.fillna(value)`                          |
| Rename Columns         | `df.rename(columns={"old": "new"})`         |
| Remove Duplicates      | `df.drop_duplicates()`                      |
| Convert Data Types     | `df["col"] = df["col"].astype(int)`         |
| Clean String Data      | `df["col"].str.strip()`                     |

---

## Practice Context

I practiced with sample datasets containing missing values, duplicate rows, mixed types, and dirty string columns.

These operations helped me shape clean datasets ready for analysis or modeling.

---

## Notebook

My full notes and code are available in the [`day6.ipynb`](day06notes.ipynb) notebook.

---

### #Day6 #Pandas #DataCleaning #Python #100DaysOfML #LearningInPublic
