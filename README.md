# Bicycle Sharing Prediction Model

<img src="https://github.com/dkalenov/Bicycle-Sharing-Prediction-Models/blob/main/assets/bike_rental_shop_in_Korea_.png" alt="Bike rental service in South Korea" width="500" height="250">

## Project objectives

Develop bicycle-sharing prediction models

## Tasks
- Data processing: Check for data anomalies, and handle missing values, incorrect data types, and outliers.
- Prepare data for model building: Encode categorical features, and scale data.
- Conduct Exploratory Data Analysis (EDA): Analyze distributions and correlations.
- Select the most important features.
- Build models to predict daily demand for bicycle sharing service using Scikit-learn, hyperparameter optimization algorithms (HyperOpt), and implement pipelines to streamline workflow and automate repetitive tasks.
- Achieve an accuracy rate of 90% on test data.

## Conclusion

The final model for predicting bicycle demand is based on Gradient Boosting. The 'adjusted R2' metric of the test data is 0.898. To select the hyperparameters of the model, the HoperOpt method was used; on these data, the model reaches a ceiling of  'adjusted R2' metrics, so in the following steps: try to train the neural network for more accurate predictions.

## Further development

Train a neural network to predict demand for bicycles
## Skills and tools 

* Data preprocessing
* EDA
* Python
* Pandas
* Matplotlib
* Scikit-learn
* HyperOpt
  
## Project status
- [x] Prediction Model Completed
- [ ] Deep Learning Model 
