# Linear Regression with Gradient Descent

This Python script is an implementation of linear regression using gradient descent. It takes a dataset as input and finds the best-fitting linear model by iteratively adjusting the model's weights (coefficients) to minimize the sum of squared errors (SSE) between the predicted values and the actual target values.

## Prerequisites

Before running the script, make sure you have the following libraries installed:

- [NumPy]For numerical operations.
- [Pandas] For data manipulation.
- [argparse] For command-line arguments.

## Usage

- `data_file.csv`: The path to the CSV file containing your dataset. The file should have columns for features and a target variable.
- `learning_rate`: The learning rate controls the step size in gradient descent. It should be a float value (e.g., 0.01).
- `convergence_threshold`: The threshold value that determines when gradient descent should stop. It should be a small positive number (e.g., 0.0001).

## Algorithm

The script implements the following steps:

1. Read the dataset from the specified CSV file.
2. Initialize the weights (coefficients) for the linear model.
3. Perform gradient descent to find the optimal weights that minimize the SSE.
4. Output the iteration number, weights, and SSE at each iteration.
5. Stop when the SSE change is smaller than the convergence threshold.


This will load the dataset from `dataset.csv`, set the learning rate to 0.01, and use a convergence threshold of 0.0001.

The script will output the iteration number, weights, and SSE at each iteration, showing the progress of the gradient descent optimization.
