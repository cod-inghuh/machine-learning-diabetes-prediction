# Diabetes Classification Using Random Forest

## Overview
This project applies machine learning techniques to predict whether a patient has diabetes based on medical diagnostic measurements. The goal is to build a binary classification model that can distinguish between diabetic and non-diabetic patients using clinical data.

The analysis was performed using Python in a Jupyter Notebook, with a focus on data exploration, model training, and evaluation.

## Dataset
The dataset used in this project is the **Pima Indians Diabetes Dataset**, which contains medical diagnostic measurements for female patients.

Features included in the dataset:

- Pregnancies – Number of pregnancies
- Glucose – Plasma glucose concentration
- Blood Pressure – Diastolic blood pressure (mm Hg)
- Skin Thickness – Triceps skin fold thickness
- Insulin – 2-Hour serum insulin
- BMI – Body mass index
- Diabetes Pedigree Function – Genetic likelihood of diabetes
- Age – Age of the patient

Target variable:

- Outcome  
  - 0 = Non-diabetic  
  - 1 = Diabetic

## Project Workflow

### 1. Data Exploration
Initial exploration of the dataset to understand the distribution of variables and identify potential patterns.

### 2. Data Preparation
Data cleaning and preprocessing steps were applied to prepare the dataset for machine learning analysis.

### 3. Model Training
A **Random Forest classifier** was used to train the model and perform the classification task.

### 4. Model Evaluation
The performance of the model was evaluated using standard classification metrics.

## Machine Learning Model

The model used in this project is **Random Forest**, an ensemble learning method that builds multiple decision trees and combines their predictions.

Advantages of Random Forest include:

- Ability to model complex relationships
- Reduced risk of overfitting compared to a single decision tree
- Insight into feature importance

## Libraries Used

The project was implemented using the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Results
The model was evaluated using metrics such as accuracy and confusion matrix analysis. These metrics help assess how well the model can correctly classify diabetic and non-diabetic patients.

## Repository Structure
