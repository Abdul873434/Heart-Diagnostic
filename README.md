# Heart-Diagnostic
This project encompassed an in-depth data analysis, data preprocessing, model development, and evaluation through machine learning methods, with the goal of supporting heart disease diagnosis.
Project Overview
Heart disease remains a leading global health issue, responsible for significant morbidity and mortality. Early diagnosis is essential for effective intervention and improved patient outcomes. In this project, we use machine learning techniques to analyze patient data and predict heart disease presence, helping to identify key risk factors and support clinical decision-making.
Dataset
Source: Cleveland Heart Disease dataset from the UCI Machine Learning Repository.
Attributes:age: Age of the patient in years.

sex: Biological sex of the patient, where:

1 = Male
0 = Female
cp: Chest pain type, where:

0 = Typical Angina
1 = Atypical Angina
2 = Non-anginal Pain
3 = Asymptomatic
trestbps: Resting blood pressure (in mm Hg) on admission to the hospital.

chol: Serum cholesterol level in mg/dl.

fbs: Fasting blood sugar, indicating if the blood sugar level is greater than 120 mg/dl, where:

1 = True
0 = False
restecg: Resting electrocardiographic results, which indicate heart rhythm, categorized by specific patterns.

thalach: Maximum heart rate achieved during a test.

exang: Exercise-induced angina, where:

1 = Yes
0 = No
oldpeak: ST depression induced by exercise relative to rest, indicating possible heart abnormalities.

slope: The slope of the peak exercise ST segment, which may show changes in heart performance during stress.

ca: Number of major vessels (0–3) colored by fluoroscopy, showing blood flow blockage in heart vessels.

thal: Thalassemia type, with values:

3 = Normal
6 = Fixed Defect
7 = Reversible Defect
target: Diagnosis of heart disease (the outcome variable), where:

1 = Presence of heart disease
0 = Absence of heart disease
Key Sections
Problem Definition
Can we predict the presence of heart disease based on clinical parameters of a patient?

Data Exploration & Preprocessing
Exploration of data to understand attribute distributions, handle missing values, and prepare features for model training.

Model Building & Evaluation
Implementation and evaluation of various classification algorithms, such as Logistic Regression, Decision Trees, and Random Forest, to identify the best-performing model. The project aims to achieve at least 95% accuracy.

Insights and Interpretability
Analysis of feature importance to identify the strongest predictors of heart disease, enabling a better understanding of contributing risk factors.
Conclusion
A summary of model performance and insights on the potential for deploying this model as a clinical support tool.
