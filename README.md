# Heart Disease Prediction
**Author:** Cristopher Delgado 
**Date:** September 2023

## Overview
This project was completed as part of the Flatiron School Curriculum for Data Science Phase 3 Machine Learning Fundamentals.

Cardiovascular diseases (CVDs) is the leading cause of death globally. In 2019 about 18 million people died from CVDs which represents 32% of all global deaths. Out of this 32% of deaths 85% were the result of a heart attack and stroke. Most CVDs can be prevented with proper behavioral risk mitigation however, a person can not simply tell someone and control their behavioral tasks related to CVD such as unhealthy diet, physical inactivity, etc. Overall, the importance of detecting CVDs as early as possible is essential to properly start counseling and treatment of patients.

## Buisness Understanding
The main goal of this project is to address the idea of diagnostics in Cardiovascular Diseases. Where the stakeholder can be Diagnostic based Medical Device companies that want to integrate machine learning to provide continous monitoring and early deetction of Cardio Vascular Disease related symptoms into developing medical devices or already existent devices. 

## Buisness Problem 
**Stakehokder:** Diagnostic Medical Device Company

The stakeholder wants to determine what related features to CVDs are the most important to monitor. Knowing that information they would like to develop medical devices for either at home use for patients or clinical use devices and potentially use Machine Learning algorithims incorporated into there diagnostic devices and create software as a medical device.

## Data Exploration
### Methodology

1. Perform data cleaning which consists of casting columns to correct data types, dealing with missing values accordingly. 
2. Perform data exploration and view correlations
3. Normalize continuous data in order to have all the data on the same scale.
4. Create Testing and Training sets to train classification models and validate there performances.
5. Observe important features from top performing model.

### Basline vs Optmized Model
To view all the models from baseline and their optimized version please view the notebook. The best performing model was the Xtreme Gradient Boost model. This model 
