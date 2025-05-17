# Week 3: Fertiliser Recommendation System

## Overview

This project is part of the internship titled **"Crop and Fertiliser Recommendation System using Machine Learning"**. It focuses on building a machine learning model to recommend the best fertiliser based on environmental, soil, and crop parameters.

## Contents

- **Dataset**: Contains features such as Temperature, Humidity, Moisture, Soil Type, Crop Type, Nitrogen (N), Potassium (K), and Phosphorous (P), along with the target fertiliser labels.
- **Model Files**: Saved machine learning model and scaler files (`fertilizer_model.sav`, `fertilizer_scaler.sav`).
- **Notebook**: Colab notebook implementing the entire pipeline — data loading, preprocessing, feature scaling, model training, evaluation, and deployment.
- **README.md**: This file.

## Features

- Data preprocessing with label encoding of categorical features.
- Feature scaling using `StandardScaler`.
- Model training using Decision Tree Classifier.
- Model accuracy evaluation on training and test datasets.
- Fertiliser recommendation function that accepts real-time inputs.
- Saving and loading the trained model and scaler using `pickle`.
- Ready for integration into web or mobile applications.

## How to Use

1. Open the notebook `Week3_Fertiliser_Recommendation.ipynb` in Google Colab or Jupyter Notebook.
2. Load the dataset `Fertilizer Prediction.csv` and preprocess the data.
3. Train and evaluate the decision tree model or load the saved model (`fertilizer_model.sav`) and scaler (`fertilizer_scaler.sav`).
4. Use the recommendation function to predict the best fertiliser based on input parameters.

## Files

| Filename                                | Description                                      |
|-----------------------------------------|--------------------------------------------------|
| `Week3_Fertiliser_Recommendation.ipynb` | Colab notebook with full project implementation  |
| `fertilizer_model.sav`                  | Saved trained fertiliser recommendation model    |
| `fertilizer_scaler.sav`                 | Saved scaler for feature normalization           |
| `Fertilizer Prediction.csv`             | Dataset used for training and testing            |
| `README.md`                             | Project overview and instructions                |

---

