#  Health Risk Prediction using Artificial Neural Networks (ANN)  
This project leverages Artificial Neural Networks (ANN) to predict cardiovascular risk based on synthetic patient health data. The model uses deep learning techniques to classify 
patients into risk categories, helping identify individuals with higher likelihood of cardiovascular diseases.

# Project Overview
Predicting cardiovascular risk is critical for early diagnosis and preventive care. In this project, I developed an ANN-based classification model 
capable of predicting cardiovascular disease risk using synthetic health data.To handle class imbalance, the project integrates SMOTE (Synthetic Minority Oversampling Technique), 
which improves the model’s ability to generalize and enhances its sensitivity to minority classes.

# Key Features
Developed and trained an Artificial Neural Network (ANN) using TensorFlow and Keras.
Handled class imbalance using SMOTE, improving recall for underrepresented risk classes.
Implemented a complete data preprocessing pipeline with Pandas and Scikit-learn.
Evaluated performance using metrics such as accuracy and confusion matrix.
Achieved improved model generalization and interpretability through data balancing and model optimization.

# Tools & Technologies
TensorFlow, Keras, Scikit-learn,Numpy, Pandas, SMOTE

# Workflow
#### 1. Data Preparation
Load and clean synthetic patient health data
Handle missing values and feature scaling

#### 2. Data Balancing (SMOTE)
Apply SMOTE to oversample minority classes

#### 3. Model Development
Design and build ANN using TensorFlow/Keras
Configure layers, activation functions, and optimizer

#### 3. Model Training & Evaluation
Train ANN on balanced dataset
Evaluate using performance metrics

#### 4. Results Visualization
Plot accuracy and confusion matrix
