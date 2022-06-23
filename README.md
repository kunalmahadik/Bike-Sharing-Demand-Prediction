# Bike Sharing Demand Prediction

![download (2)](https://user-images.githubusercontent.com/101682011/175278867-47978624-8b9b-4661-a2ea-74acf5942b09.jpg)


## 1. Business Problem

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

## 2. Solution Strategy

Step 01: Data Description: Use statistics metrics to identify data distributions.

Step 02: Feature Engineering: Derive new attributes based on the original variables to better describe the phenomenon that will be modeled.

Step 03: Exploratory Data Analysis: Explore the data to find insights and better understand the impact of variables on model learning.

Step 04: Feature Selection: Selection of the most significant attributes for training the model.

Step 05: Machine Learning Modelling: Machine Learning model training.

Step 06: Hyperparameter Fine Tunning: hoose the best values for each of the parameters of the model selected from the previous step.

Step 07: Convert Model Performance to Business Values: Convert the performance of the Machine Learning model into a business result.

## 3. Top 3 Data insights

The demand for rental bikes is highest in the month of June and decreases gradually till December.

Temperature is positively correlated with the people using bikes. The maximum is between 20 °C and 30 °C.

The demand for bike increases throughout the day, maximum at around 6 pm.

## 4. Machine learning models implemented

Linear Regression, Lasso Regression, Ridge Regression, Elastic Net Regression, Decision Tree, Random Forest, Gradient Boost.

## 5. Model performance comparision

![image](https://user-images.githubusercontent.com/101682011/175279883-86605833-21da-44e4-aab2-2f79b64d7d05.png)


## 6. Conclusion

Both "Random forest regression" and "Gradient Boosting regression(gridsearch cv) has highest R2 score.

Performance on "Decision Tree" algorithm is comparitively less with an R2 score of 68%.

Almost all algorithms performed really well on both training dataset and testing dataset so we can say that varience is less and no issues of overfittings are present.

