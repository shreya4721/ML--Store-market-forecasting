# ML--Store-market-forecasting
Store Demand Forecasting Technologies Used: Python, Pandas, NumPy, Scikit-learn, XGBoost Developed a demand forecasting model to predict future product demand for retail stores.
# Store Demand Forecasting

This project aims to predict the sales demand for various items in different stores based on historical sales data. The goal is to develop a machine learning model that can provide accurate forecasts for future sales of each store-item combination.

## Technologies Used
- **Python**
- **Pandas**
- **PyTorch**
- **TensorFlow**
- **Microsoft Excel**
- **Canva**
- **Visual Studio Code**
- **Markdown**
- **GitHub**
- **Windows Terminal**

## Problem Description
The objective of the "Store Item Demand Forecasting" project is to predict the sales demand for items across different stores using historical sales data. Accurate sales predictions can help businesses optimize inventory, reduce stockouts, and prevent overstocking, which ultimately improves operational efficiency.

## Dataset Information

The dataset consists of historical sales records for items sold at different stores. It is split into two datasets:

- **Training Dataset**: Used to train the model. Contains the following columns:
  - `date`: Date of the sales record (in datetime format).
  - `store`: Store ID where the item was sold.
  - `item`: Item ID that was sold.
  - `sales`: Quantity of items sold on that specific date at the given store.

- **Test Dataset**: Contains the same columns as the training dataset but lacks the `sales` information, which is the target variable for prediction.

## Background Information

Demand forecasting plays a crucial role in retail and supply chain management. Accurate demand forecasts help retailers optimize inventory, allocate resources efficiently, and prevent issues like stockouts and overstocking.

In this project, we use machine learning algorithms and time series forecasting techniques to build a predictive model that can forecast future sales based on historical data. Various factors, such as seasonality, trends, and special events, impact demand, and our goal is to develop a model that can effectively capture these factors for accurate predictions.

## Objective

The primary goal is to build a machine learning model that accurately predicts future sales for store-item combinations based on historical sales data. This will enable retailers to improve inventory management, optimize promotions, and make data-driven decisions to meet customer demand.

## Approach

The following steps were taken to achieve the project objective:

1. **Data Loading and Exploration**: Loaded the training and test datasets to explore the data's structure and statistical properties.
   
2. **Feature Engineering**: Extracted time-related features from the `date` column and created additional features to improve model performance.
   
3. **Lag Feature Generation**: Created lag features to capture past sales patterns, important for time series forecasting.

4. **Rolling Mean Features**: Applied rolling mean features to smoothen the data and capture long-term trends.

5. **Exponential Weighted Moving Averages (EWMA)**: Used EWMA to emphasize more recent sales data for better forecasting.

6. **Machine Learning Algorithms**: Implemented LightGBM (and other machine learning algorithms) to train the model on historical sales data.

7. **Performance Evaluation**: Evaluated the model using SMAPE (Symmetric Mean Absolute Percentage Error) to measure forecasting accuracy.

8. **Prediction Generation**: Made predictions on the test dataset to forecast future sales for each store-item combination.

9. **Visualization and Comparison**: Visualized forecasted sales and compared them with actual sales to assess model effectiveness.

## Results and Evaluation

The model's performance was evaluated using SMAPE, providing insights into the accuracy of predictions. Visualizations were created to compare the forecasted and actual sales, highlighting the model's ability to predict future demand.

## Conclusion

By applying machine learning and time series forecasting techniques, this project developed a model capable of accurately predicting future sales demand for store-item combinations. The model's predictions can assist retailers in optimizing inventory, managing stock levels, and making data-driven decisions.


