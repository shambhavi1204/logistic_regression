# logistic_regression
Regression deals with a predictive modelling technique. It shows the relation between independent also known as predictive variable or dependent or target value.
Logistic regression comes int ouse when output is of categorical format such as yes/no , 1 or 0,true or false, high or low.
As in linear regression we get output values over a large range but for the categorical output it should be between 1 and 0, hence the linear regression curve is to be clipped between 1 and o which is performed using logistic regression , for this we use a sigmoid function.


concept of threshold:
This is used to decide whether the output value(betwwen o and 1) rounds off to give the output as 0(low) or 1(high).
The output values between threshold value(0.5) and 1 is rounded to 1 and the value below threshold and is rounded to 0.

concept of log likelihood:
Using the concept of linear regression:


putting the above value in sigmoid equation:


Now , by taking inspiration from Bernaulli's traits, we find the log likelyhood function and differentiating it to find the gradient ascent update equation. Hence the likelihood is defined as :

![first equation](https://latex.codecogs.com/gif.latex?l%28%5Cbeta%20%29%20%3D%20%5Cprod%20%28h%28x_%7B%5Cbeta%20%7D%29%29%5E%7By%7D%281%20-%20h%28x_%7Bb%7D%29%29%5E%7B1-y%7D)
