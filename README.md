# 1-dimensional Optimization Problem
## Introduction
We have captured sensor data with Arduino as can be seen in *Fig. 1*.

<img src="figure/input target data.png" alt="input target data" height="300"/></br>
*Figure 1:* Data captured with an Arduino-sensor pair.

We would like to develop a model for the data shown in *Fig. 1*. If we cannot predict the (mathematical) structure of the model by examining the data, it can be referred to as a **black-box** model. No matter what the model is, we are going to formulate this **model fitting** problem with Least Squares method and Gradient-Descent algorithm here. The approach for building a model for the captured daha is illustrated in *Fig. 2*.

<img src="figure/general optimization model.jpg" alt="general optimization model" height="180"/></br>
*Figure 2:* Black-box model for the data captured in *Fig. 1*.

If we look at the data in *Fig. 1* carefully, we see that the points can be represented with a line (in the form of y = ax + b). If we further examine the axes and data together, we see that the line actually passes through 0, which simplifies the line equation (i.e., our model) to y = ax. Eventually, *Fig. 2* is updated to *Fig. 3*.

<img src="figure/anticipated optimization model.jpg" alt="anticipated optimization model" height="180"/></br>
*Figure 3:* Anticipated model for the data captured in *Fig. 1*.
## Least Squares
Now, let's formulate this problem with a technique called **Least Squares**. If we minimize the error for each data point, then we obtain the correct parameters and the model. In least squares, because of the input-target data size (multi-dimensional), we minimize the sum of errors in order to optimize the adjustable (sought) parameters. Unfortunately, this yields to an undesired result in the case of errors cancelling each other and sometimes despite having zero total error, obtained model is irrelevant. To avoid this issue, instead of summing the errors, we sum the *squared* errors, which actually names the technique of **Least Squares**. If we are able to minimize the sum of squared errors, then we achieve the **least squares** literally :thumbsup:
## Gradient-Descent
<img src="figure/loss function.png" alt="loss function" height="300"/></br>
*Figure 2:* Loss function.

<img src="figure/search for a.png" alt="search for parameter a" height="300"/></br>
*Figure 3:* Searching for the optimal value of parameter a.

<img src="figure/line fit.png" alt="line fit with gradient descent" height="300"/></br>
*Figure 4:* Line fit with gradient descent.
## References 
