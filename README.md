# ITechnolabs
We have to predict Patients who are having diabetes. In this Project we have two csv files.

1- diabetes_train_analysis.csv --> This constains all the information about the patient.

id             
cholesterol        
gluc               
smoke              
alco               
active             
pressure        
diabetes

2-diabetes_train_info.csv --> This contains the basic details of the patient.

id        
age        
height      
weight      
gender 


I have joined the 2 tables and done preprocessing on the data set which include data cleaning, Encoding the Categorical fieds, identifying the outliers in the data set.
Feature engineering has been perfomed on pressure column. outliers were identified in Age and pressure column. Domain knowledge was taken from the google about the Pressure high and low level value.

Various Feature selection method has been applied.

Feature scaling has been done.

Selecting the base model step has been applied by looping all the Baseline classification algo to check which base Machine Learning algo is performing well.

Logisic regression was performing the best among all. Still performed Hyper parameter tuning on Random forest. But Type 1 and type 2 error was less acieved in Logistic regression.


Model is saved by the name (diabetes-prediction-Logistic-model.pkl)

coding file notebook (Diabetes prep.ipynb)

I have tried my best to explain each and every line in the code along with Logical explanation.
