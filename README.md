# #  Machine Learning Model for Heart Disease Diagnosis
## Business Problem:
Cardiovascular diseases (CVDs) are the number one cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of five CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common event caused by CVDs and this dataset contains 11 features that can be used to predict a possible heart disease.
People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.# Author: Abdelhamead Ibrahim

# Data:

The Data conisited of a total of 12 columns with various information. This included the following: 

1. Age  918 non-null    int64  
2. Sex 918 non-null    object 
3. ChestPainType   918 non-null    object
4. RestingBP       918 non-null    int64  
5. Cholesterol     918 non-null    int64  
6. FastingBS       918 non-null    int64
7. RestingECG      918 non-null    object
8. MaxHR          918 non-null    int64
9. ExerciseAngina  918 non-null    object
10. Oldpeak         918 non-null    float64
11. ST_Slope        918 non-null    object 
12. HeartDisease    918 non-null    int64

### Methods
The Data preparation steps I used were to first explore the Dataset using pandas as well as data visualization tools like matplotlib and seaborn to explore the Dataset. 

##The Target for Prediction : 
The Target will be the column Heart Disease since that column has a 0 for negative (this indicates that the patient does not have heart disease) and 1 for positive(this indicates that the patient has heart disease).

### Results:


<img width="723" alt="Screen Shot 2022-09-23 at 8 50 24 AM" src="https://user-images.githubusercontent.com/4527669/192002277-f2014a18-2e8f-48ca-a003-4b701e26a146.png">





# Model

Report the most important metrics
For the base Logistic Regression model there was a higher reduction in Type 2 Error in the Model 
<img width="723" alt="Screen Shot 2022-09-23 at 8 50 24 AM" src="https://user-images.githubusercontent.com/4527669/192002324-c2dbae59-3ad8-4205-b177-1a9e286f1d96.png">

![download](https://user-images.githubusercontent.com/4527669/192002226-9d70f034-8156-45ae-ae9e-ea735eebcb57.png)



### Recommendations:
My Recommendation is that we use the Base Logistic Regreession model to diagnose Heart Disease 

### Limitations & Next Steps:
The Limitations of my dataset is that the data was gathered from patients in Hungary. We can use data from other countries just in case there is a higher or lower occurence of Heart Disease in Hungary compared to other countries. 

For further information
For any additional questions, please contact me by email @ abdelhameadibrahim@gmail.com 
