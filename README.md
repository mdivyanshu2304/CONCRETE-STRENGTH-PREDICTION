# CONCRETE-STRENGTH-PREDICTION
# Concrete Compressive Strength Prediction using Machine Learning
Concrete is one of the most important materials in Civil Engineering. Knowing the compressive strength of concrete is very important when constructing a building or a bridge. The Compressive Strength of Concrete depends upon ingredients used in making it and their characteristics. Thus, using Machine Learning to predict the Strength could be useful in generating a combination of ingredients which result in high Strength.

This project aims to predict the compressive strength of concrete using machine learning algorithms. The dataset contains features representing the composition and age of concrete, and the target is its compressive strength (in MPa).

## Data set Description
Data is obtained from UCI Machine Learning Repository. https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength

Number of instances - 1030

Number of Attributes - 9

Attribute breakdown - 8 quantitative inputs, 1 quantitative output

Attribute information

Input
* Cement
* Blast Furnace Slag
* Fly Ash
* Water
* Superplasticizer
* Coarse Aggregate
* Fine Aggregate
* Age (in days)
  
Output

Concrete Compressive Strength (Mpa)

## Modelling and Evaluation

Multiple algorithms are used to get a better and optimised output.

Algorithms used for evaluation :

* Linear regression
* Polynomial regression
* Random Forest 

Metric - Since the target variable is a continuous variable, regression evaluation metric - RMSE (Root Mean Squared Error) and R2 Score (Coefficient of Determination) have been used.



