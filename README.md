### Title: Gradient Descent for Simple Linear Regression

Description:
This Python script demonstrates the implementation of gradient descent for a simple linear regression model. The example uses randomly generated input data (x1, x2) and corresponding output labels (y). The goal is to optimize the model parameters (weights, bias) to minimize the mean squared error.

Key Features:

Random Initialization: The script initializes the weights (w1, w2) and bias (b) with random values to start the optimization process.

Forward Pass: The forward_pass function computes the predicted output (y_hat) and the total error based on the mean squared error formula.

Weight Update: The weight_update function calculates the gradients with respect to the parameters (weights and bias) and updates them using the gradient descent algorithm.

Learning Rate Decay: The learning rate (lr) decreases by a factor of 10 after each cycle, demonstrating the concept of learning rate decay.

Early Stopping: The script implements early stopping when the total error falls below a threshold (20 in this case), showcasing the use of a stopping criterion in training.

Model Orchestration: The main loop orchestrates the training process, iterating through cycles and updating weights until the early stopping condition is met or the specified number of cycles is reached.

Error Plotting: The script utilizes Matplotlib to plot the cost (Sum of Squared Errors) at each iteration, providing visual insight into the convergence of the optimization process.

