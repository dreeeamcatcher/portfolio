# [Project 1: Supervised Learning - Heart Disease Classifier](https://github.com/dreeeamcatcher/heart_disease_classification)

For this example project I built a heart disease classifier to identify whether or not patients have heart disease, given their clinical parameters. The real project could be useful for doctors to determine the risk of the presence of the disease by conducting a preliminary examination of the patient. They could use it like simple web application, where they will fill in the information from the examination of patients and get the probability of occurrence / presence of the disease.

I was able to get the model to predict the heart disease with 84.5% accuracy after tuning with `RandomSearchCV` and `GridSearchCV`. And that's using only 303 samples in our dataset. To get these results I used **Logistic Regression**, **KNN** and **Random Forest** models.

![cv_scores](/images/cv_scores.png)



# [Project 2: Supervised Learning - Bulldozers Sale Price Prediction](https://github.com/dreeeamcatcher/bulldozers_price_prediction)

This project was based on the [Kaggle competition](https://www.kaggle.com/c/bluebook-for-bulldozers/overview). The goal of the contest was to predict the sale price of a particular piece of heavy equiment at auction based on it's usage, equipment type, and configuaration. I tried to use it as a real case example. 

The evaluation metric for this competition was the RMSLE (root mean squared log error) between the actual and predicted auction prices. So my goal was to build machine learning model with the least RMSLE.

During this project, I completed the following steps: 
* EDA
* Filling missing values
* Data transformation
* Tuning hyperparameters
* Calculating feature importance

![features_importance](/images/feature_importance.png)



# [Project 3: Deep Learning - Dog Breed Identification](https://github.com/dreeeamcatcher/dog_breed_identification)

This project was based on the [Kaggle competition](https://www.kaggle.com/c/dog-breed-identification). The main idea was to build Neural Network using TensorFlow 2.0 and TensorFlow Hub to predict dog breed given an image of a dog.

I used **MobiNetV2** model from TensorFlow Hub as a base and modified it to predict 120 different dog breeds.

One of the experimentation steps:

![experimental_prediction](/images/border_collie.png)

After training the model I was able to get right predicts for 4 out of 5 my own images.
