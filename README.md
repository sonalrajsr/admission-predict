# -*- coding: utf-8 -*-
"""Generate README.md for Admission Predict GRE.ipynb"""

content = """
# Admission Prediction using GRE Scores

## Overview
This project involves building a machine learning model to predict the chance of admission based on various features such as GRE scores, TOEFL scores, University Rating, SOP, LOR, CGPA, and Research experience. The model is built using a neural network implemented in TensorFlow/Keras.

## Dataset
The dataset used for this project is "Admission_Predict.csv", which contains the following columns:
- `GRE Score`: GRE score of the applicant (out of 340)
- `TOEFL Score`: TOEFL score of the applicant (out of 120)
- `University Rating`: Rating of the university (out of 5)
- `SOP`: Strength of the Statement of Purpose (out of 5)
- `LOR`: Strength of the Letter of Recommendation (out of 5)
- `CGPA`: Undergraduate GPA (out of 10)
- `Research`: Research experience (1 if the applicant has research experience, 0 otherwise)
- `Chance of Admit`: Probability of admission (ranging from 0 to 1)

## Requirements
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow
