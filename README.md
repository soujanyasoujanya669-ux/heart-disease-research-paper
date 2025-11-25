 Heart Disease Detection using Machine Learning

This project implements an AI-based heart disease prediction system using Python and machine learning algorithms. It is inspired by the research paper: *"An Artificial Intelligence Model for Heart Disease Detection Using Machine Learning Algorithms"* (Healthcare Analytics, 2022).

 Overview

The goal is to predict the likelihood of a person having heart disease using various medical indicators. This system uses classification algorithms such as:

- Random Forest Classifier (Primary)
- K-Nearest Neighbors
- Support Vector Machine
- Decision Tree Classifier
- Logistic Regression

The best-performing model is the **Random Forest Classifier**, achieving approximately **83% accuracy**.

 Dataset

The dataset used contains 14 clinical attributes including:

- Age
- Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Cholesterol (chol)
- Fasting Blood Sugar (fbs)
- Resting ECG (restecg)
- Max Heart Rate Achieved (thalach)
- Exercise Induced Angina (exang)
- ST Depression (oldpeak)
- Slope of Peak Exercise ST Segment (slope)
- Number of Major Vessels Colored (ca)
- Thalassemia (thal)
- Target (1 = heart disease, 0 = no heart disease)

 Technologies Used

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

 Model Performance

| Algorithm               | Accuracy |
|------------------------|----------|
| K-Nearest Neighbors    | 87%      |
| Support Vector Machine | 83%      |
| Decision Tree          | 79%      |
| Random Forest          | 84%      |

 Project Structure

