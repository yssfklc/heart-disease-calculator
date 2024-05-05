# Predicting Heart Disease Using Machine Learning

This notebook looks into various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes.

## Problem Definition

In a statement,

Given clinical parameters about a patient, can we predict whether or not they have heart disease?

## Data

The original data come from the Cleaveland data from the UCI Machine Learning Repository:

[UCI Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease)

There is also a version of it available on Kaggle:

[Kaggle Heart Disease Dataset](https://www.kaggle.com/datasets/heptapod/uci-ml-datasets)

## Evaluation

If we can reach 95% accuracy at predicting whether or not a patient has heart disease during the proof of concept, we'll pursue the project.

## Features

**Create data dictionary**

- id (Unique id for each patient)
- age (Age of the patient in years)
- origin (Place of study)
- sex (Male/Female)
- cp chest pain type ([typical angina, atypical angina, non-anginal, asymptomatic])
- trestbps resting blood pressure (resting blood pressure (in mm Hg on admission to the hospital))
- chol (serum cholesterol in g/dl)
- fbs (if fasting blood sugar > 120 mg/dl)
- restecg (resting electrocardiographic results) -- Values: [normal, stt abnormality, lv hypertrophy]
- thalach: maximum heart rate achieved
- exang: exercise-induced angina (True/False)
- oldpeak: ST depression induced by exercise relative to rest
- slope: the slope of the peak exercise ST segment
- ca: number of major vessels (0-3) colored by fluoroscopy
- thal: [normal; fixed defect; reversible defect]
- num: the predicted attribute

## Preparing the Tools

We are going to use pandas, Matplotlib, and NumPy for data analysis and manipulation.
