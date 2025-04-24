# 🚢 Task 1: Data Cleaning & Preprocessing – Titanic Dataset

This project is part of the AI & ML Internship. The objective is to learn and apply basic data preprocessing techniques on a real-world dataset.

---

## 🧠 Objective

To clean and prepare raw data for machine learning using the Titanic dataset. The goal is to understand and implement data preprocessing steps including handling nulls, encoding, scaling, and outlier detection.

---

## 📁 Dataset

- **Source**: [Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- **Used File**: `titanic.csv`

---

## 🔧 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

---

## 📊 Tasks Performed

### 1. Import & Explore
- Loaded the dataset and printed basic info (shape, datatypes, missing values).
- Explored statistics using `.describe()` and `.info()`.

### 2. Handle Missing Values
- Filled missing `Age` values with the **median**.
- Filled missing `Embarked` values with the **mode**.
- Dropped `Cabin` column due to too many missing values.

### 3. Encode Categorical Features
- Converted `Sex` and `Embarked` columns using **Label Encoding**.

### 4. Feature Scaling
- Standardized `Age` and `Fare` using **StandardScaler**.

### 5. Outlier Detection & Removal
- Visualized outliers using **boxplots**.
- Removed outliers from `Fare` using **IQR method**.

---

## 📈 Final Output

- Cleaned dataset ready for machine learning.
- Final shape after preprocessing: *(depends on your result, e.g., 870 rows × 9 columns)*

---

## 📂 Repository Structure

