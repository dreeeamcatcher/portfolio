# [Project 1: Data Science Heart Disease Classifier](https://github.com/dreeeamcatcher/heart_disease_classification)

For this example project I built a heart disease classifier to identify whether or not patients have heart disease, given their clinical parameters. The real project could be useful for doctors to determine the risk of the presence of the disease by conducting a preliminary examination of the patient. They could use it like simple web-app, where the results of the patient's examination will be filled.

I was able to get the model to predict the heart disease with 84.5% accuracy after minimal tuning with `RandomSearchCV` and `GridSearchCV`. It is using only 303 samples in our dataset. To get these results I used **Logistick Regression**, **KNN** and **Random Forest** models.

![cv_scores](/images/cv_scores.png)



# [Project 2: Data Science Bulldozers Sale Price Prediction](https://github.com/dreeeamcatcher/bulldozers_price_prediction)

This project was based on the [Kaggle competition](https://www.kaggle.com/c/bluebook-for-bulldozers/overview). The goal of the contest was to predict the sale price of a particular piece of heavy equiment at auction based on it's usage, equipment type, and configuaration. And I tried to use it as a real case example. 

The evaluation metric for this competition was the RMSLE (root mean squared log error) between the actual and predicted auction prices. So my goal was to built machine learning model which minimises RMSLE.

During this project I performed: 
* EDA
* Filling missing values
* Data transformation
* Tuning hyperparameters
* Calculating feature importance

![features_importance](/images/feature_importance.png)
