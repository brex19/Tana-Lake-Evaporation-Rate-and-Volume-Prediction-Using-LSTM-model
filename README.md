# Tana's Lake Evaporation Rate and Volume Prediction using LSTM

## Overview

This project aims to predict the evaporation rate and water volume of Lake Tana using a Long Short-Term Memory (LSTM) model. Time series data is used to model environmental changes and forecast future evaporation rates. The project consists of exploratory data analysis and the implementation of the LSTM model to make predictions.

## Repository Structure

This repository contains the following files:

- **`EDataset/`**: Holds the dataset used for training and testing the model.
- **`Evaporation.ipynb`**: Contains the exploratory data analysis (EDA) performed on the dataset to understand the data trends and features.
- **`Prediction-final.ipynb`**: Implements the LSTM model using the processed data from the EDA notebook (`Evaporation.ipynb`) to predict Lake Tana's evaporation rate and volume.

## File Descriptions

1. **`EDataset/`**
   - The dataset folder includes the raw data used in this project. This data consists of time-series information related to Lake Tana's evaporation rate and water volume over time.
   
2. **`Evaporation.ipynb`**
   - This Jupyter Notebook contains the Exploratory Data Analysis (EDA) conducted on the dataset. It includes data cleaning, feature extraction, and visualization to better understand the key patterns in the dataset.

3. **`Prediction-final.ipynb`**
   - This Jupyter Notebook contains the final implementation of the LSTM model. It takes the processed data from the EDA notebook and predicts the future evaporation rate and volume of Lake Tana using a time-series forecasting approach.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/tana-evaporation-prediction.git
   cd tana-evaporation-prediction
   ```

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

   Make sure you have all the necessary libraries installed, such as `tensorflow`, `pandas`, `matplotlib`, and `numpy`.

3. Explore the data by opening the `Evaporation.ipynb` notebook in Jupyter:

   ```bash
   jupyter notebook Evaporation.ipynb
   ```

4. Once the exploratory data analysis is complete, run the `Prediction-final.ipynb` notebook to train and test the LSTM model:

   ```bash
   jupyter notebook Prediction-final.ipynb
   ```

## Results

- The LSTM model is trained to predict both the evaporation rate and volume of Lake Tana based on historical time-series data.
- The results include visualizations of the predicted vs. actual evaporation rates and volume to assess the accuracy of the model.

## Future Improvements

- Extend the dataset with additional environmental factors, such as wind speed and humidity, to improve prediction accuracy.
- Implement a model comparison using other time-series forecasting models like ARIMA, Prophet, or GRU.
- Create an interactive web dashboard for real-time evaporation rate monitoring and prediction.

