# Predicting "Match" in a Speed Dating Experiment

For this project, the objective is to predict whether the participant successfully matches with a partner (yes or no) and identify the important predictors when it comes to a match in an experiment conducted during 2002-2004. The data is from [Kaggle](https://www.kaggle.com/annavictoria/speed-dating-experiment), which includes participant information related to demographics, dating habits, lifestyles, an attribute evaluation questionnaire taken when the participants sign up, ratings for their partners during the 4 minute interactions, and each participant’s response on if they would like to match with the partner they met.

To approach the objective, we deployed a number of classification models including Simple Logistic regression, Ridge logistic regression, Neural Network, Classification Tree, Generalized Additive Models (GAM), Random Forest, Gradient Boosting Trees and Support Vector Machine. After analyzing the strengths, limitations and performances of the above models, we built another ensemble model by aggregating the prediction of best three models (Gradient Boosting Tree, Generalized Additive Models and Neural Network) in terms of predictive power.

Check out `deliverables/PA2 Final Report.pdf` for our final report.
