# Linear Regression :-

In statistics, linear regression is a linear approach to modelling the relationship between a dependent variable and one or more independent variables. It is both a statistical algorithm and a machine learning algorithm.

When there is a single input variable (x), the method is referred to as *simple linear regression*. When there are multiple input variables, literature from statistics often refers to the method as *multiple linear regression*.

**Simple linear regression** :
1 dependent variable (interval or ratio), 1 independent variable (interval or ratio or dichotomous).

**Multiple linear regression** :
1 dependent variable (interval or ratio) , 2+ independent variables (interval or ratio or dichotomous).

**Logistic regression** :
1 dependent variable (dichotomous), 2+ independent variable(s) (interval or ratio or dichotomous).

**Note-** Ordinary Least Squares and Gradient Descent are two common. 

- Four techniques to prepare a linear regression mode :-
1. Simple Linear Regression
  > With *simple linear regression* when we have a single input, we can use statistics to estimate the coefficients.
  > This requires that you calculate statistical properties from the data such as **means, standard deviations, correlations and covariance**. All of the data must be available to     traverse and calculate statistics.
2. Ordinary Least Squares
  >  Used when we have more then one input.
  >  Given a regression line through the data we calculate the distance from each data point to the regression line, square it, and sum all of the squared errors together. This is      the least squares seeks to minimize.

3. Gradient Descent
   > ![image](http://rasbt.github.io/mlxtend/user_guide/general_concepts/gradient-optimization_files/ball.png)
