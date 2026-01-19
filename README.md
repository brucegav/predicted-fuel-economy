# Fuel Economy Prediction Analysis

This project predicts vehicle fuel efficiency (MPG) using the classic Auto-MPG dataset. 

## Key Results
* Final Test R2: 0.832
* Mean Absolute Error (MAE): 2.52 MPG

## Technical Workflow
1. EDA: Identified multicollinearity between engine displacement and weight.
2. Feature Engineering: Created Polynomial Features and Interaction Terms.
3. Transformation: Applied Log Transformation to the target variable to address heteroscedasticity.

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Run the Jupyter Notebook: `fuel_prediction.ipynb`
