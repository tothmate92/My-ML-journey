# My first model

## Overview

In this project, I built a logistic regression model to predict the 10-year risk of coronary heart disease (CHD). 
The project utilizes the Framingham dataset, a renowned dataset containing 14 features that are potentially associated with the risk of developing CHD. 
The primary goal of this project is to develop a predictive model that can assist in identifying individuals at higher risk of developing CHD over a 10-year period.

## Dataset

The dataset used in this project is the Framingham dataset, which is available on Kaggle. It includes a variety of demographic, behavioral, and medical risk factors collected from the Framingham Heart Study. 
The dataset contains 14 features, including age, sex, cholesterol levels, blood pressure measurements, smoking status, and diabetes status, among others. 
The target variable is the 10-year risk of CHD, which is binary (0 or 1), indicating whether an individual developed CHD within the following 10 years.

You can find the dataset and its description on Kaggle: https://www.kaggle.com/datasets/dileep070/heart-disease-prediction-using-logistic-regression

## Methodology

1. ### Data preprocessing:

   The dataset underwent preprocessing steps such as handling missing values, encoding categorical variables, and scaling numerical features. Additionally, considering the imbalanced nature of the dataset, techniques such as oversampling (e.g., SMOTE) were applied to address class imbalance.

2. ### Model Development:
   Logistic regression, a commonly used classification algorithm, was employed to build the predictive model. Special attention was given to hyperparameter tuning and model evaluation considering the imbalanced nature of the dataset.

1. ### Model Evaluation:

   The model's performance was evaluated using various metrics, including accuracy, precision, recall, and F1-score. These metrics provide insights into different aspects of the model's performance in predicting CHD risk.



## Conclusion

Through this project, insights were gained into the challenges posed by the imbalanced nature of the dataset when developing a predictive model for CHD risk prediction. The model's performance metrics were interpreted with consideration to class imbalance, highlighting the importance of evaluating models using appropriate metrics in imbalanced datasets. Future research could explore advanced techniques for addressing class imbalance, such as ensemble methods or cost-sensitive learning, to further improve predictive accuracy and effectiveness in identifying individuals at higher risk of developing CHD.





