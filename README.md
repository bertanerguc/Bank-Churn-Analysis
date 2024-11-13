# Churn Prediction and Campaign Recommendation App 💸

This Streamlit application predicts customer churn and suggests tailored campaigns to retain at-risk customers. Using a Random Forest Classifier, the app identifies customers likely to churn and provides campaign recommendations to improve retention rates.

## Overview

- **Title**: Churn Prediction and Campaign Recommendation App 💸
- **Description**: This app predicts whether a customer will churn and suggests targeted marketing campaigns.
- **Technologies Used**: 
  - Python
  - Streamlit
  - Pandas
  - Scikit-Learn (Random Forest Classifier)

## Features

1. **Data Upload**: Users can upload a customer dataset in CSV format.
2. **Data Preprocessing**: The app prepares the data by dropping irrelevant columns, handling categorical features with one-hot encoding, and splitting it into features (X) and target (y).
3. **Model Training**: The app trains a Random Forest Classifier to predict churn.
4. **Performance Evaluation**: Displays a classification report for the model's performance on the test set.
5. **Campaign Suggestions**: Provides targeted campaign suggestions for customers likely to churn, e.g., "Special Bank Interest Rate Discount."

## How to Use

1. **Upload Data**: Click the "Upload File" button to load a CSV file with customer data.
2. **View Data**: Uploaded data will be displayed for preview.
3. **Run Model**: The app will preprocess the data, train a model, and predict churn.
4. **Get Campaign Suggestions**: For customers predicted to churn, the app will suggest retention strategies.

## Files

- `app.py`: Main file containing the Streamlit app code.
- **Dependencies**: Streamlit, Pandas, Scikit-Learn

## Example CSV Format

The application expects the uploaded CSV file to contain columns similar to the following:
- `RowNumber`, `CustomerId`, `Surname`, `Exited` (target column), along with other features relevant for predicting churn.

## License
This project is licensed under the MIT License.
