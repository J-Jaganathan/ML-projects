# Stroke Prediction using Decision Tree Classifier

This repository provides a machine learning model to predict whether a person is at risk of having a stroke based on a dataset containing various health features. The model is built using the Decision Tree Classifier with a Gini index criterion for feature selection.

## Dataset

The dataset used for this project is a CSV file containing the following columns:

- **id**: Unique identifier for each record
- **gender**: Gender of the individual (Male, Female, Other)
- **age**: Age of the individual
- **hypertension**: Whether the individual has hypertension (0 = No, 1 = Yes)
- **heart_disease**: Whether the individual has heart disease (0 = No, 1 = Yes)
- **ever_married**: Whether the individual has ever been married (Yes, No)
- **work_type**: Type of work the individual does (Private, Self-employed, Children, Govt_job, Never_worked)
- **Residence_type**: Type of residence (Urban, Rural)
- **avg_glucose_level**: Average glucose level in the blood
- **bmi**: Body Mass Index
- **smoking_status**: Smoking status (never smoked, formerly smoked, smokes, Unknown)
- **stroke**: Whether the individual has had a stroke (1 = Yes, 0 = No)

## Installation

### Prerequisites

Ensure that you have Python 3.x installed along with the following libraries:

- `pandas`
- `numpy`
- `scikit-learn`
- `category_encoders`
- `graphviz`

You can install these dependencies using pip:

```bash
pip install pandas numpy scikit-learn category_encoders graphviz

