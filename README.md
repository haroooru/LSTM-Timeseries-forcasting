# LSTM-Based Time Series Forecasting

This notebook demonstrates how to use an LSTM (Long Short-Term Memory) model to forecast time series data using TensorFlow/Keras.

## What This Project Does

- Reads monthly air travel data from `AirPassengers.csv`
- Prepares the data for supervised learning
- Builds and trains an LSTM model
- Makes predictions and compares them to real values
- Visualizes the model's predictions and training loss
- Calculates R² score for both training and testing phases

## Dataset Used

The dataset `AirPassengers.csv` contains monthly totals of international airline passengers from 1949 to 1960.  
Make sure to upload this file to your Colab runtime or place it in the same folder if running locally.  
It is also included in this GitHub repository.

## Key Libraries

- NumPy and Pandas  
- Matplotlib  
- Scikit-learn  
- TensorFlow / Keras

## Visual Output

- Smaller-sized plots with red color scheme  
- Training vs prediction graphs  
- Loss over epochs  
- R² metrics printed in the output

## How to Run

1. Upload `AirPassengers.csv` in your Google Colab session or clone the GitHub repo  
2. Open the notebook (`.ipynb`) file in Colab or Jupyter  
3. Install any missing libraries with pip  
4. Run all cells step-by-step

## Output

- Visual and numeric comparison of predicted and actual values  
- Loss curve showing model training over time  
- Evaluation metrics for performance

## Note

This project is created for academic demonstration purposes.  
You can replace the dataset with any other time series data to adapt it to your needs.


