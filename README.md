# Diabetes Prediction of Pima Indian Women
## by (Valentine Ezenwanne)

## Project Objective
- The objective of the dataset is to diagnostically predict whether a patient has diabetes based on certain 
diagnostic measurements included in the dataset.
- To determine the features that are best suited for predicting diabetes in the women


## Dataset

- This dataset is originally from the National Institute of Diabetes and Digestive and Kidney
Diseases. 
- The dataset contain patients all females at least 21 years old of Pima Indian heritage. It contain independent(several medical predictor variables) and only one target dependent variable (Outcome).



## Tools used
- Data cleaning: Pandas
- Data Visualization: Matplotlib and seaborn
- Scikit library
- Numpy


## Project Steps

The steps taken for the project include:
1.	Data collection
2.	Data Wrangling
3.	Data Exploration
4.	Data Preprocessing
5.	Model Building
6.	Model Evaluation
7.	Hyperparameter Tuning
8.	Choosing the Best Model
9.	Feature Selection





# Summary of findings

## Best Model
 - The best model for the prediction is the **Logistic Regression**. It has an accuracy score of 77.27% and AUC score of 0.75 which is better than Random Forest.
 - Also, from the model evaluation, the Logistic Regression did well with score of 77%
 
## Best Features
 - The top five features that help in predicting diabeties are Insulin, Glucose, Age, BMI and Pregnancies.
 - But, the top two features that stood out is the Insulin and Glucose which of course are the dominant features that determines if a patients is diabetic or not.
 - Insulin is an hormone that regulates blood glucose which when not produce will result in high level of glucose in the blood and this results in diabetes
