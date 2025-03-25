# Heart-Disease-Model
This model attempts to predict heart disease in individuals using 918 observations of 11 features including age, sex, resting blood pressure, fasting blood sugar, etc. We use a tuned logistic regression model for the classification of data points into one of two groups. These groups are individuals without heart disease and individuals with heart disease.

The dataset used was taken from Kaggle and is a combination of 5 smaller datasets mostly taken from different hospitals around the world. These were taken from hospitals in Cleveland, Hungary, Switzerland, and Long Beach VA and includes the Statlog (Heart) dataset. 

In the process of creating this model, we will follow these steps:
1. Import the necessary packages
2. Download the dataset
3. Explore the dataset through correlation coefficients and visualizations to uncover trends
4. Split the data into training, validation, and test sets
5. Search for and fill any missing values from the dataset
6. Scale the numeric data
7. Encode the categorical data to numerical data
8. Train and evaluate the model
9. Tune hyperparameters to reduce overfitting and increase accuracy
10. Evaluate the final accuracy of the model on the test set
11. Predict results of future patients
12. Save and Load the Trained Model

### Citation
fedesoriano. (September 2021). Heart Failure Prediction Dataset. Retrieved March 21, 2025 from [Kaggle](https://www.kaggle.com/fedesoriano/heart-failure-prediction).
