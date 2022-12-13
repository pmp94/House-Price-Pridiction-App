# House Price Pridiction model by Param Patel

Objective:
The objective of this project is to develop a model that can accurately predict the sale price of a house based on a set of relevant features.

Pridict House Rate by
bedrooms       - No. of bedrooms
bathrooms      - No. of bathrooms
sqft_living    - square footage of the living
sqft_lot       - square footage of the lot
floors         - No. of floors
waterfront     - Nearby
view           - side views from houes
condition      - Out of 5
no_year        - How old is the house
statezip       - Zipcode

Algorithm: I used Random forest a Supervised Machine Learning Algorithm to test and train my model. Test will be 20% and train will be 80%

Evaluation: To evaluate the performance of the model, we will use a variety of metrics, such as mean absolute error and mean squared error. 

##How to use
step 1 - pip install -r requirements.txt
step 2 - run House_Predict_Model_ParamPatel.ipynb and it will create a file called random_forest_regression_model_y_5.pkl
step 3 - flask run
