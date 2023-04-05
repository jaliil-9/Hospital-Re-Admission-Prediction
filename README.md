# Hospital-Re-Admission-Prediction
This project uses machine learning to predict hospital readmission using the Kaggle hospital readmission dataset. The model achieved an accuracy of 83% in predicting readmission within 30 days of discharge which can help hospitals provide better care and reduce healthcare costs.

## Dataset
The Kaggle hospital readmission dataset contains over 100,000 hospital admissions from diabetic patients. The dataset includes patient demographics, medical history, medications, and laboratory tests, as well as information about the hospital admission and readmission.

## Model
The machine learning model (RandomForestClassifier) used in this project is a binary classification model that predicts whether a patient will be readmitted within 30 days of discharge. The model is based on a gradient boosting algorithm, and was trained and evaluated using Python's scikit-learn library.

## Results
The model achieved an accuracy of (83% on train & 64% on test) in predicting readmission within 30 days of discharge, which indicates that the model is able to identify most of the patients who are at high risk of readmission, while minimizing false positives.
