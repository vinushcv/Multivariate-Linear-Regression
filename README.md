# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>

### Step2
<br>

### Step3
<br>

### Step4
<br>

### Step5
<br>

## Program:
```python
import pandas as pd
from sklearn import linear_model
data=pd.read_csv("cars.csv")
x=data[["Weight","Volume"]]
y=data["CO2"]
regr=linear_model.LinearRegression()
regr.fit(x,y)
print("coefficients: ",regr.coef_)
print("intercept:",regr.intercept_)
predictco2=regr.predict([[3300,1300]])
print("prediction co2 for the corresponding weight and volume",predictco2)



```
## Output:
![output](/linear%20regression.png)

### Insert your output

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.