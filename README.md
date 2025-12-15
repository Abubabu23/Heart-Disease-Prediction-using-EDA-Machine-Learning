# Heart Disease Prediction using EDA & Machine Learning

This project focuses on predicting the presence of **heart disease** using **Exploratory Data Analysis (EDA)** and **Machine Learning models**.  
The goal is to identify **high-risk patients early** based on clinical features such as age, cholesterol, chest pain type, resting blood pressure, and exercise-related attributes.



## Business Objective

To build a **data-driven classification model** that predicts whether a patient is likely to have heart disease (**Yes / No**).  
This can assist healthcare professionals in:
- Early diagnosis
- Preventive care planning
- Reducing overall health risks



## Dataset Overview

The dataset contains patient-level clinical data, including:
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Maximum Heart Rate (MaxHR)
- Exercise Angina
- Oldpeak
- Other medical indicators

Target variable:
- **Heart Disease (Yes / No)**


## Exploratory Data Analysis (EDA)

EDA was performed to understand data patterns and key risk factors.

### Key EDA Insights
- Strong indicators of heart disease:
  - **MaxHR**
  - **Oldpeak**
  - **Chest Pain Type**
  - **Exercise Angina**
- Correlation analysis revealed meaningful relationships between clinical features and heart disease.
- Clear differences in distributions between patients with and without heart disease.

### Visualizations Used
- Heatmaps
- Boxplots
- Bar charts
- Categorical comparisons



## Machine Learning Models

Multiple models were trained and evaluated.

### Logistic Regression
- **Accuracy:** 88%
- **Recall (Heart Disease):** 93%
- Highly interpretable
- Preferred for medical decision-making due to transparency

### Random Forest Classifier
- **Accuracy:** 88%
- Balanced precision and recall
- Captures non-linear relationships effectively

### Model Selection
Although both models performed well, **Logistic Regression** was selected as the final model due to:
- High recall for detecting heart disease
- Simplicity and interpretability for healthcare use cases



## Key Learnings

- Proper EDA greatly improves model understanding and feature selection
- Careful handling of categorical variables is critical in healthcare datasets
- Simple models can perform as well as complex ones and are easier to explain
- Model interpretability is crucial in medical applications



## Tech Stack

- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**



## Project Structure

- heart_disease_eda_ml.ipynb # EDA and model development notebook
- data/ # Dataset (if included)
- README.md # Project documentation

