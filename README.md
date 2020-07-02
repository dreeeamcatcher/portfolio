# Vladyslav Fesenko Data Science portfolio

# [Project 1: Data Science Heart Disease Classifier](https://github.com/dreeeamcatcher/heart_disease_classification)

For this example project I built a heart disease classifier to identify whether or not patients have heart disease, given their clinical parameters. The real project could be useful for doctors to determine the risk of the presence of the disease by conducting a preliminary examination of the patient. They could use it like simple web-app, where the results of the patient's examination will be filled.

I was able to get the model to predict the heart disease with 84.5% accuracy after minimal tuning with `RandomSearchCV` and `GridSearchCV`. It is using only 303 samples in our dataset. To get these results I used **Logistick Regression**, **KNN** and **Random Forest** models.
