# Treatment-Recommender-system

#Abstract

This project aims to build a Treatment recommendation system using a dataset containing information about various symptoms and their corresponding diagnoses and medications. The system will analyze the user's input symptoms and recommend the diseases and appropriate medications based on the dataset.

#Task:

I devided this project into two part.

##part 1:

I use cosine_similarity where it takes patient symtoms and predict the top 5 diseases that can patient have.

##part 2:

In this part the primary task is to develop a machine learning model that can accurately predict the disease based on a given set of symptoms. The model will be trained on a dataset containing symptom information and corresponding disease diagnoses. Once the disease is predicted, the system will fetch relevant information such as precautions, exercises, descriptions, medications, and diets specific to that disease from other datasets.

#Key Processes:

Data Preprocessing: I check for missing values. Then i encoded categorical features using one-hot encoding.
cosine Similarity: Find similarity Matrix using cosine Similarity and recommend the most probable disease a patient can have.
Model Training: I use multiple machine learning model like SVM, RandomForest, GradientBoosting, KNN, multinomial Naive bayes on the preprocessed dataset to predict the disease based on the input symptoms.
Prediction and Recommendation: After training the model, it will be used to predict the disease based on the user's input symptoms. Once the disease is predicted, the system will fetch relevant information like precautions, exercises, descriptions, medications, and diets from other datasets and provide recommendations accordingly.
