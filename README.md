**Titanic Analysis Using Chi-Square and Logistic Regression**
**Chi-Square Test**
In the Titanic dataset, the Chi-Square test can be applied to examine the association between categorical variables such as passenger class (Pclass), sex (Sex), and port of embarkation (Embarked) with survival (Survived).

Hypotheses for Chi-Square Test:

Null Hypothesis (H0): There is no association between the categorical variable and survival.
Alternative Hypothesis (H1): There is an association between the categorical variable and survival.
Variables Considered:

Pclass: Passenger class (1st, 2nd, 3rd)
Sex: Gender of the passenger (male, female)
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Steps:
Create a contingency table for each pair of variables (e.g., Pclass and Survived, Sex and Survived, Embarked and Survived).
Calculate the Chi-Square statistic and p-value to determine if the observed distribution differs significantly from the expected distribution.


**Logistic Regression**
Logistic regression is used to predict the probability of survival based on several input features. It models the relationship between one dependent binary variable (Survived) and one or more independent variables.

Variables Considered:
Input Variables (Predictors):
Pclass (Passenger class)
Sex (Gender)
Embarked (Port of embarkation)
SibSp (Number of siblings/spouses aboard the Titanic)
Parch (Number of parents/children aboard the Titanic)
Output Variable (Response):
Survived (0 = No, 1 = Yes)

Steps:
Encode categorical variables (Pclass, Sex, and Embarked) into numerical values.
Split the data into training and testing sets.
Fit a logistic regression model to the training data.
Evaluate the model using the testing data by checking metrics like accuracy, precision, recall, and the area under the ROC curve (AUC).
Logistic Regression Model Interpretation:

Coefficients: Determine the impact of each predictor on the likelihood of survival.
Odds Ratios: Explain the change in odds of survival for a one-unit change in the predictor variable.
Significance: Identify which predictors significantly affect the probability of survival.
