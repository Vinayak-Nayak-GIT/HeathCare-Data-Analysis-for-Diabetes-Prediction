# Diabetes Onset Prediction Project

## Overview

NIDDK (National Institute of Diabetes and Digestive and Kidney Diseases) research creates knowledge about and treatments for the most chronic, costly, and consequential diseases.

The dataset used in this project is originally from NIDDK. The objective is to predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. The project aims to build a model to accurately predict whether the patients in the dataset have diabetes or not.

## Dataset Description

The dataset consists of several medical predictor variables and one target variable (Outcome). Predictor variables include the number of pregnancies the patient has had, their BMI, insulin level, age, and more.

## Variables Description

- **Pregnancies:** Number of times pregnant
- **Glucose:** Plasma glucose concentration in an oral glucose tolerance test
- **BloodPressure:** Diastolic blood pressure (mm Hg)
- **SkinThickness:** Triceps skinfold thickness (mm)
- **Insulin:** Two-hour serum insulin
- **BMI:** Body Mass Index
- **DiabetesPedigreeFunction:** Diabetes pedigree function
- **Age:** Age in years
- **Outcome:** Class variable (either 0 or 1). 268 of 768 values are 1, and the others are 0.

## Project Objectives

- Build a predictive model for diabetes onset using machine learning techniques.
- Perform comprehensive data preprocessing, including handling missing values and feature engineering.
- Conduct exploratory data analysis (EDA) to gain insights into the dataset.
- Evaluate and compare multiple machine learning algorithms for model selection.
- Create a user-friendly Tableau dashboard for data visualization and reporting.

## Key Achievements

- Developed and fine-tuned a machine learning model with an accuracy of 85%.
- Identified important features contributing to diabetes prediction.
- Created informative visualizations in Tableau to present project findings.

## Technologies Used

- Python
- Scikit-Learn
- Pandas
- Matplotlib
- Tableau

## Folder Structure

- `/data`: Contains the dataset used for analysis.
- `/notebooks`: Jupyter notebooks with code for data preprocessing, modeling, and EDA.
- `/visualizations`: Images and Tableau dashboard files.

## Getting Started

To replicate or explore this project, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the `/notebooks` folder and run the Jupyter notebooks to see the code.
3. Check out the Tableau dashboard in the `/visualizations` folder for interactive visualizations.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
