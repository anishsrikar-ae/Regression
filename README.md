What is Linear Regression?

- It is fitting a line to the data so as to minimize the loss (the mean squared distance in this case)
- The Line describes the data and assumes a linear relationship (Low Variance and High Bias) which maybe be helpful depending on the data

What is Logistic Regression?

- Unlike linear regression a straight line may not be suitable for data related to likelihood as the data may include negative values as well as values higher than one. But, probability can neither be negative nor above one
- so, we fit this data using a function in this case called the sigmoid which makes sure that the data remains within the limits >=0 and <=1


In this repository, all algorithms have been implemented using numpy and pandas and it also includes a sci kit learn version

This repo is made for the sole reason of learning the Basics of regression algorithms



Sources used for learning:

- StatQuest By JoshStarmer
- Introduction to Statistical Learning (ISLP)