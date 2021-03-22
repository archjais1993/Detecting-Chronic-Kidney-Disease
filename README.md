# Detecting-Chronic-Kidney-Disease
# Factors Causing Chronic Kidney Disease
Built the relationship model identifying factors leading to chronic kidney disease. 

### TABLE OF CONTENTS
* [Objective](#objective)
* [Conceptual Model](#conceptual_model)
* [Variable Selection](#variable_selection)
* [Data Exploration](#data_exploration)
* [Logistic Regression Model](#logistic_regression_model)
* [Results](#results)

## OBJECTIVE 
* To  identify factors causing chronic kidney disease

* Build a predictive model to identify subjects, who could potentially be affected by CKD.

* Interpret the statistical model to estimate the impact of each factor leading to CKD.

*NOTE:* Data is restricted for public access

## CONCEPTUAL Model

![GitHub Logo](https://github.com/archjais1993/Detecting-Chronic-Kidney-Disease/blob/2e8dfa2829fb915a77b6c5fdef89005de1815f56/conceptual_model.png)


## VARIABLE SELECTION

Based on the conceptual model

* The variables capturing details such as income, martial status, education, source of medical care and insurance details, were discarded.

* The variables like BMI, waist size, weight and height were discarded, considering no direct impact with the target variable.

* Total cholesterol, inheritance  of diabetes and hypertension from family were removed

### STATISTICAL TESTS

Chi – Square test to identify the relation between categorical variables and target (binary) variables.

T-test to identify the relationship with target variables and the variable under consideration

![GitHub Logo](https://github.com/archjais1993/Detecting-Chronic-Kidney-Disease/blob/3a1fc4f222823c0f0f15a46e41e2718aa226ed48/data_exp.png)

## LOGISTIC REGRESSION

Built the logistic regression model to understand the relation the between *variables* (predictors for the chronic kidney disorder) and the *traget variable* (weather an individual is affected or not)

![GitHub](https://github.com/archjais1993/Detecting-Chronic-Kidney-Disease/blob/2e8dfa2829fb915a77b6c5fdef89005de1815f56/Logistic%20Regression.png)

![GitHub](https://github.com/archjais1993/Detecting-Chronic-Kidney-Disease/blob/3a1fc4f222823c0f0f15a46e41e2718aa226ed48/results.png)

## RESULTS

Factors like AGE, RACE(hispanic), HDL levels, HYPERTENSION, DIABETES and CARDIO VASCULAR DISEASES proved to be the significant predictors for the target variable.
