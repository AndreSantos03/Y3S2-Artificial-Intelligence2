# Supervised Learning Model

## Project Overview

This project is the second assignment for the Artificial Intelligence course in the Bachelor's program in Informatics and Computing Engineering at the University of Porto. The goal of this project is to implement a supervised learning model to predict autism spectrum disorder (ASD) traits based on various features.

## Data

[Dataset](https://www.kaggle.com/datasets/vaishnavisirigiri/autism-dataset-for-toddlers)

The dataset used in this project contains information about individuals and their ASD traits. It includes features such as demographic information, family history of ASD, and behavioral characteristics. The target variable indicates whether an individual exhibits ASD traits or not.

## Data Preprocessing

Before building the predictive model, we performed several preprocessing steps on the data:

1. **Handling Missing Values**: We addressed missing values in the dataset through imputation or removal.

2. **Feature Engineering**: We created new features and encoded categorical variables as needed.

3. **Class Balancing**: As the dataset was imbalanced, we employed the NearMiss algorithm to balance the classes by undersampling the majority class.

## Model Development

We employed various supervised learning algorithms to predict ASD traits based on the features:

1. **Logistic Regression**: A simple yet effective linear model for binary classification.

2. **Random Forest Classifier**: A versatile ensemble method that combines multiple decision trees.

3. **Support Vector Machine (SVM)**: A powerful algorithm for classification tasks, particularly effective in high-dimensional spaces.

## Model Evaluation

We evaluated the performance of each model using the following metrics:

- **Classification Report**: Provides precision, recall, F1-score, and support for each class.
  
- **Confusion Matrix**: Visualizes the performance of the classification model.

- **Accuracy on Random Samples**: Calculated accuracy on a subset of randomly selected samples for additional validation.

## Results

The models were trained and evaluated using the provided dataset. Performance metrics such as precision, recall, and accuracy were calculated to assess the effectiveness of each model in predicting ASD traits.

## Conclusion

In conclusion, this project provided hands-on experience in building, training, and evaluating supervised learning models for binary classification tasks. By implementing various algorithms and evaluating their performance, we gained insights into the strengths and limitations of each approach in predicting ASD traits based on demographic and behavioral features. Further optimization and fine-tuning of the models could potentially improve their predictive accuracy and generalization to unseen data.

## Contributos

- André Santos (up202108658)
- Pedro Beirão (up202108718)