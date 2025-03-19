The project is a Diabetes Prediction model using supervised classification with K-Nearest Neighbors (KNN). 

## Project Overview
Dataset: Loaded from a CSV file, likely from a diabetes dataset archive.

### Data Understanding:
Previewing the dataset (head(), tail(), columns, info(), describe()).

Checking for missing values and duplicates.

### Data Transformation:
Replacing zero values in key columns (Glucose, BloodPressure, SkinThickness, Insulin, BMI) with the mean of respective columns.

### Data Visualization:
Using Seaborn for pair plots to understand relationships.

### Model Training:
Using Train-Test Split.

StandardScaler for feature scaling.

KNeighborsClassifier for classification.

Accuracy score & classification report for evaluation.
