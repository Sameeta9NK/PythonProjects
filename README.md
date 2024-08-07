Overview - 

In this project I am using Support Vector Machine (SVM) for predicting the likelihood of diabetes 
in individuals based on various health factors. I have built this model using diabetes dataset from the National Institute of Diabetes and Digestive and Kidney Diseases.

The data consists of the below columns that entail the health factors of each individual - 

Pregnancies: Number of times pregnant
Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
BloodPressure: Diastolic blood pressure (mm Hg)
SkinThickness: Triceps skin fold thickness (mm)
Insulin: 2-Hour serum insulin (mu U/ml)
BMI: Body mass index (weight in kg/(height in m)^2)
DiabetesPedigreeFunction: Diabetes pedigree function
Age: Age (years)
Outcome: Class variable (0 or 1)

Data Cleaning and Preparation

Due to the presence of numerical columns with varying scales, I have scaled the data to prevent any one feature from dominating the model training process, 
ensuring all features contribute equally to the model's learning. 
My X variable consists of all health factors such as Glucose levels, BloodPressure, Skin Thickness, Insulin, etc 
which will be utilized to determine the Outcome (Y) - Diabetes (1) or Not Diabetes (0).

Model Training 
I doing a 20-80 split to create test and train data, respectively. I am then running the The model which gives about 75% accuracy.
