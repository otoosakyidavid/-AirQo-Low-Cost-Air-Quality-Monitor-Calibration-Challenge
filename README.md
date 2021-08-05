# AirQo-Low-Cost-Air-Quality-Monitor-Calibration-Challenge

_This model was trained for the above named challenge on Zindi.africa_

Over the past few years AirQo has built up a network of over 50 low cost air quality monitoring devices in Kampala and a further 50 across Uganda. We have designed, refined and improved the devices over time and we think that they are awesome. But low cost devices are only indicative, they are not as accurate as ‘Reference monitors’ (although they only cost 1% of the price) and so to increase the validity of our work we need to calibrate our low cost monitors against the reference monitors to ‘power up’ our results and bring them as close as we can to international reference standards.

We have three locations: Makerere, Nakawa and US Embassy. Each contains a reference monitor collocated with a low cost monitor to allow a comparison over many months that can be used to train and test the model. Some supplementary and metadata has also been included to help things along

# Model Objective
The objective of this challenge is to develop a model that will take low cost device data and other supplementary data and transform it as accurately as possible to the reference value.

This model will allow Airqo to ‘power up’ the accuracy of our measured results so they can be shared with the world as reference grade to ensure accurate insights are provided and decisions are made by citizens, government and industry that reflect the true air quality values.

# Evaluation Metric
Root Mean Squared Error

# Best Model and Ranking
In the course of the competition, my selected solution ranked **44 out of 161** on the final leaderboard with a score **10.6215669874976**

# Approached used
A catboost model was trained and the selected feature of this model was trained from using lgbm

# Best Score model
In my private leaderboard, my overall best score (which I didn't select) was **10.5388849970377**, obtained with
`CatBoostRegressor(n_estimator=2000)`
