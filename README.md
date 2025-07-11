# Expression_ML
- **Naïve method**: using the most recent observation as a forecast. 

- **Forecasting**: is about predicting the future as accurately as possible, given all of the information available, including historical data and knowledge of any future events that might impact the forecasts.

- **Goals**: are what you would like to have happen. Goals should be linked to forecasts and plans, but this does not always occur. Too often, goals are set without any plan for how to achieve them, and no forecasts for whether they are realistic.

- **Planning**:: is a response to forecasts and goals. Planning involves determining the appropriate actions that are required to make your forecasts match your goals.

- **Short-term forecasts** : are needed for the scheduling of personnel, production and transportation. As part of the scheduling process, forecasts of demand are often also required.
  
- **Medium-term forecasts** : are needed to determine future resource requirements, in order to purchase raw materials, hire personnel, or buy machinery and equipment.

- **Long-term forecasts** : are used in strategic planning. Such decisions must take account of market opportunities, environmental factors and internal resources.  

-**95% prediction intervals** : 

-**Trend**: changeing direction in long-term.

-**Seasonal**: seasonal factors such as the time of the year or the day of the week, 

-**we usually combine the trend and cycle into a single trend-cycle component (often just called the trend for simplicity).**

-**Seasonally adjusted series**: If the variation due to seasonality is not of primary interest , If the seasonal component is removed from the original data, the resulting values are the “seasonally adjusted” data.

- Flow of advancing in decomposition of the seasonal -->  additive decomposition- multiplicative decomposition - X11 - SEATS (Seasonal Extraction in ARIMA Time Series) - STL (Seasonal and Trend decomposition using Loess) -
-  
<img width="1090" height="406" alt="image" src="https://github.com/user-attachments/assets/e96be64a-7572-462c-981f-848306ff33cf" />

Data preparation (tidy) - Plot the data (visualise) - Define a model (specify) - Train the model (estimate) - Check model performance (evaluate) - Produce forecasts (forecast)

-**residual refers**: the difference between the actual observed value and the value predicted (or fitted) by the model.

-** Innovation Residuals**: Sometimes, data is transformed (e.g., using logarithms) before modeling.

-**If residuals are randomly scattered around zero, it means the model is doing a good job. // If residuals show a pattern, it means the model has missed some information or trend in the data and needs improvement.**

-**homoscedasticity**:The innovation residuals have constant variance. This is known as “homoscedasticity”.

-**Box-Cox transformation **: a widely used method in statistics to transform non-normally distributed data into a more normal distribution

-**bootstrapped**: is a reference to pulling ourselves up by our bootstraps, because the process allows us to measure future uncertainty by only using the historical data.

