#  LSTM Time Series Forecasting

This project demonstrates how to build and train a Long Short-Term Memory (LSTM) neural network for time series forecasting using Python and TensorFlow/Keras.

---

##  Overview

Time series forecasting is a powerful technique used to predict future values based on previously observed data points. This project implements a Long Short-Term Memory (LSTM) model using TensorFlow/Keras to perform time series forecasting on the Air Passengers dataset. The objective is to predict the number of monthly international airline passengers over time using historical trends.


The script will:

- Load and visualize the original passenger data.

- Normalize data and create 12-month sequences.

- Split into training (80%) and testing sets.

- Build and train an LSTM model (50 units + dropout).

- Compute RMSE and R² for train and test sets.

- Forecast the next 12 months of passenger counts.

- Plot actual vs. predicted values and future forecast.

##  Requirements

- Python 3  
- Required Python packages:

    - TensorFlow / Keras  
    - NumPy  
    - Matplotlib / Seaborn  
    - Pandas
    - scikit-learn

---

##  Files

- `LSTM_Time_series_Forecasting.ipynb`: Jupyter Notebook containing the full code and explanations.

---

##  How to Run

1. Clone the repository or download the notebook.

2. Make sure you have the required packages installed. You can use the following:

    ```bash
    pip install numpy pandas matplotlib seaborn tensorflow
    ```

3. Open the notebook using Jupyter or any compatible environment:

    ```bash
    jupyter notebook LSTM_Time_series_Forecasting.ipynb
    ```

4. Run each cell in order to train and test the model.

---

##  Results

- Time Series Plot of Actual Data
- Predicted vs Actual on Test Set
- Forecast for Next 12 Months


##  Notes

- Ensure your dataset is properly formatted (time series with consistent intervals).  
- You may need to tweak hyperparameters or sequence length based on your specific use case or dataset.

---

