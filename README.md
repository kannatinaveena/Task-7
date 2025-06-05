# 🧠 Support Vector Machines (SVM) Classification

This repository contains the implementation and evaluation of the Support Vector Machine (SVM) algorithm for binary classification using both **linear** and **RBF (Gaussian)** kernels. The objective is to understand the concept of margin maximization, the kernel trick, hyperparameter tuning, and performance evaluation of SVMs.

---

## 📂 Dataset

- **Name**: Breast Cancer Wisconsin Diagnostic Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)) or `sklearn.datasets`
- **Format**: CSV (`breast-cancer.csv`)
- **Target Variable**: `diagnosis` (converted: `M=1`, `B=0`)

---

## 📌 Objectives

- Load and preprocess a real-world dataset
- Train SVM classifiers with both Linear and RBF kernels
- Visualize decision boundaries using selected features
- Tune hyperparameters like `C` and `gamma` using `GridSearchCV`
- Evaluate model performance using cross-validation

---

## 🛠️ Tools & Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib / Seaborn
- Scikit-learn

---

## 🧾 Steps Performed

### 📁 Dataset Preparation
- Loaded dataset from CSV
- Converted `diagnosis` labels to binary values
- Performed standardization using `StandardScaler`

### 🧠 Trained SVM Classifiers
- Trained Linear SVM (`kernel='linear'`)
- Trained RBF SVM (`kernel='rbf'`)
- Evaluated each with `accuracy_score` and classification report

### 📈 Visualized Decision Boundaries
- Selected two features (`radius_mean` and `texture_mean`)
- Created 2D plots of decision regions for both kernels
- Overlayed test points to visualize classification accuracy

### 🔧 Hyperparameter Tuning
- Used `GridSearchCV` to tune `C` and `gamma` for RBF kernel
- Selected best parameters and evaluated the optimized model

### 🔁 Cross-Validation
- Performed 5-fold cross-validation for both models
- Reported mean accuracy and fold-wise performance

---

## 📊 Results

| Kernel     | Accuracy | Best Parameters (if tuned) |
|------------|----------|----------------------------|
| Linear     | ~96–98%  | C = 1.0                    |
| RBF        | ~97–99%  | C = 10, gamma = 0.01       |

- Decision boundaries clearly show separability
- Hyperparameter tuning improved RBF performance
- Cross-validation confirms model generalization

---

---

## 👩‍💻 Author

- **Name:** Kannati Naveena  
- **GitHub:** [@kannatinaveena](https://github.com/kannatinaveena)  
- **Internship:** AI & ML Internship  
- **Task:** Task 7 – SVM  
- **Date:** June 2025

---

## 📮 Submission

- **GitHub Repo Link:** Paste your repo link here before submission  
- **Submit via Internship Portal:** before 10:00 PM on the due date.

---


