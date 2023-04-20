# Auto-Price-Insights
Auto Price Insights is a machine learning-based car price prediction tool that utilizes various data points and algorithms to estimate the value of a car. By analyzing factors such as the car's make and model, year, mileage, condition, and other relevant data, AutoValuate provides users with an accurate estimate of the car's market value.
This project is an implementation of the Random Forest Algorithm 
to predict car prices based on various features.

Dataset
The dataset used in this project is sourced from Kaggle. 
It consists of car specifications such as make, model, year, engine type, fuel type, etc.
and the corresponding prices. The dataset has 205 observations and 26 columns.

Requirements
The following libraries are required to run the code:

Pandas
NumPy
datatime
seaborn
Scikit-learn
Installation

To install the required libraries, run the following command:
## pip install pandas numpy scikit-learn ##


Algorithm

The Random Forest Algorithm is an ensemble learning technique that 
combines multiple decision trees to improve the accuracy and reduce the variance of the model. 
In this project, we train a Random Forest Regressor to predict the car prices. 
The hyperparameters of the model are optimized using Grid Search Cross-Validation.
