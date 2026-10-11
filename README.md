# Pneumonia Risk Prediction - ML Model for Pediatric Emergency

**Built using real-world inspired data from ChildLife Foundation ER experience**

## Problem
Childhood pneumonia kills 800,000 children yearly. Early prediction in ER can save lives. Can we predict pneumonia risk from vitals at triage?

## Dataset
10,000 synthetic pediatric records with 10 features:
Age, Weight, Temperature, Respiratory Rate, SpO2, Cough Duration, Malnutrition, Vaccination status etc.

## Models Used
1. Random Forest - 84% accuracy
2. XGBoost - 87% accuracy (Best)

## Key Findings
- Top 3 predictors: Oxygen Saturation <92%, Respiratory Rate >50, Temperature >38.5
- Malnutrition increases pneumonia risk by 2.3x
- Model can be deployed as triage tool in low-resource ERs

## Tools
Python, Scikit-learn, XGBoost, Pandas, Seaborn

## Run
Open `pneumonia_prediction.ipynb` and run all cells.
