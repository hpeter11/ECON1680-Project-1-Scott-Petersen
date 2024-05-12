# Using XGBoost to Predict Uber Rates in the Greater Boston Area

## Description
This repository contains code for analyzing Uber pricing data using machine learning techniques. The analysis aims to predict Uber prices based on various factors such as weather conditions, time of day, and location.

## Installation
Clone the repository to your local machine. Ensure that you have Python and necessary libraries installed. You can install the required dependencies using `pip install 'your_library_name'` or `conda install 'your_library_name'`.

## Content
This repository contains the following files:

- **Code.ipynb**: Jupyter Notebook containing code for data preprocessing, model training, evaluation, and analysis.
- **Data**: The dataset used for this analysis consists of Uber rides and weather data. The data will not appear on Github but can be downloaded [here](link_to_dataset) and should be uploaded to the data folder. The dataset includes the following variables:
  - 'distance': Distance of the ride.
  - 'cab_type': Type of Uber cab.
  - 'time_stamp': Timestamp of the ride.
  - 'destination': Destination of the ride.
  - 'location': Pickup location.
  - 'price': Price of the ride.
  - 'surge_multiplier': Surge multiplier for pricing.
  - 'id': Unique identifier for the ride.
  - 'product_id': Product identifier for the ride.
  - 'name': Name of the ride.
  - 'temp': Temperature.
  - 'clouds': Cloud coverage.
  - 'pressure': Atmospheric pressure.
  - 'rain': Rainfall.
  - 'humidity': Humidity.
  - 'wind': Wind speed.

## Usage
Follow these steps to use the code:

1. Run the Jupyter Notebook `Code.ipynb` to replicate the analysis, ensuring the relevant libraries are installed in your environment.
2. Follow the code cells to understand the data preprocessing, model training, evaluation, and analysis steps.
3. Experiment with different machine learning algorithms, hyperparameters, and feature engineering techniques to improve prediction performance.
4. Make your own interpretation of the results and insights provided in the notebook to understand factors influencing Uber prices.

