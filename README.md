# autoregressor

- Python library to automate the process of building machine learning models
- Handles missing values and scaling of the dataset before training of models.
- Trains multiple regression models on the pre-processed data and ensembles the best performing model.
- Fits the data in the final model, predicts the output from the testing dataset and returns prediction after inverse scaling to the orignal scale and provides the evaluation of the final model.


You can install autoregressor from PyPI
    
    $ pip install autoregressor
    
Once the library is installed, import the modules in your python notebook or any IDE of your choice.

    $ import autoregreessor
    $ from autoregressor import autoregressor
    
We now have the package imported. To use the library, we use:

    prediction = autoregressor.solve(X_train , y_train , X_test)
    
Where, 

* prediction - Predicted output of the Regression model.
* X_train - Training dataset
* y_train - Target variable of the training dataset
* X_test - Testing dataset
