# Binary Classification with a Software Defects Dataset
## Aim
To predict defects in C programs given various various attributes about the code.
## Link to the competition
[\<click!\>](https://www.kaggle.com/competitions/playground-series-s3e23)
## Score
AUC = 0.793
## Approach
    1. evaluate the basic models
    2. create the ensembles of best-performing basic models (three models in one)
    3. evaluate such ensembles and find out the one that performs best
## Used techniques
### Libraries
    1. pandas
    2. numpy
    3. itertools
    4. matplotlib
    5. seaborn
    6. sklearn
    7. xgboost
    8. lightgbm
    9. catboost
### Preprocessing
    1. EDA
### Learning
    1. Logistic Regression
    2. Logistic Regression with Kernel Approximation
    3. Ridge Regression
    4. Random Forest Classifier
    5. Extra Trees Classifier
    6. HistGBM Classifier
    7. XGBM Classifier
    8. AdaBoost Classifier
    9. LightGBM Classifier
    10. CatBoost Classifier
    11. kNN Classifier
    12. Ensembles
    13. Cross-Validation
