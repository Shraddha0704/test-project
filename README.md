# Bike-Sharing-Demand-Prediction
In this project, we train a model to predict the number of bike rentals at any hour of the year given the weather conditions. The data set obtained contained the historical bike usage pattern with weather data spanning two years.

We first build several individual regression models such as Linear, Ridge, Random Forest, Gradient Boost and Adaboost. We then use 'Stacking' approach where the predictions from these level 1 individual models are used as meta-features to build a second level model (Linear Regressor, Random Forest and Gradient Boost) to further enhance the predicting capabilities.
