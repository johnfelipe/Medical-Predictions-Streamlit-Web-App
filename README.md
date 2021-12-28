# Medical-Predictions-Streamlit-Web-App

This app is used to predict the medical state of an individual
The disease sections include ->
1. Covid-19
2. Diabetes
3. Heart Disease 


Each prediction page is conneceted with a Machine Learning Model which uses Random Forest Classifier to predict the results.
Also we have 3 different datasets used for each prediction.
We can land into each prediction site of the web app from the options in the Navigation Menu.


Each prediction is done with the help of 4 features which will be taken as input from the user.
The most relevant features are taken into consideration for prediction also these features can be found out with simple tests or analysis without visiting any doctor.
So the victim can get a broad overview of their health condition.
The features taken into consideration are as follows=
1. Covid-19 = dry cough, fever, sore throat, breathing problem
2. Diabetes = glucose, insulin, BMI, age
3. Heart Disease = chest pain, BP, cholestrol, max HR

The feature selection is carefully done under the supervision of a medical science student.


After the modeling part the model is deployed using Streamlit library on Streamlit Share so that the app is available for usage for everyone.
