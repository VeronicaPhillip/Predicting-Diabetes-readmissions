# Predicting-Diabetes-readmissions
# Predicting readmission of Diabetes patients in Hospital

## General Assembly Data Science Immersive - Capstone Project

The objective of the project was to build a machine learning classifier to predict the readmission of diabetes patients, to identify the drivers of readmission and to make recommendations on how to manage/ reduce hospital readmission of diabetes patients.

## Background and Problem Statement

Diabetes is a metabolic disease that causes high blood sugar. The hormone insulin moves sugar from the blood into your cells to be stored or used for energy. With diabetes, your body either doesn't make enough insulin or can't effectively use the insulin it does make.

World health Organization studies shows:
* The number of people with diabetes rose from 108 million in 1980 to 422 million in 2014.
* Diabetes prevalence has been rising more rapidly in low- and middle-income countries than in high-income countries.
* Diabetes is a major cause of blindness, kidney failure, heart attacks, stroke and lower limb amputation. 
* Diabetes impacts all social, economic, and ethnic backgrounds.

As Diabetes is a condition  that can be effectively treated in primary care facilities, high and increasing levels of hospital readmission are cause for concern and need to be investigated by hospitals to identify the causes. 

## What are some of the impacts of high hospital readmission - 

* High readmission rates can point to quality of hospital care
* Impact on the cost to the Healthcare providers - Medicare and Medicaid in the case of the US as this is a US dataset.
* Cost to the patient and their families.
* Psychological impact of repeated admissions, especially if it relates to the same illness.
* Increased staffing levels within the hospital 
* Increase in costs which has a negative impact on hospital budgets.

 
## Project overview

The project was  carried out using the data from the UCI machine learning repository (link).
The data consists of over 100,000 hospital admissions of diabetes patients across 230 US hospitals between 1999 - 2008. The original dataset consists of 101,766 rows and 50 columns.

In this project python was used to build predictive models. Classification techniques used to predict the likelihood of a diabetes patient being readmitted to a hospital using various modelling techniques. Identified the drivers of a readmission and proposed strategies for reducing readmission rates by using the model and other insights from the analysis. Multiple models such as Logistic Regression, Decision Trees, SVM and ensemble methods such as Bagging, and Boosting were used to create models and make predictions using these models. Model performances were evaluated and assessed. 
The dataset was cleaned and transformed using feature engineering and split into training (70%) and testing (30%) test sets.

## Prerequisites

To run the code, there were a number of Python libraries that needed to be installed. These are as follows:

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Logistic RegressionCV
* DecisionTree Classifier
* Bagging Classifier
* StandardScaler
* Metrics
* Train_test_split, cross_val_score, GridSearchCV
* Accuracy_score


## Summary/Findings

* Max_Glu_Serum  and A1C test were not available for all patients diagnosed with diabetes. As these are initial indicators of the disease and can guide the treatment required, these should be initial tests carried out to assist with the diagnosis of diabetes and should form part of the hospitals’ protocol.
* Patients aged 65 to 85 showed high levels of readmission, patient management plans need to be in place to manage these patients in primary care to reduce hospital readmission.
* Medications such as Chlorproomide,  Tolazimide, glimepiride-pioglitazone, Acetohexomide and Glyburide_metformin were identified as contributors to an increase in readmission.   These medications need to be looked at to determine the effectiveness and possible alternative medication prescribed.
* The number of inpatient visits and the number of emergency visits a patient had were drivers of readmission. 
* Medications such as Mitglitol, Insulin, and Glizpizide were identified as contributors to decrease in readmission.
* The number of procedures a patient had was identified as a contributor to a decrease in readmission.


## References


ICD9 Code - [The Web's Free ICD-9-CM & ICD-10-CM Medical Coding](http://www.icd9data.com/2009/Volume1/default.htm)

Rubin (2015). “Hospital Readmission of Patients with Diabetes” https://link.springer.com/article/10.1007/s11892-015-0584-7
