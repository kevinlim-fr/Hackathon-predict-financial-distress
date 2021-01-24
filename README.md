# Hackathon-Predict-Financial-Distress
This is a Machine Learning Hackathon project made in 3 hours.

## Dataset Presentation
Hackathon Machine Learning - https://www.kaggle.com/c/hackathon-machine-learning-5435432567543354215678/overview/description
The goal of the dataset analysis is to analyse a set information from somebody and predict if he will experience financial distress in the next two years.

## Classification problem
The dataset consists of 10 features and 1 target which is SeriousDlqin2yrs.

### Classification algorithms
We mesured the performance of the following algorithms: 
- Logistic Regression
- Classificaiton Tree
- Random Forest - Bagging
- Linear Discriminant Analysis

The Linear Discriminant Analysis has the best accuracy with: 93,29%. 

## Impovements
- We can fix the dataset unbalance by downsampling the entries.
- We can improve our research by making hyperparameters tuning for our algorithms
- We can improve our model by looking at more mesures like the f-score, precision and recall beucause our dataset is unbalanced.
