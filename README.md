### House Price Prediction Model
## Objective
The objective of this project is to develop a model that can accurately predict the sale price of a house based on a set of relevant features.

## Data
The dataset for this project consists of information about houses that have been sold in the past. It includes the following features:

* Number of bedrooms
* Number of bathrooms
* Square footage of the living space
* Square footage of the lot
* Number of floors
* Proximity to the waterfront
* View from the house
* Condition of the house (on a scale of 1-5)
* Age of the house
* Zip code

## Methodology
To develop the house price prediction model, we will use machine learning techniques. Specifically, we will use a random forest algorithm to train the model on the collected data. This will involve splitting the data into training and test sets, and then using the training data to train the model. The performance of the model will be evaluated on the test set.

## Evaluation
To evaluate the performance of the model, we will use a variety of metrics, such as mean absolute error and mean squared error. We will also conduct a thorough analysis of the model's predictions to ensure that they are reasonable and consistent with market conditions.

## Usage
To use the model, follow these steps:

Install the required dependencies by running pip install -r requirements.txt
1. Run the Jupyter notebook House_Predict_Model.ipynb to train the model and save it to a file
2. Start the Flask app by running flask run
3. Use the app to make predictions by entering values for the relevant features

## Conclusion
This project presents a house price prediction model that can be used to make accurate predictions based on a set of relevant features. The model uses a random forest algorithm and has been evaluated using a variety of metrics. It can be easily integrated into a web app for use by potential home buyers or real estate professionals.
