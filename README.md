# Machine-Learning---AU-Dataset-Sales-Record-Prediction
This code performs time series analysis on sales data stored in an Excel file named "test.xlsx" using the Grey Model (GM) and then predicts future sales using the same model. The code makes use of various libraries such as pandas, numpy, matplotlib, statsmodels, and scikit-learn.

The code first loads the data from the Excel file into a pandas DataFrame and creates a list of product names from the column names. The code then loops through each product and splits the data into independent and dependent variables. The independent variable, Year, is normalized using MinMaxScaler. The dependent variable, sales, is also normalized using MinMaxScaler and split into training and testing sets.

The code then fits the Grey Model to the training data and uses the test data to predict future sales. It calculates the mean squared error (MSE) of the prediction and prints the MSE along with the predicted and actual sales values. The future sales are predicted from 2018 to 2030 and the results are printed. Finally, the predicted vs. actual sales are plotted using matplotlib.

# Time Series Forecasting of Sales Using Grey Model
This Python code demonstrates how to use Grey Model for time series forecasting of sales for a list of products. It reads data from an Excel file and loops through each product to generate sales predictions.

The code applies MinMaxScaler to normalize the independent variable (Year) and dependent variable (sales) before splitting the data into training and testing sets. Grey Model is then applied to the training data and predictions are made using the test data. Mean Squared Error (MSE) is calculated to evaluate the accuracy of the predictions.

The code also predicts future sales for each product from 2018 to 2030 using the trained model.

Finally, the code plots the predicted vs. actual sales for each product using matplotlib.

To run the code, ensure that you have installed the following libraries:

* pandas
* numpy
* matplotlib
* statsmodels
* scikit-learn
The data should be in an Excel file with two columns: 'Year' and 'Product 1', 'Product 2', etc.
