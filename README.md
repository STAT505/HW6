# HW6

### 1. 4 points (Based on ROS 5.2)

The logarithms of weights (in pounds) of men in the Unite States are approximately normally distributed with mean 5.13 and standard deviation of 0.17; women's log weights are approximately normally distributed with mean 4.96 and standard deviation of 0.20. Suppose 10 adults selected at random step on an elevator with a capacity of 1750 pounds. What is the probability that their total weight exceeds this limit?

Clearly state any assumptions that you make in calculating this probability.

### 2. 4 points (Based on ROS 5.4)
For the following values of n = (5, 20, 50, 100), let x = x1 + ... + xn, the sum of n independent uniform random variables. In R, create 1000 simulations of x (for each n) and plot their histogram. For each n, what is the normal approximation from the CLT (note that the variance of a uniform random variable is $\frac{1}{12}$ (b-a)^2$, where $b$ and $a$ are the upper and lower bounds of the uniform variable). Overlay the normal density on top of each histogram and comment on any differences between the histogram and curve.

### 3. 3 points

Simulate and plot synthetic data with:

- x in the range of 0 to 4 percent corresponding to the regression line with y = 30 + 10 x, with residual standard deviation of 3.9
- x in the range of 0 to 4 percent corresponding to the regression line with y = 30 + 10 x, with residual standard deviation of 10
- x in the range of 0 to 4 percent corresponding to the regression line with y = 30 + 10 x^2, with residual standard deviation of 3.9

For each plot include the best linear fit, geom_smooth(method = 'lm'), as well as the LOESS fit, geom_smooth(method = 'loess')

### 4. 4 points

For each of the scenarios in Question 3, fit a linear regression model using either `lm` or `stan_glm`. For the third scenario fit one model with `y~x` and `y~x_squared.` For each situation, summarize the model fit and discuss how the results compare with your expectations.
