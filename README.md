# Task-1
# Titanic Data Cleaning & Preprocessing

This project demonstrates essential data cleaning and preprocessing techniques using the Titanic dataset. The objective is to prepare raw data for machine learning models by handling missing values, encoding categorical variables, standardizing features, and removing outliers.

## 📁 Files Included

- `Data_Cleaning_Preprocessing_Titanic.ipynb` – Jupyter Notebook containing the complete data cleaning and preprocessing pipeline.
- `titanic.csv` – Dataset file

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🔍 Steps Performed

1. **Import and Explore Data**
   - Load the Titanic dataset and review its structure and statistics.

2. **Handle Missing Values**
   - Impute missing `Age` values with median.
   - Fill missing `Embarked` values with mode.
   - Drop the `Cabin` column due to excessive missing data.

3. **Encode Categorical Features**
   - Convert `Sex` to binary (0: male, 1: female).
   - One-hot encode `Embarked` values.

4. **Normalize/Standardize Numerical Features**
   - Scale `Age`, `Fare`, `SibSp`, and `Parch` using `StandardScaler`.

5. **Visualize and Remove Outliers**
   - Use boxplots to detect outliers.
   - Remove outliers using the IQR method.

## ✅ Outcome

A cleaned and preprocessed dataset ready for machine learning model training and analysis.


