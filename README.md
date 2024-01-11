# Energy Consumption Forecasting

This project focuses on forecasting energy consumption using a combination of LSTM (Long Short-Term Memory) and Transformer models. The goal is to leverage the strengths of both architectures and improve the accuracy of energy consumption predictions.

## Overview

The project includes the following components:

1. **Data Preprocessing**: The energy consumption dataset is loaded and preprocessed. Missing values are handled, and the data is resampled to different time intervals.

2. **LSTM Model**: A Long Short-Term Memory (LSTM) model is implemented for time series forecasting. The model is trained on resampled data and evaluated on test data.

3. **Transformer Model**: A Transformer model is implemented for time series forecasting. Similar to the LSTM model, it is trained on resampled data and evaluated on test data.

4. **Combined Model**: The predictions from both the LSTM and Transformer models are combined to create a hybrid model. This combined model aims to leverage the strengths of both architectures.

5. **Evaluation**: The performance of each model (LSTM, Transformer, and Combined) is evaluated using metrics such as Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE). The results are visualized for better interpretation.

## Usage

### Requirements

- Python 3.x
- TensorFlow
- Keras
- Scikit-Learn
- NumPy
- Pandas
- Matplotlib

### Installation

Clone the repository and install the required packages:

```bash
pip install -r requirements.txt
```

### Running the Models
Execute the .ipynb scripts to train and evaluate the models:

### Results
The results of the individual models (LSTM and Transformer) as well as the combined model are presented in terms of RMSE and MAE. Visualizations are provided for a better understanding of the forecasting performance.