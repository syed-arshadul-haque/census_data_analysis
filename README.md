# Multi-Method Data Analysis on the 2011 UK Census Data

This project is part of academic coursework for the *Intelligent Data and Text Analytics* module. It involves comprehensive data analysis of the 2011 UK Census microdata using multiple machine learning and statistical techniques including descriptive analytics, classification, regression, association rule mining, and clustering.

## 📊 Project Summary

- **Module Code**: M33147  
- **Topic**: Multi-Method Data Analysis of UK Census 2011  
- **Tools Used**: Python, Pandas, Scikit-learn, CatBoost, Matplotlib, Seaborn, Apyori  
- **Dataset**: 2011 UK Census (sample microdata)  

---

## 🧠 Tasks Covered

### Task 1: Descriptive Analytics
- Computed basic statistics for all attributes.
- Converted coded numerical columns to categorical data.
- Used contingency tables, grouped bar charts, stacked bar charts, boxplots, and violin plots.
- Key insights on population demographics, working hours, marital status, student distribution, and health.

### Task 2: Classification
**Target**: Approximated Social Grade  
**Models Used**:
- Random Forest Classifier (84.05% accuracy)
- Bagging Classifier (83.51% accuracy)
- MLP Classifier (83.06% accuracy)
- CatBoost Classifier (84.14% accuracy)

Preprocessing included label encoding, missing value imputation, and feature scaling.

### Task 3: Regression
**Target**: No. of Hours Worked  
**Models Used**:
- Linear Regression (Best R² score: 96.2%)
- Random Forest Regressor (R²: 92.4%)
- CatBoost Regressor (R²: 92.9%)

Evaluated using MAE, MSE, RMSE, and R² metrics.

### Task 4: Association Rule Mining
- Implemented **Apriori** and **FP-Growth** algorithms.
- Mapped encoded values to categorical labels for interpretability.
- Filtered rules with lift > 1 for relevance.

### Task 5: Clustering
**Algorithms Applied**:
- K-Means
- Agglomerative Clustering
- K-Medoids

Identified population clusters based on socio-demographic features.

