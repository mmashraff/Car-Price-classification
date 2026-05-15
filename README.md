# Car Price Classification — Machine Learning Project

## Project Overview
Built a classification model to predict whether a car's price 
is Low, Medium, or High based on its features.

## Objective
Apply supervised machine learning (Random Forest) to classify 
car prices using real-world automotive data.

## Tools & Libraries
- Python (Pandas, NumPy)
- Scikit-learn (RandomForestClassifier, LabelEncoder, StandardScaler)
- Matplotlib & Seaborn (Data Visualization)

## Project Steps
1. **Data Loading & Exploration** — shape, info, describe, missing values
2. **Data Cleaning** — removed duplicates, renamed columns
3. **Feature Engineering** — Label Encoding for categorical variables
4. **Target Creation** — converted Price to 3 classes (Low / Medium / High)
5. **Model Training** — Random Forest Classifier (80/20 split)
6. **Evaluation** — Accuracy Score, Confusion Matrix, Feature Importance

## Key Results
- Trained Random Forest model on 200+ car records
- Evaluated using Confusion Matrix (normalized & raw)
- Identified most important features affecting car price

## Files
| File | Description |
|------|-------------|
| `Ai_Project.ipynb` | Full notebook (EDA + Model) |
| `Car_Price.csv` | Raw dataset |
