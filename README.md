# HealthML-Diabetes-Risk-Prediction-System

## Overview

HealthML is a machine learning project that predicts diabetes risk using patient health data and provides a basic diet recommendation based on the prediction result.

The project uses:

- Python
- Pandas
- Scikit-Learn
- Random Forest Classifier
- Google Colab

## Features

✅ Calculates BMI

✅ Classifies disease risk based on BMI

✅ Trains a Random Forest Machine Learning model

✅ Predicts Diabetes Risk

✅ Provides a basic diet recommendation

## Dataset

This project uses the Pima Indians Diabetes Dataset.

### Features

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

### Target

- Outcome
  - 0 = No Diabetes
  - 1 = Diabetes

## Machine Learning Model

Algorithm Used:

- Random Forest Classifier

Train-Test Split:

- 80% Training Data
- 20% Testing Data

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/HealthML-Diabetes-Risk-Prediction.git
```

Install required libraries:

```bash
pip install pandas scikit-learn numpy
```

## Running the Project

Run the Python file:

```bash
python healthml.py
```

## Sample Output

```text
Accuracy: 0.90

Prediction:
HIGH DIABETES RISK 🚨

Diet Plan:
- Oats
- Boiled Eggs
- Green Tea
- Brown Rice
- Grilled Chicken
```

## Future Improvements

- Streamlit Web Application
- Personalized Diet Plans
- Multiple Disease Prediction
- Health Dashboard
- Model Deployment
