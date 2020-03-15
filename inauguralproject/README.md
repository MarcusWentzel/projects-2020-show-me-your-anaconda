##### Inauguralproject #####

# Results are produced by running the notebook "inauguralproject.ipynb". The other notebook "correct q1" is to not to be regarded.

##### The structure of the notebook is as follows #####

* First, packages etc. is imported.

* Secondly, the Labor-Supply-Problem is solved constructing an optimizer using optmize.minimize_scalar() for a single wage value.

* Thirdly, we use the optimizer to iterate over 10.000 wages in the interval [0.5:1.5] and plotting the resulting labor and consumption as a function of wages.

* Fourthly, the total tax revenue is calculated given our wage function, which is graphically reported.

* Next, we redefine the Frisch-Elasticy and once more iterate over the wage function to obtain optimal labor and consumption for which we can calculate the tax revenue.

* Lastly, we redefine oour functions from question 1 such that each parameter is a vector corresponding to the N wage observations. Thus, allowing us to use the optimize.minimize() and do multivariate optimization.