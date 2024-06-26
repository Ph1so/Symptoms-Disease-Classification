### Disease Prediction Machine Learning Project

# Overview

This repository contains a machine-learning project focused on classifying diseases based on a pool of over 130 symptoms. This project aims to develop a model that can accurately predict an individual's disease based on various combinations of symptoms.

# Dataset

The dataset used for this project consists of 4920 samples. The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/itachi9604/disease-symptom-description-dataset).

# Approach

In this project, I employed several different machine learning models from Scikit-learn to train and evaluate the predictive model. The steps involved in the process include:

- Importing data: Cleaning the dataset, handling missing values, and scaling features.
- Model training: Training the selected algorithm on the preprocessed dataset.
- Model evaluation: Assessing the performance of the trained model using appropriate metrics such as accuracy, precision, recall, and F1-score.

# Results

Currently, the trained model achieves an accuracy score of 99.4% using Decision Trees. 

<img width="727" alt="accuracy score" src="https://github.com/Ph1so/Disease-Prediction/assets/56458094/a9183a4a-7432-4026-a21d-eb0f2112aca2">

# Usage

To run this project locally, follow these steps:

1. Open this [link](https://colab.research.google.com/drive/1UfI3Nj5jgRPzssAC03drFVRqsctfYaQu?usp=sharing) to access the Google Colab file and make a copy
2. Download dataset files from this repository
3. Run the Google Colab to preprocess the data, train the model, make predictions, and save the model.
   
# Technologies Used

Programming languages: `Python`

Libraries: `Scikit-learn` `Pandas` `NumPy` `Matplotlib` `Seaborn`

# Future Improvements

Some potential enhancements for this project include:

- Exploring how the order of severity can affect the accuracy
- Tuning hyperparameters to optimize the model's performance.
- Deploying the trained model as a web application or API for real-time predictions.

# Acknowledgments
Special thanks to Pranay Patil for providing the dataset used in this project.
