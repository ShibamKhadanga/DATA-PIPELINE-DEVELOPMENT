# DATA-PIPELINE-DEVELOPMENT
**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: SHIBAM KHADANGA

**INTERN ID**: CT04DF1351

**DOMAIN**: Data Science

**BATCH DURATION**: Jun 5th, 2025 to July 5th, 2025

**MENTOR NAME**: NEELA SANTHOSH

DESCRIPTION OF TASK

This task is part of the CODTECH Data Science Internship.

## 📌 Objective
Build a data preprocessing pipeline that performs:
- **Data Cleaning** (handling missing values)
- **Transformation** (scaling and encoding)
- **Loading** (preparing data for model input)

## 🛠️ Tools Used
- `pandas`
- `scikit-learn`
  - `SimpleImputer` for missing values
  - `StandardScaler` for numerical scaling
  - `OneHotEncoder` for categorical encoding
  - `Pipeline` and `ColumnTransformer` to automate the process

## 🧪 Dataset
- Used the **Titanic** dataset from the `seaborn` library (publicly available).
- Target: `survived`
- Features: `age`, `fare` (numerical), `sex`, `embarked` (categorical)

## 🧰 Preprocessing Steps
1. **Numerical columns:**
   - Missing values filled with **mean**
   - Standardized using **StandardScaler**

2. **Categorical columns:**
   - Missing values filled with **most frequent**
   - Converted to numeric using **OneHotEncoder**

3. **Combined all preprocessing steps** using `ColumnTransformer` and `Pipeline`

## 🚀 How to Run

### 🔧 Install requirements
```bash
pip install pandas scikit-learn seaborn



https://github.com/ShibamKhadanga/DATA-PIPELINE-DEVELOPMENT/issues/1#issue-3142315241



