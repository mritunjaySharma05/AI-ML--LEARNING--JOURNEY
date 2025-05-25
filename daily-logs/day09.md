# Day 9 – Evaluation Metrics: Beyond Accuracy

**Date:** May 24, 2025

---

## ✅ What I Learned Today

Today, I dived deeper into evaluating machine learning models — because **accuracy isn't everything!**  
Here’s what I explored:

---

## Key Concepts

1. **Why Accuracy Isn’t Enough**  
   - Accuracy can be misleading, especially with imbalanced datasets (e.g. 95% accuracy when the model just predicts the majority class).

2. **Confusion Matrix**  
   - A table showing true positives, true negatives, false positives, and false negatives.  
   - Helps visualize model performance.

3. **Precision, Recall, F1-Score**  
   - **Precision**: How many predicted positives are actually positive  
   - **Recall**: How many actual positives were correctly predicted  
   - **F1-Score**: Harmonic mean of precision and recall

4. **Classification Report**  
   - Generated with `classification_report()` from `sklearn.metrics`  
   - Includes precision, recall, F1-score, and support per class

5. **How to Interpret Metrics**  
   - Helps understand what kind of errors your model is making  
   - Useful for improving models in real-world scenarios

---

## Tools & Libraries Used

- `sklearn.metrics`
  - `confusion_matrix()`
  - `classification_report()`
  - `accuracy_score()`

---

## Skills Gained

- Learned how to go **beyond accuracy**  
- Understood the importance of **precision and recall**  
- Built confidence reading **confusion matrices and classification reports**

---

## Notebook

Full implementation and notes are saved in [`day9.ipynb`](day09notes.ipynb).

---

### #Day9 #MachineLearning #ModelEvaluation #Precision #Recall #F1Score #ConfusionMatrix #LearningInPublic #100DaysOfML
