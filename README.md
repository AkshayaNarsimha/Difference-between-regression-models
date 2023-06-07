# Difference-between-regression-models
Linear Regression Model:
In the code after giving the dataset we implement the Linear Regression model using sklearn. It
is a free python machine learning library. With the help of matplotlib we create scatter plots for
our dataset.
And in the next cell we imported the mean squared error from scikit learn metrics library. In the
scikit learn metrics it includes the library SVM, random forests, gradient boosting, k-means, and
DBSCAN as classification, regression, and clustering techniques. As we plotted the graph using
the matplotlib the result is obtained.
The mean square error is obtained as 0.01 with the help of the mean_square_error function
from sklearn library.

Polynomial Regression Model:
In our python code we used sklearn.preprocessing to implement the polynomial features. To fit
our Linear regression data and polynomial features with the degree 2 we used the
make_pipeline library.
After fitting the data, we used the matplotlib to scatter plots and get a plot graph.
Later we calculated the mean squared error of the dataset using the polynomial regression with
the help of mean_square_error library from sklearn library. The mean squared error obtained is
0.00

3-Layer Neural Network:
With our dataset we splitted the data as train data as 80% and test data as 20% with the help of
the train_test_split using the sklearn library. We have normalized the x data using the
StandardScaler. We imported the keras from tensorflow. We created a 3 layered neural network
with the activation function as relu with a sequential model. We then compile the model with
keeping the optimizer as adam and loss as mean_squared_error.
We calculated the mean squared error of the dataset using the polynomial regression with the
help of mean_square_error library from sklearn library. The mean squared error obtained is
0.0324818277480495.

Results:
The Mean squared error using Linear Regression model is 0.01
The Mean squared error using polynomial model is 0.00
The Mean squared error using 3-Layer neural network is 0.0324818277480495
As we can see the mean square error for the polynomial model is least compared with the
Linear regression and neural network, which is 0.00. The lower the error the more the quality of
the code and the closer the code is to the actual code. As the error is least, it is the best suitable
method. The Linear regression model also obtained the least value of mean square error
compared to neural networks which is 0.01.
As we can see the regression models provide the best outcome or best quality for the code
compared to the neural networks which makes it statistically significant.
