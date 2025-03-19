# Treatment-Recommender-system

# Abstract

This project aims to build a Treatment recommendation system using a dataset containing information about various symptoms and their corresponding diagnoses and medications. The system will analyze the user's input symptoms and recommend the diseases and appropriate medications based on the dataset.

# Task:

I devided this project into two part.

## part 1:

I use cosine_similarity where it takes patient symtoms and predict the top 5 diseases that can patient have.

## part 2:

In this part the primary task is to develop a machine learning model that can accurately predict the disease based on a given set of symptoms. The model will be trained on a dataset containing symptom information and corresponding disease diagnoses. Once the disease is predicted, the system will fetch relevant information such as precautions, exercises, descriptions, medications, and diets specific to that disease from other datasets.

# Key Processes:

## Data Preprocessing:
The dataset is first examined for missing values to ensure data integrity. Categorical features are then transformed using one-hot encoding to facilitate numerical representation for machine learning algorithms.

## Cosine Similarity: 
A similarity matrix is computed using cosine similarity to identify patterns and relationships within the data. This matrix is utilized to recommend the most probable disease based on the patient's symptoms.

## Model Training: 
Multiple machine learning models, including Support Vector Machines (SVM), Random Forest, Gradient Boosting, K-Nearest Neighbors (KNN), and Multinomial Naive Bayes, are trained on the preprocessed dataset. These models are designed to predict the disease based on the input symptoms provided by the user.

## Prediction and Recommendation: 
Once the models are trained, they are employed to predict the disease based on the user's input symptoms. Following the prediction, the system retrieves relevant information such as precautions, exercises, descriptions, medications, and dietary recommendations from external datasets. This information is then compiled and presented to the user as part of a comprehensive recommendation system.
