Time Series Forecasting Using LSTM Networks

This project explores how Long Short-Term Memory (LSTM) neural networks can be used for time series forecasting with TensorFlow and Keras.

 Overview

Using historical monthly air passenger data, we build a deep learning model that can capture time-dependent patterns and forecast future values.  
The dataset is processed and reshaped into a supervised format before being fed into the LSTM model.

Features

- Utilizes the `AirPassengers.csv` dataset  
- Data preprocessing and transformation into sequences for LSTM input  
- LSTM model training and testing  
- Inverse scaling of predictions  
- Evaluation with R² metric for both train and test sets  
- Clean and intuitive visualizations of results

Dataset

We use the classic **AirPassengers** dataset, which includes monthly totals of international airline passengers from 1949 to 1960.  
Ensure the CSV file is uploaded to your Colab environment or placed in the same directory locally.  
The dataset is also included in this repository.
 
Libraries Used

- `pandas` for data handling  
- `numpy` for numerical computations  
- `matplotlib` for visualizations  
- `sklearn` for preprocessing and metrics  
- `tensorflow.keras` for building the LSTM model

 Visualizations

- Red-themed compact plots  
- Line graphs showing actual vs predicted values  
- Loss progression throughout training  
- Clear labeling for interpretability

 How to Use

1. Upload `AirPassengers.csv` in your Colab session or keep it in the same folder locally  
2. Open the `.ipynb` notebook and run the cells step by step  
3. Ensure necessary packages are installed (`pip install -r requirements.txt` if needed)  
4. Observe prediction quality and loss trends through visuals

 Output Summary

- Graphical forecast performance comparison  
- Loss vs epoch curve  
- R² metrics for evaluating model fit

---

**Disclaimer:**  
This notebook is intended for educational use. You can easily swap in your own time series dataset by following the same pipeline.

