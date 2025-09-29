# Titanic EDA – Task 5 🚢

##
**Harsh Sharma**

## 📌 About
This repository contains **Exploratory Data Analysis (EDA)** performed on the **Titanic dataset** as part of my Data Analyst Internship – **Task 5**.  
The main objective is to extract insights using visual and statistical exploration.

## 🛠 Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SciPy  
- Statsmodels  

## 📂 Files in this Repository
- `titanic-task5.ipynb` → Jupyter Notebook with full EDA  
- `report.pdf` → PDF export of the notebook (findings + visuals)  
- `train_cleaned.csv` → Cleaned version of dataset after preprocessing (optional)  

## 🔍 Steps Performed
1. **Data Inspection** – Checked dataset structure, missing values, and summary statistics.  
2. **Data Cleaning** – Handled missing values (Age, Cabin, Embarked), created new features (Title, FamilySize, IsAlone, HasCabin).  
3. **Univariate Analysis** – Distribution of Age, Fare, Pclass, Sex, and Embarked.  
4. **Bivariate Analysis** – Relationship of features with Survival (Sex vs Survived, Pclass vs Survived, etc.).  
5. **Multivariate Analysis** – Correlation heatmap, pairplots, interaction effects.  
6. **Statistical Tests** – Chi-square test for categorical features, t-test for Age differences.  
7. **Multicollinearity Check** – Used VIF to detect correlated predictors.  
8. **Summary of Insights** – Key patterns and trends identified.  

## 📊 Key Insights
- **Females** had a much higher survival rate than males.  
- **1st class passengers** were more likely to survive compared to 2nd and 3rd class.  
- Passengers with a **cabin number (HasCabin=1)** had better chances of survival.  
- **Younger passengers** and those traveling in families had higher survival chances.  
- Fare distribution was highly skewed; passengers who paid higher fares tended to survive more.  


---
