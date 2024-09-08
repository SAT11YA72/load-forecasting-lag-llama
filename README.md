# Load Forecasting using Lag-LLAMA

This repository showcases the implementation of load forecasting using the Lag-LLAMA model, focusing on short-term and long-term electricity demand predictions. We utilized an existing time series foundation model, Lag-LLAMA, to analyze and predict electricity consumption patterns.

## Data Format:
- Data should be formatted as follows: **time as index, power, item_Id**.
- If your dataset doesn't contain an item_Id, assign a random string (same for every row).

## How to Use:
- This repository contains Jupyter notebooks that demonstrate how to preprocess data and apply the Lag-LLAMA model for load forecasting.
- If your data is already in the required format, use `main.ipynb` to perform the forecasting.
- If your data needs preprocessing, refer to `Dataset.ipynb` and `data_preprocessing.ipynb`, and modify them according to your dataset.

## Important Notes:
- The Lag-LLAMA model is an open-source time series forecasting model, and we did not develop it from scratch. This repository focuses on its application to load forecasting.
- To run the fine-tuning part of the code, **GPU** access is required.

## Demo:
- Explore our implementation through this Colab notebook: [Demo Link](https://colab.research.google.com/drive/1EPYFI79JJJvmDqpAR9zhBs18OGq9QUJJ)

## Dataset:
The dataset used for this project is the Smart Meter Data from Mathura and Bareilly, which you can find on Kaggle [here](https://www.kaggle.com/datasets/jehanbhathena/smart-meter-data-mathura-and-bareilly).

## Future Work:
- Investigate fine-tuning methods to enhance long-term forecasting performance with the Lag-LLAMA model.
