# DS605 — Fundamentals of Machine Learning
## Lab Assignment 5: Scikit-learn vs Manual NumPy Implementation
## Student id-202618032
## Name:- Shah Divy Jigarkumar
This repository contains the implementation and analysis for **Lab Assignment 5** of **DS605 — Fundamentals of Machine Learning**.

The assignment focuses on implementing and comparing **Linear Regression** and **Logistic Regression** using two approaches:

1. **Scikit-learn**
2. **Manual implementation using NumPy and Pandas**

The objective is to understand not only how machine-learning models are used through libraries, but also how their underlying mathematical and computational procedures work.

---

## Dataset

The dataset used in this assignment is the:

**UCI Productivity Prediction of Garment Employees Dataset**

The dataset contains productivity-related information collected from a garment manufacturing environment.

### Dataset characteristics

- Records: **1,197**
- Original features: **15**
- Target variable for regression: `actual_productivity`
- Classification target: `MeetsTarget`

The classification target was created using:

```text
MeetsTarget = 1 if actual_productivity >= targeted_productivity
MeetsTarget = 0 otherwise
