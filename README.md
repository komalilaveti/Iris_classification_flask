# Iris_classification_flask

This repository contains a simple Flask web application for predicting the Iris flower species based on input features. The application uses a pre-trained machine learning model to make predictions.

The main files in this repository are:

- `index.html`: This HTML template defines the user interface of the web application. It includes input fields for sepal length, sepal width, petal length, and petal width. Upon submission, the form data is sent to the Flask server for prediction.

- `deploy.py`: This Python script sets up the Flask application, loads the pre-trained model from the 'iris_model.sav' file, and defines the routes for handling requests. The '/' route renders the home page, and the '/predict' route receives the form data, makes predictions using the model, and renders the results on the page.

- `iris_model.sav`: This is the serialized machine learning model file (pickle format) that is loaded by the Flask application for making predictions. Ensure that this file exists in the same directory as 'deploy.py'.

To run the application, follow these steps:

1. Install the required dependencies listed in 'requirements.txt'.
2. Make sure the 'iris_model.sav' file is present in the same directory.
3. Execute the 'deploy.py' script using Python.
4. Open a web browser and navigate to 'http://localhost:5000' to access the application.

Feel free to customize and enhance the application according to your needs.

