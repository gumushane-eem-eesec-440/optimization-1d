# 1-dimensional Optimization Problem
## Introduction
We have captured sensor data with Arduino as can be seen in *Fig. 1*.

<img src="figure/input target data.png" alt="input target data" height="300"/></br>
*Figure 1:* Input target data.

We would like to develope a model for the data shown above. The most general model is called a **black-box** model.

<img src="figure/general optimization model.jpg" alt="general optimization model" height="180"/></br>
*Figure 2:* Black-box model for the data captured in *Fig. 1*.

If we look at the data carefully, we see that the points can be represented with a line in the form of y = ax + b. If we further examine the axes and data together, we see that the line actually passes through 0, which simplifies the line equation (i.e., our model) to y = ax. Eventually, *Fig. 2* is updated to *Fig. 3*.

<img src="figure/anticipated optimization model.jpg" alt="anticipated optimization model" height="180"/></br>
*Figure 3:* Anticipated model for the data captured in *Fig. 1*.

## Least Squares

## Gradient-Descent
<img src="figure/loss function.png" alt="loss function" height="300"/></br>
*Figure 2:* Loss function.

<img src="figure/search for a.png" alt="search for parameter a" height="300"/></br>
*Figure 3:* Searching for the optimal value of parameter a.

<img src="figure/line fit.png" alt="line fit with gradient descent" height="300"/></br>
*Figure 4:* Line fit with gradient descent.
## References 
