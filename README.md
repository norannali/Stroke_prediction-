# Stroke Prediction

## Overview
Stroke is a severe medical condition that requires early detection for effective treatment. This project develops a **machine learning model** to predict the likelihood of stroke based on patient health attributes.

## Dataset
The dataset contains various medical and demographic attributes of patients, including:
- `gender` - Male, Female, or Other
- `age` - Age of the patient
- `hypertension` - 0 (No) or 1 (Yes)
- `heart_disease` - 0 (No) or 1 (Yes)
- `ever_married` - Yes or No
- `work_type` - Type of employment
- `residence_type` - Urban or Rural
- `avg_glucose_level` - Average glucose level in blood
- `bmi` - Body Mass Index
- `smoking_status` - Smokes, Formerly Smoked, Never Smoked
- `stroke` - 0 (No stroke) or 1 (Stroke)

## Methodology
The following steps were followed:
1. **Data Preprocessing** - Handling missing values, encoding categorical features, and normalizing numerical data.
2. **Exploratory Data Analysis (EDA)** - Identifying trends and correlations.
3. **Feature Engineering** - Selecting relevant features.
4. **Model Training** - Using classification models:
   - Logistic Regression
   - Random Forest
   - Support Vector Machine (SVM)
   - XGBoost
   - Neural Networks
5. **Evaluation** - Comparing models using accuracy, precision, recall, and F1-score.

## Installation
To run the project, install the required libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
