Heart Disease Classification with Decision Trees
Overview
This project focuses on using machine learning techniques, specifically Decision Trees, to classify heart disease based on various medical attributes. The dataset used contains demographic and clinical parameters of patients.

Table of Contents
Overview
Dataset
Installation
Usage
Dependencies
Contributing
License
Dataset
The dataset (heart.csv) used for this project contains the following columns:

age: Age of the patient
sex: Gender of the patient (1 = male; 0 = female)
cp: Chest pain type (0-3)
trestbps: Resting blood pressure (mm Hg)
chol: Serum cholesterol (mg/dl)
fbs: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
restecg: Resting electrocardiographic results (0-2)
thalach: Maximum heart rate achieved
exang: Exercise induced angina (1 = yes; 0 = no)
oldpeak: ST depression induced by exercise relative to rest
slope: Slope of the peak exercise ST segment (0-2)
ca: Number of major vessels (0-3) colored by fluoroscopy
thal: Thalassemia type (0-3)
target: Presence of heart disease (1 = presence; 0 = absence)
Installation
Clone the repository
Navigate into the project directory
Install the required dependencies:

Usage
Ensure you have Python and necessary libraries installed.
Run the Jupyter notebook heart_disease_classification.ipynb to see the project code and analysis steps.
Explore different sections of the notebook:
Data exploration and preprocessing.
Training and evaluating the Decision Tree classifier.
Visualizing the Decision Tree using GraphViz.
Making predictions and evaluating model performance.
Dependencies
Python 3.x
pandas
scikit-learn
seaborn
matplotlib
pydotplus
GraphViz
