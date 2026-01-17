The challenge is a monthly sales forecast based on real data from a Siemens business unit in Germany.

We performed time series forecasting using machine learning algorithms based on each of the fourteen groups of products' historical sales and the market indices data from 
October 2018 to April 2022 to predict the sales specifically for the Germany unit.

The project follows the CRISP-DM process model, which began by understanding the company's operational background, its objectives and defining the success criteria. Before 
engaging with the data provided by Siemens Advanta, we set precise data mining objectives for this monthly forecasting. Then, following that methodology, we proceeded with 
understanding each macro economical index and found some extra information that could be relevant for the predictions: covid impact, Siemen's year's closure and blockage of 
the Suez Canal. After, data preprocessing was addressed, dealing with anything that could potentially harm the results such as missing values, negative purchase, duplicates 
and outliers. Next, we applied some models for the best RMSE results and could be applied due to the models' requisites and our data limitations: CatBoost, Prophet, Means and 
Median. After conducting thorough analysis, we consistently found that CatBoost models yielded the lowest RMSE, indicating superior performance. Leveraging this insight, we 
employed Prophet to forecast future market data based on selected features for each product. Subsequently, using CatBoost for its proved superior predictive capabilities, we 
generated sales forecasts for individual product groups on unseen data.

The culmination of these efforts involved integrating all individual sales predictions into the test data template for submission. This monthly forecast plays a pivotal role 
for Siemens in refining strategic planning, incorporating insights from our analytical process, best-performing models, macroeconomic trends, and historical company data.
