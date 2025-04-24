# 🧹 Titanic Dataset - Data Cleaning & Preprocessing

This repository contains my submission for **Task 1** of the **AI & ML Internship Program**. The task focuses on data cleaning and preprocessing using the Titanic dataset from Kaggle.

---

## 📝 Task Objective

To learn and implement essential data preprocessing techniques, including:
- Handling missing values
- Encoding categorical variables
- Feature scaling (normalization/standardization)
- Outlier detection and removal

---

## 📁 Dataset

- **Source**: [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- **File used**: `titanic.csv`

---

## ⚙️ Tools Used

- Python
- Pandas
- NumPy
- Seaborn & Matplotlib (for data visualization)
- Scikit-learn (for scaling)

---

## 🔍 Steps Performed

1. **Exploration**:
   - Displayed dataset info, types, and missing values.

2. **Missing Value Treatment**:
   - `Age` filled with **median**.
   - `Embarked` filled with **mode**.
   - `Cabin` dropped due to many missing entries.

3. **Categorical Encoding**:
   - Converted `Sex` and `Embarked` using **One-Hot Encoding** (`get_dummies`).

4. **Feature Scaling**:
   - Applied **StandardScaler** to `Age` and `Fare`.

5. **Outlier Detection & Removal**:
   - Used **boxplot** to visualize outliers in `Fare`.
   - Removed rows with `Fare > 300` as potential outliers.

6. **Saved Cleaned Data**:
   - Final cleaned dataset exported as `titanic_cleaned.csv`.

---

## 📦 Files in This Repo

- `titanic_cleaned.csv` – Cleaned dataset ready for ML modeling
- `task1_titanic_preprocessing.ipynb` – Colab notebook with complete code
- `README.md` – Summary of the task

---

## 📌 Learning Outcomes

- Importance of preprocessing in ML pipelines
- Difference between **normalization vs standardization**
- Practical experience with **real-world dataset cleaning**
- Knowledge of handling **nulls**, **categorical data**, and **outliers**

---

## ✅ Task Completed Successfully!

Submitted as part of the AI & ML Internship Program – **Task 1: Data Cleaning & Preprocessing**

