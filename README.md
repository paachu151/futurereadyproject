# Diabetes Prediction - My Future Ready Project
Hey there, My name is Prahalad Krishna. As a part of my internship project, i made a diabetic predictor using ML, Azure web app and much more
• This repository consists of files required to deploy a ___Web App___ created with ___Flask___ on ___Microsoft___ Azure.# diabetes_predictor
The project helps the user to identify whether someone is suffering from diabetes by simply inputting certain values like BMI, Glucose level, Blood pressure etc. with the help of a Kaggle database.

By using the statistical data about how certain aspects like BMI, Glucose level, Insulin level, age etc. impact if an individual is prone to diabetes or not, the project will be able to tell the user if the person has diabetes or not by entering those values. So in a way the project will help in monitoring the likelihood of someone developing diabetes. The project can be extended to include other diseases prediction which I will incorporate later down the road. 

# Project Synoptics
# Industry Name: 
Health
# Project Title: 
Diabetes Prediction
# Problem Statement/Opportunity:
AU’s Health department considers this is the right time for them to do a good usage of the dataset they were able to build by providing an open diabetes predictor to the community.it should serve as an advisor for triage purposes.
with the information provided by the patient (Age, Gender, Body Mass Index, Blood Pressure, Serum 1-6, and current diabetes level – Y) the engine should be able to predict what the diabetes rate should look like in 12 months from the date of the inquire.
the engine should be able to provide further recommendations to patients projected to be running over the acceptable threshold that separates diabetic people from non-diabetic people.
it should be consumed exposed through APIs so whatever external channel could take advantage of it. The bot is the preferred way to consume the engine, as far as AU’s health team would like to begin with.

# Project Description:
Diabetes prediction has to be built from scratch as Microsoft Cognitive Services doesn’t offer an specialized API for for that purpose.
There is a recommendation piece in there, which could be a good fit for Recommendations API in Azure (we need to validate that).
There is, obviously, a Dataset involved. It does mean we’re gonna need some storage capability for that purpose.
There is also a need for compute Meaning that we need a place for us to run the models we’re going to build.
Once we’re satisfied with the results our model is returning, we need, somehow to publish it in the format of Restful API, so that different channels can consume.
AU’s Health department would like to have a Bot serving as interface between patients and the predictor in Azure.

# Primary Azure Technology: 
Azure Web app, Azure Resource Group, Azure Machine Learning

