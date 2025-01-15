Key Functions:
load_data(file_path):

Loads the CSV file into a pandas DataFrame.
train_model(data):

Splits the data into independent (X) and dependent (y) variables.
Splits the data into training and testing sets using train_test_split from scikit-learn.
Initializes a linear regression model (LinearRegression()).
Trains the model using the training set (model.fit()).
Makes predictions on the test set.
Evaluates the model using Mean Squared Error (MSE) and R-squared, and prints these metrics.
Ensure your data file is available: The file_path argument in the load_data function should point to the CSV file containing the dataset (business_linear_regression_dataset.csv).

Call the functions in your main script: Create a script to call these functions, load the data, train the model, and visualize the results. This script could look like:
