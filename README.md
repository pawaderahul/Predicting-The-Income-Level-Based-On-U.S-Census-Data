# Predicting-The-Income-Level-Based-On-U.S-Census-Data


## Description:

This data was extracted from the 1994 Census bureau database by Ronny Kohavi and Barry Becker (Data Mining and Visualization, Silicon Graphics). A set of reasonably clean records was extracted using the following conditions: ((AAGE>16) && (AGI>100) && (AFNLWGT>1) && (HRSWK>0)). The prediction task is to determine whether a person makes over $50K a year.


## Data Dictionary:

age - the age of an individual
workclass - a general term to represent the employment status of an individual
final weight - in other words, this is the number of people the census believes the entry represents
education - the highest level of education achieved by an individual
education_num - the highest level of education achieved in numerical form.
marital_status - marital status of an individual. Married civ spouse corresponds to a civilian spouse while Married AF
spouse is a spouse in the Armed Forces
occupation - the general type of occupation of an individual
relationship - represents what this individual is relative to others
race - descriptions of an individual’s race
sex - the biological sex of the individual
capital_gain - capital gains for an individual
capital_loss - capital loss for an individual
hours_per_week - the hours an individual has reported to work per week continuous
income - whether or not an individual makes more than 50,000 dollars annually (the label)


## Framing Problem:

    For now, we can categorize our Machine Learning System as:
            Supervised Learning Task- we are given labled training data
            Classification task- our model is expected to predict the income=>50k or income=<50k using given features
            
## [Dataset](https://github.com/pawaderahul/Predicting-The-Income-Level-Based-On-U.S-Census-Data/blob/main/adult.csv)
            
## ML Models:
1. [Data Preprocessing](https://github.com/pawaderahul/Predicting-The-Income-Level-Based-On-U.S-Census-Data/blob/main/DataPreprocessing.ipynb)
2. [Decision Tree](https://github.com/pawaderahul/Predicting-The-Income-Level-Based-On-U.S-Census-Data/blob/main/DecisionTree.ipynb)
3. [K Nearest Neighbors](https://github.com/pawaderahul/Predicting-The-Income-Level-Based-On-U.S-Census-Data/blob/main/KNN.ipynb)
4. [Logistic Regression](https://github.com/pawaderahul/Predicting-The-Income-Level-Based-On-U.S-Census-Data/blob/main/LogisticRegression.ipynb)
5. [Naive Bayes](https://github.com/pawaderahul/Predicting-The-Income-Level-Based-On-U.S-Census-Data/blob/main/NaiveBayes.ipynb)
6. [Random Forest](https://github.com/pawaderahul/Predicting-The-Income-Level-Based-On-U.S-Census-Data/blob/main/RandomForest.ipynb)
7. [XGBoost](https://github.com/pawaderahul/Predicting-The-Income-Level-Based-On-U.S-Census-Data/blob/main/XGBoost.ipynb)

## Model Performance
| Models             | Accuracy Score       | 
| ------------------ |:--------------------:|
| Decision Tree      | 0.8446184553968985   |
| K Nearest Neighbors| 0.7990173499155535   |     
| Logistic Regression| 0.8000921234454169   |
| Naive Bayes        | 0.7954859511745739   |
| Random Forest      | 0.8608935974205435   |
| XGBoost            | 0.8688776293566712   |

## Hence XGBoost model gives best performance for our data
