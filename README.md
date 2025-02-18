# Customer Churn Prediction Model

This repository contains the code for predicting customer churn using a deep learning model built with Keras and TensorFlow. The model uses customer data, such as demographics, account information, and behavior, to predict whether a customer will exit the service.

## Project Overview

This project uses a dataset from a telecommunications company to predict whether a customer will exit (churn) based on various customer features. The model is built using a Neural Network architecture, trained on the processed data, and evaluated for performance.

### Key Features:
- **Customer Demographics:** Age, Geography, Gender
- **Account Information:** Credit score, Balance, Number of Products
- **Behavioral Information:** Tenure, Has Credit Card, Active Member, Estimated Salary

### Tools & Technologies:
- Python
- Pandas
- TensorFlow / Keras
- Scikit-learn
- Jupyter Notebook (for development)
- Matplotlib (for visualizations)

### Steps for Training the Model:
1. **Data Preprocessing:**
   - The data is cleaned and transformed to remove irrelevant columns and encode categorical features such as 'Geography' and 'Gender'.
   
2. **Feature Scaling:**
   - Features are scaled using `StandardScaler` to ensure that all features have similar ranges for better performance in deep learning models.

3. **Model Architecture:**
   - A simple Neural Network model with three hidden layers and a sigmoid output layer is used for binary classification (churn prediction).

4. **Training:**
   - The model is trained using the Adam optimizer and binary cross-entropy loss.

5. **Model Evaluation:**
   - The model is evaluated using accuracy and a confusion matrix.

6. **Saving the Model:**
   - The trained model is saved using `joblib` for later predictions.

### How to Use the Model:
1. **Clone this Repository:**
   ```bash
   git clone <repository_url>
