# Determining-Strength-of-Cement-
A. Build a baseline model. Use the Keras library to build a neural network with the following:
One hidden layer of 10 nodes, and a ReLU activation function
Use the adam optimizer and the mean squared error as the loss function.
Randomly split the data into a training and test sets by holding 30% of the data for testing. You can use the train_test_splithelper function from Scikit-learn.
Train the model on the training data using 50 epochs.
Evaluate the model on the test data and compute the mean squared error between the predicted concrete strength and the actual concrete strength. You can use the mean_squared_error function from Scikit-learn.
Repeat steps 1 - 3, 50 times, i.e., create a list of 50 mean squared errors.
Report the mean and the standard deviation of the mean squared errors.

B. Normalize the data. 
Train and test the model at the same time using the fit-method. We will leave out 30% of the data for validation and we will train the model for 50 epochs. And use predictors_norm instead of predictors.

C. Increase the Number of epochs 
Increasing the number of spochs from 50 to 100

D. Increase the number of hidden layers
Building model with 3 hidden layers
