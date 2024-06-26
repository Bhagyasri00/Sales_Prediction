# Rossmann_Retail_Sales_Prediction

![rossmann-filiale](https://github.com/Bhagyasri00/Sales_Prediction/assets/142825445/917fe920-0c39-4582-88cd-92a27a766db0)

#  About Rossmann
Rossmann is a prominent chain of drug stores operating across seven European countries, with over 3,000 stores in its network. The company offers a wide range of products, including pharmaceuticals, personal care items, beauty products, household goods, and more. Rossmann is known for its extensive product selection, competitive pricing, and convenient store locations.Founded in Germany in 1972 by Dirk Rossmann, the company has since expanded its presence across Europe, becoming one of the largest drug store chains in the region. Rossmann's stores are known for their modern and inviting layouts, making shopping convenient and enjoyable for customers.


#  Problem Statement

Rossmann operates a large chain of drug stores across seven European countries, totaling over 3,000 stores. Store managers are responsible for predicting daily sales up to six weeks in advance, considering various influencing factors such as promotions, competition, holidays, seasonality, and locality. However, the accuracy of sales predictions varies among individual managers due to their unique circumstances and approaches. To address this variability and improve forecasting accuracy, the task is to develop a robust machine learning model using historical sales data from 1,115 Rossmann stores. The objective is to accurately forecast the "Sales" column for the test set, considering factors like promotions, holidays, and other relevant features. This model will provide store managers with reliable sales forecasts, enabling them to optimize inventory management, staffing, and promotional strategies, thereby enhancing operational efficiency and maximizing revenue across Rossmann stores.

# Project Summary

*  Exploratory Data Analysis (EDA) revealed insights such as the linear relationship between customers and sales, the impact of promotions and holidays on sales, and seasonal sales patterns.
*  Data preprocessing involved converting date columns, handling missing values, encoding categorical features, and removing outliers.
Feature engineering included creating new features and removing multicollinear features to improve model performance.
*  Three regression models (Linear Regression, Decision Tree, Elastic Net) were implemented, with hyperparameter tuning to optimize model performance.
Random Forest Regression was selected as the final prediction model due to its superior performance after tuning and its ability to handle non-linearity and feature importance evaluation.
*  Model explainability was achieved through feature importance analysis using Random Forest
*  The final model achieved significant improvements in predictive accuracy, making it a valuable tool for Rossmann store managers to forecast sales and optimize business strategies.

# Conclusion

*  Utilize insights on the impact of promotions to optimize promotional strategies, ensuring effective timing and types of promotions.
Use sales forecasts to optimize staffing levels and inventory management, ensuring adequate resources during peak sales periods while minimizing excess stock.
*  Plan staffing, promotions, and inventory management strategies in advance for holidays and school breaks, considering their impact on sales.
*  Analyze individual store performance based on model predictions, identifying areas for improvement and implementing targeted strategies.
*  Enhance the overall customer experience by tailoring promotions, product offerings, and store layouts to meet customer preferences and needs.
*  Monitor the competitive landscape and adjust pricing, promotions, and marketing strategies accordingly to stay ahead of competitors.

