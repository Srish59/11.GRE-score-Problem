# 11.GRE-score-Problem
Import data from web storage and To perform Logistic Regression to compute relation  between variables that are affecting admission of student in a instance based on his/her GRE  score, GPA obtained by the student, and also To check model is fit or not.
Aim: To import data from web storage and To perform Logistic Regression to compute relation between variables that are affecting admission of student in a instance based on his/her GRE score, GPA obtained by the student, and also To check model is fit or not.
Requirements: Sample data set , Python Software.
Procedure:
In this program, we start by loading the dataset from the provided URL using `pd.read_csv`. Then, we rename the columns for convenience. Next, we preprocess the data by converting the "Rank" variable to a categorical variable using `as type ("category"). We create dummy variables for the "Rank" variable using `pd.get_dummies` and drop the first dummy column to avoid multicollinearity issues. We then concatenate the original data frame with the dummy variables. The independent variables (GRE, GPA, and rank dummies) are stored in the `X` data frame, and the dependent variable (admission) is stored in the `y` series. We perform logistic regression using 'sm.Logit' and obtain the result using the `fit` method. We print the summary of the logistic regression model using `result_Summary ()`. Finally, we check the model's fit by predicting the admission probabilities for the same dataset. We round the predictions to 0 or 1, and calculate the accuracy by comparing the predicted classes with the actual admission values.
Result: Data from web storage is imported and Logistic Regression to compute relation between variables that are affecting admission of student in a instance based on his/her GRE score, GPA obtained by the student has been performed, and also the model is checked whether it is fit or not.
