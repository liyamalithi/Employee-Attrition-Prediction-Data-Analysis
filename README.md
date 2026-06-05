# Employee Attrition Prediction Data Analysis
<img width="310" height="226.5" alt="univariant analysis" src="https://github.com/user-attachments/assets/fa0d1a78-ada0-4d7d-b0f0-e9a883512a88" />
<img width="355" height="195" alt="bivariant analysis" src="https://github.com/user-attachments/assets/f16ef6f4-6c0f-4ad3-bbb6-c9a28f4f104d" />
<img width="327" height="260" alt="multivariant analysis" src="https://github.com/user-attachments/assets/34df8fb2-5dfd-4df0-b14d-dfa7930eaaf9" />

## Project Overview

Employee attrition is a major challenge for organizations as it increases recruitment and training costs while affecting overall productivity. This project focuses on predicting employee attrition using data-driven techniques and identifying the key factors that influence employees to leave an organization.

#### Goal
Predict employee attrition using machine learning techniques.

#### Objectives
Identify key factors leading to attrition and enable preventive actions

#### Techniques Used
Data cleaning, EDA, classification models (Logistic Regression, Random Forest, etc.)

---

## Problem Statement

Employee attrition can lead to:

- Increased hiring and onboarding costs.
- Loss of experienced talent and organizational knowledge.
- Reduced team productivity and morale.
- Operational disruptions.

This project aims to:

- Predict whether an employee is likely to leave.
- Understand the key drivers of attrition.
- Help HR departments develop retention strategies.

---

## Dataset Description

### Dataset Source
IBM HR Analytics Employee Attrition Dataset

### Dataset Size
- Approximately 1,470 employee records
- 35 features (columns)

### Key Features

#### Demographic Information
(Age, Gender, Marital Status)

#### Job-Related Information
(Job Role, Job Level, Departmenr, Years at Company)

#### Performance and Compensation
(Performance Rating, Monthly Income, Percent Salary Hike)

#### Work Environment Factors
(Overtime, Work-Life Balance, Job Satisfaction, Environment Satisfaction)

#### Target Variable
Attrition (Yes/No)

---

## Data Preprocessing

The following preprocessing steps were performed:

### Data Cleaning
- Checked for missing values.
- Removed duplicate records.
- Ensured data consistency.

### Data Transformation
- Encoded categorical features using:
  - Label Encoding
  - One-Hot Encoding
- Standardized numerical variables using StandardScaler.

### Handling Class Imbalance
- Applied SMOTE (Synthetic Minority Oversampling Technique) to balance attrition classes.

---

## Exploratory Data Analysis (EDA)

EDA was conducted to understand data patterns and relationships.

### Univariate Analysis  
<img width="310" height="226.5" alt="univariant analysis" src="https://github.com/user-attachments/assets/fa0d1a78-ada0-4d7d-b0f0-e9a883512a88" />

- Distribution of employee age.
- Monthly income analysis.
- Attrition rate distribution.
- Overtime frequency.

### Bivariate Analysis
<img width="355" height="195" alt="bivariant analysis" src="https://github.com/user-attachments/assets/f16ef6f4-6c0f-4ad3-bbb6-c9a28f4f104d" />

- Attrition vs Overtime.
- Attrition vs Job Satisfaction.
- Attrition vs Monthly Income.
- Attrition vs Work-Life Balance.

### Multivariate Analysis
<img width="327" height="260" alt="multivariant analysis" src="https://github.com/user-attachments/assets/34df8fb2-5dfd-4df0-b14d-dfa7930eaaf9" />

- Correlation analysis.
- Feature interaction studies.
- Heatmaps and relationship visualization.

---

## Feature Engineering

To improve model performance:

- Converted categorical variables into numerical representations.
- Removed low-variance features.
- Eliminated highly correlated features.
- Selected the most relevant attributes for prediction.

---

## Model Building

### Data Splitting
- Training Set: 70%
- Testing Set: 30%

### Validation Strategy
- Cross-validation used to improve model reliability and generalization.

### Evaluation Metrics
The following metrics were used to evaluate model performance:

- Accuracy
- Precision
- Recall
- F1-Score

---

## Machine Learning Models

The following classification algorithms were implemented and compared:

### Logistic Regression
A baseline model used for binary classification.

### Decision Tree
Captures non-linear relationships and provides interpretability.

### Random Forest
An ensemble learning method that improves prediction accuracy and reduces overfitting.

---

## Results

The models were evaluated and compared using:

- Accuracy Score
- Precision Score
- Recall Score
- F1-Score
- Confusion Matrix

The best-performing model can be selected for deployment based on these evaluation metrics.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Jupyter Notebook

---

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Prediction and Insights
8. Deployment Planning

---

## Future Enhancements

- Deploy the predictive model as part of an HR Analytics Dashboard.
- Periodically retrain the model using updated employee data.
- Integrate employee feedback and exit interview data.
- Develop real-time attrition monitoring capabilities.
- Collaborate with HR teams to design targeted retention strategies.

---

## Conclusion

This project demonstrates how machine learning can be used to predict employee attrition and identify the factors that influence employee turnover. The insights generated can help organizations improve employee retention, reduce operational costs, and make informed HR decisions.
