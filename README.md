# AI-Based Medical Diagnosis System (Symptom → Disease Prediction)

A machine learning project that predicts likely diseases based on user-reported symptoms using supervised classification models.

## What this project does
• Takes symptom inputs (binary features)  
• Predicts a disease label (prognosis) using trained ML classifiers  
• Evaluates model predictions on a held-out test file  

## Important disclaimer
• This project is for educational purposes only  
• It is not medical advice and should not be used for real clinical decisions  
• Predictions depend heavily on dataset quality and symptom encoding  

## Models used
• Decision Tree  
• Random Forest  
• Naive Bayes (GaussianNB)  
• K-Nearest Neighbors (KNN)  

## Dataset format
• `training.csv` and `testing.csv` contain symptom columns (features)  
• Target label column: `prognosis`  
• Symptom columns are 0/1 encoded  

## Tech stack
• Python  
• Jupyter Notebook  
• pandas, numpy  
• scikit-learn  

## Repo structure
• `notebooks/` – main notebook  
• `data/` – training/testing CSV files  
• `docs/` – project notes and methodology  

## How to run
• Open `notebooks/Project_ML.ipynb` in Jupyter or Google Colab  
• Ensure `data/training.csv` and `data/testing.csv` exist  
• Run all cells to train models and evaluate predictions  

