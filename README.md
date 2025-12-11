# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>
Start

Import required libraries

Import pandas for data handling.

Import linear_model from sklearn for regression.


### Step2
<br>

Use pd.read_csv("car.csv") to load the dataset into a DataFrame df.

Select input (independent) and output (dependent) variables

Set X as the features: "Volume" and "Weight".

Set Y as the target variable: "CO2".

Create a Linear Regression model

Initialize the model using regr = linear_model.LinearRegression().

### Step3
<br>
Fit the model using regr.fit(X, Y) to learn the relationship between the features and CO₂ emissions.

Display the model parameters

Print the coefficients using regr.coef_.

Print the intercept using regr.intercept_.

### Step4
<br>
Make a prediction

Predict CO₂ emission for a car with Volume = 3300 and Weight = 1300 using regr.predict([[3300, 1300]]).

### Step5
<br>
Display the predicted CO₂ emission

end the program

## Program:
```






```
## Output:

### Insert your output

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
