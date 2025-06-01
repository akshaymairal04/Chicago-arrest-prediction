# 🚔 Chicago Arrest Prediction

This project uses crime data from the city of Chicago to predict whether a reported crime results in an arrest. A logistic regression model is trained using features such as the type of crime, location, time, and whether the crime was domestic.

## 📊 Features

- Data Cleaning & Preprocessing
- Feature Engineering (e.g. extracting month/year/hour from date)
- Logistic Regression Model
- Model Evaluation with Accuracy Score & Confusion Matrix

## 📍 Dataset

The dataset used originates from the **Chicago Crime Data** portal and includes the following key fields:

- Primary Type (type of crime)
- Description
- Location Description
- Date (timestamp)
- Domestic (yes/no)
- District
- Ward
- Community Area
- Arrest (target variable)

## ⚙️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

📈 Model Performance
The logistic regression model yields an accuracy of approximately 78%, and performance is further analyzed with a confusion matrix.

🔍 Observations
Crime type and location play a major role in determining the probability of arrest.

Temporal features such as hour of the day and month can influence arrest likelihood.


