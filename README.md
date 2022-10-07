# Applied Machine Learning

*Homework 1*: Write a programm to estimate the parameters for an unknown polynommial using the polyfit() functionn of the numpy package.
  1. Plot the noisy data and polynomial that was found 
  2. Plot MSE versus order m, for m = 1, 2, 3, 4, 5, 6, 7, 8 respectively. Identify the best choice of m. 
  3. Change variable noise_scale to 150, 200, 400, 600, 1000 respectively, re-run the algorithm and plot the polynomials with the m found in 
      - Discuss the impact of noise scale to the accuracy of 
the returned parameters. 
  4. Change variable number_of_samples to 40, 30, 20, 10 respectively, re-run the algorithm and plot the polynomials with the m found previously. Discuss the impact of the number of samples to the accuracy of the returned parameters. 
  
*Homework 2*: Write a program to find the coefficients for a linear regression model for the dataset provided. Assume a linear model y = w_0 + w_1*x. PLot the data and implement the following methods to find the coefficients: 
  1. Normal Equation 
  2. Gradient Descent using batch and stochastic modes 
      - plot MSE vs. iteration of each mode for both training set and testing set.
      - compare batch and stochastic modes in terms of accuracy and speed of convergence 
      - plot MSE vs. learning rate (using 0.01, 0.02, 0.03, 0.04, 0.05, 0.06, 0.07, 0.08, 0.09, 0.1) and determine the best learning rate.
algorithms are implemented from scratch without the fit() function.

*Homework 3*: using the Titanic Dataset, predict survivors using Decision Tree Classifier, GridSearchCV, and Random Forest Classifier 

*Homework 4*: using a Titanic Dataset, fit a neural network with the independent variables 'pclass + sex + age + sibsp’ and dependent variable 'survived'. Check the performance of the model with out-of-sample accuracy. Used scikit-learn. 
