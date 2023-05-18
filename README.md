# Cardiovascular Disease Prediction

## Data

The dataset consists of `70 000` records of patients data: `11` features and a target variable.

Input features could be considered as belonging to the following `3` types:

- <u>Objective</u>: factual information;
- <u>Examination</u>: results of medical examination;
- <u>Subjective</u>: information given by the patient.

Features:


| Feature Description                             | Feature Type           | Feature Name  | Data Type                                                    |
|-------------------------------------------------|------------------------|---------------|--------------------------------------------------------------|
| `Age`                                           | Objective Feature      | `age`         | int (days)                                                   |
| `Height`                                        | Objective Feature      | `height`      | int (cm)                                                     |
| `Weight`                                        | Objective Feature      | `weight`      | float (kg)                                                   |
| `Gender`                                        | Objective Feature      | `gender`      | Categorical code                                             |
| `Systolic blood pressure`                       | Examination Feature    | `ap_hi`       | int                                                          |
| `Diastolic blood pressure`                      | Examination Feature    | `ap_lo`       | int                                                          |
| `Cholesterol`                                   | Examination Feature    | `cholesterol` | `1`: `normal`, `2`: `above normal`, `3`: `well above normal` |
| `Glucose`                                       | Examination Feature    | `gluc`        | `1`: `normal`, `2`: `above normal`, `3`: `well above normal` |
| `Smoking`                                       | Subjective Feature     | `smoke`       | binary                                                       |
| `Alcohol intake`                                | Subjective Feature     | `alco`        | binary                                                       |
| `Physical activity`                             | Subjective Feature     | `active`      | binary                                                       |
| `Presence or absence of cardiovascular disease` | <u>Target Variable</u> | `cardio`      | binary                                                       |


All of the dataset values were collected at the moment of medical examination.

## Task

The goal of the project is to analyze Cardiovascular Disease dataset to find which factors are related to the heart diseases.

## Used Tools & Libraries
`numpy`, `pandas`

