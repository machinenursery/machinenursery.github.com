---
layout: page
title: Glossary of Terms
---
{% include JB/setup %}

A glossary of terms we've come across in our travels.

* [Bias and Variance](http://bit.ly/W92qah)  
Given a function *f(x)* which we use to estimate an expected outcome *Y* over a set of inputs *X* in a training set.    
The error rate of that function is the difference between what the function thinks an input should be predicated as and what it actually is in the training set.  
The **bias is the average error** and the **variance describes the spread of those errors**.

* [Covariance matrix](http://en.wikipedia.org/wiki/Covariance_matrix)  
This is a matrix used to show the covariance between different variables where covariance describes how much the two variables change together. If as one increases the other increases then they're said to have positive covariance.

* [Cross Entropy](http://en.wikipedia.org/wiki/Cross_entropy)  
This can be used as [an alternative to squared error](http://www.cse.unsw.edu.au/~billw/cs9444/crossentropy.html) when determining the error rate of a learning algorithm. It's particularly useful when we have multiple outputs e.g. with classification problems.

* [Determinant](http://en.wikipedia.org/wiki/Determinant)  


* [Discriminant Function](http://www.unesco.org/webworld/idams/advguide/Chapt9_2.htm)  
A discriminant function is one in which we try to find coefficients to apply to variables/features with the goal of making values in the same group as close as possible and those in different groups far apart.

* [log-likelihood](http://en.wikipedia.org/wiki/Likelihood-ratio_test)  
A statistical test used to check the fit of a model for a training set of inputs. 

* [Logistic Function](http://en.wikipedia.org/wiki/Logistic_function)  
A logistic function allows us to model 'S Shaped' behaviour where initially the growth of a curve may be exponential but it eventually slows and then stops. e.g. P(t) = 1 / 1 + e^-t

* [logit function](http://en.wikipedia.org/wiki/Logit)  
The logit of a number *p* between 0 and 1 is given by the formula: logit(p) = log(p / 1-p) = log(p) - log(1-p)

* Orthogonal  
If two factors/vectors are said to be orthogonal then it means that they are uncorrelated.

* [Posterior Probability](http://en.wikipedia.org/wiki/Posterior_probability)  
This seems to be another way of referring to conditional probability. i.e. what is the probability of a certain event given that another one has happened.

* [Ridge Regression](http://tamino.wordpress.com/2011/02/12/ridge-regression/)  
This is an estimator that we use to to work out coefficients when two or more of the predictor variables are very strongly correlated. e.g. if we regress global temperature as a function of time and of the logarithm of population then we'll find that these two predictors are strongly correlated.


* [Voronoi Tesselation](http://en.wikipedia.org/wiki/Voronoi_diagram)  
A way of dividing space into a number of regions. In our context it describes the way that a classifier visually divides training data points into their respective classes.