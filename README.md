# HR-data-prediction-
employee working or leaving the company prediction
# Employee Attrition Prediction
<img width="1262" alt="Screenshot 2023-10-12 at 8 11 12 AM" src="https://github.com/ImrulNYC/HR-data-prediction-/assets/147569091/f49870d6-f126-47c0-83c4-6246f5eb564a"><img width="423" alt="Scr<img width="628" alt="Screenshot 2023-10-12 at 8 11 48 AM" src="https://github.com/ImrulNYC/HR-data-prediction-/assets/147569091/723af232-bb53-46f2-8fe7-4be4a96ff693">
eenshot 2023-10-12 at 8 11 30 AM" src="https://github.com/ImrulNYC/HR-data-prediction-/assets/147569091/d6d048a0-4389-476d-a989-d225b7e55af6">



## Introduction

This project focuses on predicting employee attrition in an organization. The dataset used contains various employee attributes such as education, age, gender, and experience. Machine learning models are used to predict whether an employee will leave the organization or continue working.

## Data

The data is loaded from a CSV file named 'Employee.csv'. It contains the following columns:

- `Education`
- `JoiningYear`
- `City`
- `PaymentTier`
- `Age`
- `Gender`
- `EverBenched`
- `ExperienceInCurrentDomain`
- `LeaveOrNot` (0 for 'LEFT' and 1 for 'WORKING')

## Data Preprocessing

- Handling missing values: There are no missing values in the dataset.

- Encoding categorical data:
  - The 'LeaveOrNot' column is mapped from 0 and 1 to 'LEFT' and 'WORKING', respectively.
  - 'Education' is encoded using an ordinal encoder, but the accuracy was not satisfactory.

- Standardization: Numeric features such as 'Age' and 'Experience' are standardized.

## Models

Three machine learning models are trained and evaluated:
- Logistic Regression
- Random Forest Classifier
- K-Nearest Neighbors (KNN)

Run using https://colab.research.google.com

Make sure you have the following Python libraries installed:

numpy
pandas
matplotlib
pandas-datareader
scikit-learn
tensorflow
You can install these libraries using pip:

pip install numpy pandas matplotlib pandas-datareader scikit-learn tensorflow

