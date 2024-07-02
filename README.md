# Heart_Disease_Prediction
In this project , we develop a machine learning model to predict the presence or absence of heart disease in a patient based on various medical attributes. Our goal is to develop a predictive model capable of accurately identifying individuals with heart disease.

# Data Collection:
The dataset taken from the Kaggle website.
Collect data with 14 attributes: age, sex, chest pain type, resting blood pressure, serum cholesterol, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, exercise-induced angina, ST depression (old peak), slope of the peak exercise ST segment, number of major vessels, and thalassemia.

# Data Preprocessing:
Clean and preprocess the collected data to handle missing values, outliers, and inconsistencies.
Cleaning and organizing the data to ensure accuracy and consistency.

# Machine Learning Algorithm:
Algorithm Selection: We Use Logistic Regression due to its effectiveness in binary classification problems.
Divide the dataset into training and testing sets (e.g., 80/20 split),Train the Logistic Regression model using the training data and Use the testing data to make predictions.

# Evaluation:
Performance Metrics: Evaluate using accuracy, precision, recall and F1 score.
Interpret the accuracy alongside other metrics like precision, recall, and F1 score to assess overall model performance.
Confusion Matrix: Analyze true positives, true negatives, false positives, and false negatives to understand model predictions.

# RESULT
Present the results of the machine learning model in terms of its accuracy and effectiveness in Heart disease prediction using Logistic Regression. Include visualizations and comparisons between predicted and actual counts to highlight the model's performance. We used the Confusion Matrix for the comparisons. We also Calculated accuracy, precision, recall and F1 score to evaluate the model. The final output is 0 or 1 (Because it is binary classification problem), where 0 is Healthy Heart, 1 is Defective Heart. When we give the new input to Predict, it should contain the 13 attributes. By taking those attributes, the model converted values from -1 to 1. The model gave an output of “0”(The Person does not have a Heart Disease) or “1” (The Person has Heart Disease).

