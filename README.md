# Heart-Disease-Risk-Classifier
This repository contains a machine learning project focused on heart disease prediction based on a clinical dataset including features such as Age, Sex, ChestPainType, RestingBP, Cholesterol, MaxHR, ST_Slope and more.

This project aims to build a machine learning model capable of predicting **heart disease** based on clinical attributes of patients.  
The dataset includes the following features:

- Age  
- Sex  
- ChestPainType  
- RestingBP  
- Cholesterol  
- FastingBS  
- RestingECG  
- MaxHR  
- ExerciseAngina  
- Oldpeak  
- ST_Slope  
- HeartDisease (target)


##  Project Overview

This repository contains:

- Python code responsible for preprocessing, training, and evaluating ML models
- three classification models:
  - Logistic Regression  
  - K-Nearest Neighbors (KNN)  
  - Decision Tree Classifier  
- evaluation metrics: classification report, confusion matrix, and K-Fold cross-validation

The project demonstrates a complete workflow from data preprocessing to model evaluation.



##  Data Preprocessing

The dataset contains several categorical variables:

- `ChestPainType`
- `Sex`
- `RestingECG`
- `ExerciseAngina`
- `ST_Slope`

These were transformed into numerical values using manual mapping.

## Model Evaluation

Evaluation metrics include:

- accuracy

- precision

- recall

- f1-score

  ## Conclusions
This project demonstrates how machine learning can be applied to medical datasets to predict heart disease risk. 
By comparing multiple models, we can determine which algorithm performs best on this dataset and provides the most reliable predictions.
