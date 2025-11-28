
This project predicts whether a person is diabetic based on medical diagnostic measurements using a machine learning model. The dataset used is the popular Pima Indians Diabetes Dataset.

## Project Overview

The goal of this project is to build a prediction system that can classify a person as:

- **1 → Diabetic**
- **0 → Non-Diabetic**

The machine learning pipeline includes:
- Data cleaning  
- Feature scaling  
- Train–test split  
- Model training (Logistic Regression / Random Forest)
- Evaluation (Accuracy, Classification Report)
- A prediction system to test custom input values
  
## Dataset
The dataset contains 8 medical feature columns and one target column (`Outcome`):
- Pregnancies  
- Glucose  
- BloodPressure  
- SkinThickness  
- Insulin  
- BMI  
- DiabetesPedigreeFunction  
- Age  
- Outcome (target)

## Machine Learning Workflow

### 1. Data Preprocessing
- Handled missing values
- Standardized features using `StandardScaler`
- Split into train and test sets

### 2. Model Training
Models used:
- Logistic Regression
- RandomForestClassifier (for improved accuracy)

### 3. Evaluation
- Accuracy Score  

## 🔍 Prediction System

A prediction system was implemented where you can manually input values such as:
input = (1,85,66,29,0,26.6,0.351,31)
after the input model predict if the persion is diabetic or not.


