# GUVI-Capstone-Project-5

# Car Price Prediction Readme

## Overview
This repository contains the code and analysis for predicting the price of used cars based on the CarDekho dataset. The dataset comprises information on 4340 cars, including details such as make year, fuel type, kilometers driven, and more. The primary objectives are to perform Exploratory Data Analysis (EDA), handle missing values and outliers, and create a predictive model for car prices.

## Dataset
The dataset is sourced from CarDekho.com and can be accessed [here](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho).

## Project Structure

- **Notebooks:**
  - `01_Exploratory_Data_Analysis.ipynb`: This notebook contains the code for EDA, exploring trends and insights in the dataset.
  - `02_Data_Preprocessing.ipynb`: Handles missing values, outliers, and converts categorical variables into numerical features.
  - `03_Predictive_Modeling.ipynb`: Builds and evaluates the predictive model for car prices.

- **Data:**
  - `car_data.csv`: The raw dataset obtained from CarDekho.com.
  - `cleaned_data.csv`: The pre-processed dataset after handling missing values and outliers.

- **Models:**
  - `car_price_prediction_model.pkl`: The trained predictive model saved in a serialized format for easy reuse.

## Getting Started
1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/yourusername/car-price-prediction.git
   cd car-price-prediction
   ```

2. Install the required dependencies.
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebooks in the following order:
   - `01_Exploratory_Data_Analysis.ipynb`
   - `02_Data_Preprocessing.ipynb`
   - `03_Predictive_Modeling.ipynb`

4. The trained model will be saved as `car_price_prediction_model.pkl` in the 'Models' directory.

## Usage
- Use the trained model to predict car prices based on their specifications.
- Incorporate the provided functions into your own applications for real-time price predictions.

