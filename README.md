Uber Cab Price Prediction Model

This is a machine learning model that predicts the price of an Uber ride based on several factors such as distance, time of day, and location. The model is trained on a dataset of 2 lakh examples, and uses both linear and random forest regression algorithms to make predictions.

Dataset

The dataset used for this model contains information about Uber rides taken in different cities, including the starting location, ending location, time of day, and price. The dataset was preprocessed to remove any missing or irrelevant data, and then split into training and testing sets with a 80:20 ratio.

Features

The features used in the model include:

Distance: The distance between the starting and ending location of the ride.

Pickup Time: The time of day that the ride was requested.

Day of Week: The day of the week that the ride was requested.

Pickup Location: The location where the ride was requested.

Destination: The location where the ride ended.

Model Training

Two regression algorithms were used to train the model:

Linear Regression: This algorithm models the relationship between the features and the price of the ride as a linear function.

Random Forest Regression: This algorithm uses an ensemble of decision trees to model the relationship between the features and the price of the ride.

Both algorithms were trained on the same dataset using the same features. The performance of each algorithm was evaluated using r mean squared error (MSE)

Results

The performance of the two algorithms was compared using MSE. The results are summarized below:

Algorithm	MSE	

Linear Regression	 96.9880314327274

Random Forest	23.819213228358546

The random forest algorithm outperformed the linear regression algorithm in MSE, indicating that it is a better model for predicting the price of an Uber ride.

Usage

The trained model can be used to predict the price of an Uber ride given the features mentioned above. The input features can be passed to the model, and it will return the predicted price of the ride.

The model can be used in a variety of applications, including ride-hailing apps and transportation planning.

Conclusion
In this project, we developed a machine learning model to predict the price of an Uber ride using both linear and random forest regression algorithms. The model was trained on a dataset of 2 lakh examples, and achieved good performance in terms of MSE. The results suggest that the random forest algorithm is a better model for predicting the price of an Uber ride.
