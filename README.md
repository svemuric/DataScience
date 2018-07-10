# DataScience
R code handy
Linear Regression
linreg=lm(mpg~ wt,data=mtcars)#to bulid the model
summary(linreg)

#to plot the linear regressio line
plot(mtcars$wt,mtcars$mpg)
abline(lm(mtcars$mpg~mtcars$wt))
