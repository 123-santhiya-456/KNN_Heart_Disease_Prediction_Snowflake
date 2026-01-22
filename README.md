# Heart Disease Prediction using KNN and Snowflake

## Problem Statement
The objective of this project is to predict the presence of heart disease in patients using the K-Nearest Neighbors (KNN) algorithm. The patient data is stored in a Snowflake database and includes various medical features.

## Algorithm Used
- K-Nearest Neighbors (KNN)

## Dataset
- Source: Snowflake Database (`HEART_DB.PUBLIC.HOTEL_BOOK`)  
- Features: Various medical attributes (age, cholesterol, blood pressure, etc.)  
- Target: Presence or absence of heart disease

## Steps Involved
1. Connect to Snowflake and fetch data
2. Load data into a Pandas DataFrame
3. Perform preprocessing (handle missing values, feature selection)
4. Split data into training and testing sets
5. Scale features using StandardScaler
6. Train KNN classifier
7. Make predictions on the test set
8. Evaluate performance using Accuracy and Classification Report

## Evaluation Metrics
- Accuracy
- Classification Report

## How to Run
```bash
pip install -r requirements.txt
python knn_heart_disease.py
Security Note

Do not include Snowflake credentials in the code.

Use environment variables or config files to store credentials securely.

Conclusion

The KNN classifier successfully predicts heart disease presence, demonstrating the ability to use Snowflake as a data source for real-world medical datasets.
