# Titanic-Survival-Prediction
This project predicts survival on the Titanic using machine learning models. The goal is to evaluate multiple models' performances based on accuracy and feature engineering techniques.
	**Approach**
Data Preprocessing: Handled missing values in Age and Embarked. Encoded categorical features (Sex and Embarked) and dropped less informative columns (Name, Ticket, Cabin).
Feature Selection: Selected key features such as Pclass, Sex, SibSp, Parch, Fare, Embarked, and Age.
	**Models Used:**
Logistic Regression
Random Forest
Decision Tree
Support Vector Classifier (SVC)
	**Evaluation Metrics:** 
Used accuracy_score, mean_squared_error, and classification_report.
	**Challenges**
Handling missing data in Age and Embarked.
Selecting appropriate features while avoiding overfitting.
Optimizing hyperparameters for models like Random Forest and Decision Tree.
