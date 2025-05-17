# Week 3: Crop Recommendation System

## Overview

This project is part of the internship titled **"Crop and Fertiliser Recommendation System using Machine Learning"**. It focuses on developing a machine learning model that recommends the best crop to cultivate based on environmental and soil parameters.

## Contents

- **Dataset**: Contains environmental features like Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, pH, and rainfall.
- **Model Files**: Saved machine learning model and scaler files (`crop_model.sav`, `scaler.sav`).
- **Notebook**: Colab notebook implementing the full pipeline — data preprocessing, feature scaling, model training, evaluation, and deployment.
- **README.md**: This file.

## Features

- Data preprocessing and scaling using `StandardScaler`.
- Model training with Decision Tree Classifier.
- Accuracy evaluation on training and test sets.
- Crop prediction function accepting real-time environmental inputs.
- Saving and loading the trained model and scaler using `pickle`.
- Ready for deployment in web or mobile applications.

## How to Use

1. Open the notebook `Week3_Crop_Recommendation.ipynb` in Google Colab or Jupyter Notebook.
2. Load the dataset and preprocess it.
3. Train and evaluate the model or load the saved model (`crop_model.sav`) and scaler (`scaler.sav`).
4. Use the prediction function to recommend crops based on input parameters.

## Files

| Filename                            | Description                                    |
|-------------------------------------|------------------------------------------------|
| `Week3_Crop_Recommendation.ipynb   | Colab notebook with full project implementation|
| `crop_model.sav`                    | Saved trained crop recommendation model        |
| `scaler.sav`                        | Saved scaler for feature normalization         |
| `Crop_Recommendation.csv`           | Dataset used for training and testing          |
| `README.md`                         | Project overview and instructions              |

