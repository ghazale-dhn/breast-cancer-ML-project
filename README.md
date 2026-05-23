# Breast Cancer Classification

A machine learning project that predicts whether a breast tumor is 
malignant or benign using the Wisconsin Breast Cancer dataset from scikit-learn.

This is my first ML project. I built it while starting my MSc in Data Mining,
coming from a biology background.

---

## What the project does

Trains a Random Forest classifier on 30 tumor measurements (like cell radius, 
texture, and symmetry) for 569 patients. The model predicts one of two outcomes:
- Malignant (cancerous)
- Benign (non-cancerous)

Final accuracy: ~96% on the test set (20% holdout).

---

## What I learned

- How to load and explore a built-in sklearn dataset
- The difference between sensitivity and specificity — and why both matter 
  in a medical context
- How to read a confusion matrix properly
- That fixing environment and package errors is half the work

---

## Files

| File | Description |
|------|-------------|
| project1_breast_cancer.ipynb | Main notebook with all code and results |
| requirements.txt | Python packages needed to run it |

---

## How to run it

1. Clone the repository
