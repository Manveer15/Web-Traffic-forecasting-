## Real-time Web Traffic Forecasting using LSTM and CNN
 ** Overview **
This project implements a web traffic forecasting model using Long Short-Term Memory (LSTM) networks and Convolutional Neural Networks (CNN) in Python.
Although designed for real-time forecasting scenarios, the current version uses historical time-series web traffic data from a publicly available Kaggle dataset (due to lack of live website analytics access).

The model achieved ~89% accuracy on benchmark datasets, demonstrating strong performance in predicting future web traffic trends.

Dataset
Source: Kaggle - Web Traffic Time Series Forecasting Dataset

Size: ~200,000 entries

Type: Historical time-series data of website visits

Frequency: Daily observations

Note: This dataset is not real-time. The architecture, however, is designed to be adaptable to real-time streaming data if API access to live web analytics is provided.

**Features**
Combines LSTM (for sequential dependency learning) with CNN (for local pattern extraction).

Handles large-scale time series data efficiently.

Supports multi-step forecasting (predicting several days ahead).

Can be adapted for real-time predictions with minimal architectural changes.

Achieves high forecasting accuracy (~89%) on historical benchmark data.
****
Tech Stack ****
Programming Language: Python

Deep Learning Framework: TensorFlow / Keras

Data Processing: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Modeling: LSTM, CNN

** Model Architecture**
Data Preprocessing

Missing value handling

Normalization / scaling

Train-test split

Model Design

CNN Layers for local trend detection in time series

LSTM Layers for capturing long-term dependencies

Dense layers for final prediction output



Metrics: RMSE, MAE, MAPE

Achieved ~89% accuracy
