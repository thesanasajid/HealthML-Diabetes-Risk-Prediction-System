# HealthML-Diabetes-Risk-Prediction-System

## Overview

HealthML is a machine learning project developed to predict diabetes risk using patient health data and provide basic diet recommendations. The project combines BMI calculation, disease risk assessment, and diabetes prediction using a Random Forest Classifier.

## Features

- BMI (Body Mass Index) Calculation
- Disease Risk Classification (Low, Moderate, High)
- Diabetes Risk Prediction
- Diet Recommendation Based on Risk Level
- Machine Learning Model Training and Evaluation
- Random Forest Classification Algorithm

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Streamlit
- Google Colab

## Dataset

This project uses the Pima Indians Diabetes Dataset.

### Input Features

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

### Target Variable

- Outcome
  - 0 = No Diabetes
  - 1 = Diabetes

## Machine Learning Model

### Algorithm

Random Forest Classifier

### Data Split

- Training Data: 80%
- Testing Data: 20%

## Project Workflow

1. Load Diabetes Dataset
2. Preprocess Data
3. Split Data into Training and Testing Sets
4. Train Random Forest Model
5. Evaluate Model Accuracy
6. Predict Diabetes Risk
7. Generate Diet Recommendations

## Project Structure

```text
HealthML-Diabetes-Risk-Prediction/
│
├── diabetes.csv
├── healthml.py
├── requirements.txt
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/HealthML-Diabetes-Risk-Prediction.git
```

Move into the project directory:

```bash
cd HealthML-Diabetes-Risk-Prediction
```

Install required libraries:

```bash
pip install -r requirements.txt
```

## Requirements

```txt
pandas
numpy
scikit-learn
streamlit
pyngrok
```

## Running the Project

Run the Python script:

```bash
python healthml.py
```

## Sample Prediction

Example Input:

```text
Pregnancies: 6
Glucose: 148
Blood Pressure: 72
Skin Thickness: 35
Insulin: 0
BMI: 33.6
Diabetes Pedigree Function: 0.627
Age: 50
```

Example Output:

```text
HIGH DIABETES RISK 🚨

Diet Plan

Breakfast:
- Oats
- Boiled Eggs
- Green Tea

Lunch:
- Brown Rice
- Grilled Chicken
- Salad

Dinner:
- Vegetables
- Yogurt

Avoid:
- Sugar
- Soft Drinks
- Fast Food
```

## Results

The model is evaluated using:

- Accuracy Score
- Confusion Matrix

## Future Improvements

- Streamlit Web Application
- Personalized Diet Recommendations
- Multiple Disease Prediction
- Health Dashboard
- Model Deployment on Cloud



