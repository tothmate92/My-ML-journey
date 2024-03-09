## Introduction

In this project, we will constructing a decision tree classifier using the Drug 200 dataset. The primary objective is to develop a model capable of accurately predicting the optimal drug type for patients based on various attributes.

## Dataset

The Drug 200 dataset, available on Kaggle, is our focus. It contains basic information about patients and the drugs they've been prescribed. We have five different drug types labeled as A, B, C, X, and Y.

Each entry in the dataset includes details like age, sex, blood pressure, cholesterol levels, and serum concentrations of sodium and potassium. The main thing we're trying to predict is which drug type would be most effective for a particular patient based on these characteristics.

You can access the dataset on Kaggle via the following link: https://www.kaggle.com/datasets/pablomgomez21/drugs-a-b-c-x-y-for-decision-trees/data

## Exploratory Data Analysis

The knowledge gain from this part was the **Univariate** and **Bivariate** analysis. I studied each distribution of the individual categoricals, and then the relationships between the target and the categoricals.

## Data preprocessing

I noticed, that the Na_to_K feature, which is the sodium to potassium ratio in blood, is skewed. A little bit unsymmetric. So I used log-transformation on it.

The target variable if also skewed, drug-Y occurs more than the other drugs, so to address this issue, I used SMOTE, which is an oversampling in the minority class. This ensures the correct predictions.

