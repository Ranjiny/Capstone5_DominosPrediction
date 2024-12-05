Problem Statement:
Dominos faces challenges in optimizing its ingredient ordering process. Without accurate sales forecasts, there is a risk of either overstocking (leading to waste) 
or stockouts (resulting in missed sales). Efficient inventory management is crucial to ensure the right amount of ingredients are ordered at the right time.
Aim:
The goal of this project is to develop a predictive model that uses historical sales data and ingredient information to forecast future sales. 
This will enable Dominos to generate accurate purchase orders, ensuring optimal stock levels, reducing waste, and preventing stockouts.
Business Use Cases:
• Inventory Management: Maintain optimal stock levels to avoid overstocking or running out of ingredients.
• Cost Reduction: Reduce waste and costs from excess or expired inventory.
• Sales Forecasting: Predict future sales to guide strategic decisions and promotions.
• Supply Chain Optimization: Align ordering processes with predicted demand to avoid disruptions.

Libraries: tensorflow,ind_holidays,fbprophet . Install appropriate libraries as required.

Approach:
1.	Data Cleaning and EDA
2.	Feature engineering
3.	Model selection(ARIMA, SARIMA, Prophet, LSTM, XGBoostRegressor).Train on the historical data and evaluate the performance
4.	Choose the best model and predict the sales for each pizza type for the next one week.
5.	Calculate the ingredients required for the forecasted sales and generate the PO.
