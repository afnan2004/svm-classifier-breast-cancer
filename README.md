# 🧠 Internship Task 7 - Support Vector Machines (SVM)

This repository contains my implementation of Task 7 from the AI & ML Internship Program, focusing on **Support Vector Machines (SVM)** for binary classification using the Breast Cancer Dataset.

## 📌 Objective
To implement linear and non-linear classification using SVM and understand key concepts such as:
- Margin maximization
- Kernel trick
- Hyperparameter tuning (C, gamma)
- Cross-validation
- Model evaluation

---

## 📂 Contents

- `task7.ipynb`: Main Jupyter notebook containing code, results, and evaluation.
- `README.md`: Project overview and details.

---

## 🛠 Tools & Libraries
- Python
- Scikit-learn
- NumPy
- Matplotlib

---

## 📊 Dataset
- **Breast Cancer Dataset** (from Scikit-learn)
- Binary classification task (malignant vs. benign)

---

## 🔍 What I Did

1. Loaded and prepared the dataset.
2. Trained a Support Vector Machine (SVM) with:
   - Linear Kernel
   - RBF Kernel
3. Performed hyperparameter tuning using `GridSearchCV` for:
   - `C` (regularization parameter)
   - `gamma` (kernel coefficient for RBF)
4. Evaluated model performance with:
   - Accuracy score
   - Classification report
5. Used cross-validation for robust performance evaluation.

---

## 📈 Results

- Achieved high accuracy using both kernels.
- GridSearchCV identified optimal hyperparameters.
- Linear SVM performed comparably to RBF on this dataset.

---

## 🧠 Key Learnings

- How SVMs work for linearly and non-linearly separable data.
- Importance of kernel choice and parameter tuning.
- How to validate models with cross-validation.

---

## 🔗 Submission

- [Dataset Source - Breast Cancer Dataset (Kaggle)](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset)


## ✅ Completed Tasks

- [x] Binary classification dataset
- [x] SVM with linear and RBF kernels
- [x] Hyperparameter tuning (C, gamma)
- [x] Cross-validation
- [x] Accuracy & classification report
- [ ] (Optional) 2D decision boundary visualization
