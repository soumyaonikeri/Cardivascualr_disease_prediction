# Cardiovascular Disease Prediction

## Project Overview

Cardiovascular disease, also known as heart disease, is one of the leading causes of death worldwide. This project aims to predict whether a person has a high risk of cardiovascular disease based on various health metrics such as age, gender, cholesterol level, blood pressure, smoking habits, and more.

We use various machine learning models like Logistic Regression, Support Vector Machines (SVM), K-Nearest Neighbors (KNN), Decision Trees, and Random Forests to perform the prediction. After evaluating these models, the **Random Forest Classifier** was selected as the final model based on its performance.

## Dataset

The dataset used in this project includes the following features:

- **id**: Patient identifier
- **age**: Age of the person (in days)
- **gender**: Gender of the person (1 = female, 2 = male)
- **height**: Height in centimeters
- **weight**: Weight in kilograms
- **ap_hi**: Systolic blood pressure
- **ap_lo**: Diastolic blood pressure
- **cholesterol**: Cholesterol level (1 = normal, 2 = above normal, 3 = well above normal)
- **gluc**: Glucose level (1 = normal, 2 = above normal, 3 = well above normal)
- **smoke**: Smoking habit (1 = smoker, 0 = non-smoker)
- **alco**: Alcohol intake (1 = yes, 0 = no)
- **active**: Physical activity (1 = active, 0 = inactive)
- **cardio**: Presence of cardiovascular disease (1 = has disease, 0 = no disease)

## Project Structure

The project contains the following key files:

- `cardiovascular_disease.csv`: The dataset used for training and testing.
- `heart_disease_predictor.pkl`: The final Random Forest model used for predictions.
- `scaler.pkl`: Scaler used to preprocess the data.
- `main.py`: Python script that performs data preprocessing, model training, and evaluation.
- `README.md`: This file explaining the project structure and instructions.
- `requirements.txt`: List of required Python packages to run the project.

## Installation

1. **Clone the Repository**:
   Clone this repository to your local machine using the command:
   ```bash
   git clone https://github.com/your-username/cardio-prediction.git
   cd cardio-prediction
