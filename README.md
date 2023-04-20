# Co2_emissions-_MachineLearningModels_In_Python
Implementing Machine Learning Models on Co2 emissions dataset  In Python

The dataset is obtained from the Government of Canada, and it contains model-specific and detailed fuel consumption ratings and estimated carbon dioxide
emissions for new light-duty vehicles for retail sale in Canada from 2012 to 2022. The dataset has 11587 rows and 15 columns, each row resembles a list 
of features, fuel consumption, CO2 emissions and ratings of one specific vehicle. Of the 15 columns, 5 are categorical variables (make, model, vehicle class, 
transmission, and fuel type), and others are all in numeric form, including model year, engine size, cylinders, fuel consumption on different road conditions, 
CO2 emissions in gram/kilometer, CO2 rating and smog rating of the vehicle.

The goal of the project is to study how each light-duty vehicle contributes to environmental CO2 pollution and to predict the potential CO2 rating of
the vehicle by performing different types of classification models. The car which emits least CO2 gets a rating of 10, in other words it is the most
environment friendly car. A car with rating 1 emits the most CO2 and it pollutes the most. 
I build multiple models on the dataset Logistic Regression, Decision Tree, Random Forest, KNN, Gradient Boost and Neural Network. For all these models 
I analyzed the features which impacted these models the most.
