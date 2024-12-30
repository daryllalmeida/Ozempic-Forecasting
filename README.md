<b> OZEMPIC FORECASTING PROJECT </b>

Problem Statement : To develop an accurate forecasting model for predicting total sales volume across the U.S. regions for better resource planning, inventory management, and strategic decisions.

Model Selection : For this dataset, I experimented with a range of forecasting models, including ARIMA, Seasonal ARIMA, an Ensemble Model approach Regression model and advanced machine learning models like XGBoost and Random Forest in addition to the Holt-Winters model. 
After careful evaluation, I proceeded with the Holt-Winters model due to its superior ability to effectively capture both trend and seasonal components inherent in the data. 
When compared to ARIMA and the machine learning models, Holt-Winters demonstrated significantly better performance in terms of key metrics such as Mean Absolute Error (MAE) and Mean Absolute Percentage Error (MAPE). 
Its consistent accuracy and capacity to handle seasonal patterns made it the most reliable choice for forecasting in this project.

Results & Model Performance: Holt-Winters with a seasonal period of 6 works better than ARIMA(2,2,2), Random Forest, and XGBoost, proving to be the most effective model for this forecasting task. 
It successfully captured both the trend and seasonality present in the data by showing us the most reliable predictions among all the models evaluated. 
The model achieved a MAPE of 13.3% and an MAE of 2038.53 which indicates a high level of accuracy in predicting the total volume sold. 
These metrics suggest that the Holt-Winters model not only minimizes error but also provides actionable insights for strategic decision-making. 



