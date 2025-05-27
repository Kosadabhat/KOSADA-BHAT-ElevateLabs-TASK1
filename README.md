# KOSADA-BHAT-ElevateLabs-TASKS

# TASK1
# Titanic Dataset Preprocessing

## Overview

This repository contains the preprocessing and cleaning of the Titanic dataset as part of my internship task. The main objective was to prepare the data by handling missing values, encoding categorical features, scaling numerical features, and removing outliers.

## Files

- `Kosada Bhat TASK1 ElevateLabs.ipynb` — Jupyter/Colab notebook with the preprocessing code.
- `cleaned_titanic_dataset.csv` — The cleaned and preprocessed dataset.

## Preprocessing Steps Performed

1. **Handled Missing Values**  
   - Filled missing `Age` values with the median.  
   - Filled missing `Embarked` values with the mode.

2. **Encoded Categorical Variables**  
   - Applied One-Hot Encoding to `Sex` and `Embarked` columns.

3. **Standardized Numerical Features**  
   - Standardized `Age` and `Fare` using `StandardScaler`.

4. **Outlier Detection and Removal**  
   - Visualized outliers with boxplots.  
   - Removed outliers from `Age` and `Fare` using the IQR method.

## Author

Kosada Bhat




