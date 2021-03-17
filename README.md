# Predicting-The-Income-Level-Based-On-U.S-Census-Data


## Description:

This data was extracted from the 1994 Census bureau database by Ronny Kohavi and Barry Becker (Data Mining and Visualization, Silicon Graphics). A set of reasonably clean records was extracted using the following conditions: ((AAGE>16) && (AGI>100) && (AFNLWGT>1) && (HRSWK>0)). The prediction task is to determine whether a person makes over $50K a year.


## Data Dictionary:

1. age - the age of an individual
2. workclass - a general term to represent the employment status of an individual
3. final weight - in other words, this is the number of people the census believes the entry represents
4. education - the highest level of education achieved by an individual
5. education_num - the highest level of education achieved in numerical form.
6. marital_status - marital status of an individual. Married civ spouse corresponds to a civilian spouse while Married AF
7. spouse is a spouse in the Armed Forces
8. occupation - the general type of occupation of an individual
9. relationship - represents what this individual is relative to others
10. race - descriptions of an individual’s race
11. sex - the biological sex of the individual
12. capital_gain - capital gains for an individual
13. capital_loss - capital loss for an individual
14. hours_per_week - the hours an individual has reported to work per week continuous
15. income - whether or not an individual makes more than 50,000 dollars annually (the label)


## Framing Problem:

    For now, we can categorize our Machine Learning System as:
            Supervised Learning Task- we are given labled training data
            Classification task- our model is expected to predict the income=>50k or income=<50k using given features
            
## [Dataset](https://github.com/pawaderahul/Predicting-The-Income-Level-Based-On-U.S-Census-Data/blob/main/adult.csv)
            
## [Data Preprocessing](https://github.com/pawaderahul/Predicting-The-Income-Level-Based-On-U.S-Census-Data/blob/main/DataPreprocessing.ipynb)
            
## ML Models:
1. [Decision Tree](https://github.com/pawaderahul/Predicting-The-Income-Level-Based-On-U.S-Census-Data/blob/main/DecisionTree.ipynb)
2. [K Nearest Neighbors](https://github.com/pawaderahul/Predicting-The-Income-Level-Based-On-U.S-Census-Data/blob/main/KNN.ipynb)
3. [Logistic Regression](https://github.com/pawaderahul/Predicting-The-Income-Level-Based-On-U.S-Census-Data/blob/main/LogisticRegression.ipynb)
4. [Naive Bayes](https://github.com/pawaderahul/Predicting-The-Income-Level-Based-On-U.S-Census-Data/blob/main/NaiveBayes.ipynb)
5. [Random Forest](https://github.com/pawaderahul/Predicting-The-Income-Level-Based-On-U.S-Census-Data/blob/main/RandomForest.ipynb)
6. [XGBoost](https://github.com/pawaderahul/Predicting-The-Income-Level-Based-On-U.S-Census-Data/blob/main/XGBoost.ipynb)

## Model Performance (According to r2_score value)
| Models             | Accuracy Score       | 
| ------------------ |:--------------------:|
| Decision Tree      | 0.8446               |
| K Nearest Neighbors| 0.7990               |     
| Logistic Regression| 0.8000               |
| Naive Bayes        | 0.7954               |
| Random Forest      | 0.8608               |
| XGBoost            | 0.8688               |

## Hence XGBoost model gives best performance for our data
