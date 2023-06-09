# New York City Taxi Demand Prediction

The "New York City (NYC) taxi demand prediction" project is part of the master thesis titled "Predicting On-Demand Transport Requests with Machine Learning Algorithms".


## Objective 

The primary objective of this project is to develop accurate machine learning models to forecast taxi demand. This project focuses on two methodolodical approaches:
1. <b>Temporal forecasting: This approach aims to predict the hourly demand for taxis. </b>
* Linear Regression 
* Random Forest 
* Long Short-Term Memory
3. <b>Spatiotemporal forecasting: This approach aims to predict the hourly demand for taxis at specific pickup locations </b>
* Linear Mixed Model
* Mixed Effects Random Forest


## Dataset 

The project utilizes the dataset of yellow medallion taxi rides obtained from the NYC Taxi and Limousine Commission (TLC).
The raw data consits of approximately 20 million trip records covering the period from January 1, 2022 to June 30, 2022. 

## Project Structure

The project is organized into the following sections: 

1. Data Cleaning: In this stage, the dataset is explored and cleaned to ensure consistency and accuracy of the data.
2. Exploratory Data Analysis: This stage involves analyzing and visualizing temporal and spatial patterns of demand.
3. Data Preparation: The dataset is prepared for model training. Feature engineering and external data integration is applied. 
4. Temporal Forecasting Models: This section focuses on the deployment of the Linear Regression, Random Forest, and Long Short-Term Memory. Feature importance is evaluated using SHAP values.
5. Spatiotemporal Forecasting Models: This section focuses on the deployment of the Linear Mixed Model and Mixed Efects Random Forest. Feature importance is evaluated using SHAP values.


## Code Availability

The project code is available in two formats: 
1. Jupyter Notebook (Markdown_ipynb): The code and its documentation can be found in the provided markdown ipynb folder.
2. PDF Files (Markdown_pdf): The code along with its markdown documentation has also been converted into PDF format for easier readibility and accessibility.

Please refer to the respective files for a comprehensive understanding of the project implementation and results.
