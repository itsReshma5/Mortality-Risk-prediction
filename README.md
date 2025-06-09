# 🩺 Heart Disease Prediction (Mortality Risk)

A machine learning project to predict the presence of heart disease using clinical data and both classical and neural network models.

## What it does  
Classifies whether a patient has heart disease based on features like age, blood pressure, cholesterol, and exercise-related metrics. Includes visual EDA, normalization, and performance evaluation.

## 📊 Workflow  
1. Data Preprocessing  
   - Handled missing values and scaled features using StandardScaler  
   - Converted features into numerical format  

2. Exploratory Data Analysis  
   - Count plots by outcome  
   - Distribution of clinical features using boxen plots and swarm plots  
   - Correlation analysis and scatter plots

3. Model Training  
   - Support Vector Machine (SVM) using scikit-learn  
   - Artificial Neural Network (ANN) using Keras (with dropout & early stopping)  
   - Compared model accuracy, precision, recall, and F1 score

## Dataset  
- Clinical dataset (heartfailurepredn.csv)  
- Features include: Age, RestingBP, Cholesterol, FastingBS, MaxHR, Oldpeak, etc.  
- Target: HeartDisease (0 = No, 1 = Yes)

## Results  
- SVM: Balanced accuracy with fast inference  
- ANN: Tuned with dropout layers, early stopping, and 2 hidden layers  
- Visual performance metrics shown in notebook

## 🛠 Tech Stack  
Python · pandas · NumPy · scikit-learn · seaborn · matplotlib · Keras · TensorFlow · Google Colab

