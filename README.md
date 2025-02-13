If the file will not render on GitHub, go to https://nbviewer.org/ and paste in the link https://github.com/gibsongGH/Titanic/blob/main/titanic-tutorial-gg.ipynb

Objective: Predict survivors of Titanic sinking

Methodolgy: Use several ML models from Udemy class to improve accuracy of survivor predictions on test data and submit best.
Replaced categorical columns, male/female as binary, and dummy variables for Pclass, Embarked, and Cabin letter.
Additional test and train data with Age and Fare scaled for models that perform better with scaled.

Discussion: Titanic training Random Forest score was 77.5% using only Pclass, Sex, SibSp and Parch

Naive Bays unscaled was 75.8%
Decision Tree unscaled 78.1%
Linear Regression either 80.1%
KNN scaled 81.104%
Random Forest unscaled 81.108%
SVC scaled 82.2%
XGBoost either 82.6%
CatBoost either 82.7%
