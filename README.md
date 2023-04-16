# Sepsis-Analysis

MIMIC-III Dataset is from the Beth Israel Deaconess Medical Center between 2001 and 2012
Using the MIMIC-III dataset under the OMOP Common Data model
Goal: Examining the association between certain characteristics in relation to the condition Sepsis using Machine Learning


Use SQL to interact with database - finding and joining vital table/data to creating a joint dataset between sepsis and 7 other features to train on, which are: race, gender, acute renal failure syndrome, congestive heart failure, atrial fibrillation, essential hypertension, urinary tract infectious disease.

Applying Python to preprocessing data - including converted gender and other categorical diagnosis to boolean value (1 and 0). Converted all ethnicities listed into nominal integers and created a visualization (histogram) for each feature with sepesis generally. 

Chooses estimators:
K-NN,
Logistic Regression,
Random Forest Classification,
Support Vector Machine,
Neural Network,
XGBoost Classification,
XGBoost Regressor,



Constraints and Restriction:

Limited in neural networks model due to time constraints

Could not look up other features such as (parents diagnosed to sepsis)

Could not fit the whole population dataset (approximately 46,000 subjects) -> decided to test only on 10,000 subjects with randomly sampling
