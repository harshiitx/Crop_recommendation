# Crop Recommendation Model

This repository contains a machine learning model for recommending the most suitable crop to grow based on various environmental factors. The model is built using a Random Forest Classifier and trained on a dataset containing information about different crops and their corresponding growing conditions.

## Dataset

The dataset used for training the model is "Crop_recommendation.csv" which I downloaded from Kaggle. It includes the following features:

- N: Nitrogen content in the soil
- P: Phosphorus content in the soil
- K: Potassium content in the soil
- temperature: Average temperature in Celsius
- humidity: Relative humidity in percentage
- ph: pH value of the soil
- rainfall: Rainfall in millimeters

The target variable is "label", which represents the recommended crop.

## Model

The model used for crop recommendation is a Random Forest Classifier. It is an ensemble learning method that combines multiple decision trees to make predictions. The model is trained on the dataset and achieves high accuracy in predicting the suitable crop.
