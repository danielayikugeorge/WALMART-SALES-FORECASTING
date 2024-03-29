
# WALMART SALES FORECASTING
Walmart, a global retail giant, relies on precise sales forecasts across its departments. Given the multitude of factors influencing departmental sales, it is crucial to pinpoint key drivers and leverage them to create an accurate sales forecasting model.


This project aims to develop a sales forecasting model for Walmart using various features extracted from the provided dataset. The model will leverage machine learning techniques to predict future sales for different items across Walmart's outlets.

**Features Used:**

→ Item_Identifier:→ Unique identifier for each item.
→ Item_Weight:→ Weight of the item in grams.
→ Item_Fat_Content:→ Fat content of the item, either "Low Fat" or "Regular".
→ Item_Visibility:→ Visibility of the item in the store.
→ Item_Type:→ Category of the item, such as "Food" or "Drinks".
→ Item_MRP:→ Maximum retail price of the item.
→ Outlet_Identifier:→ Unique identifier for each outlet.
→ Outlet_Establishment_Year:→ Year in which the outlet was established.
→ Outlet_Size:→ Size of the outlet, categorized as "Small", "Medium", or "Large".
→ Outlet_Location_Type:→ Type of location where the outlet is situated, such as "Urban" or "Rural".
→ Outlet_Type:→ Type of outlet, such as "Grocery Store" or "Supermarket".
→ Item_Outlet_Sales:→ Sales of the item in the specific outlet.



**Model Development:**

The model will be developed using a supervised machine learning approach, where a training dataset will be used to train the model and a test dataset will be used to evaluate its performance. Various machine learning algorithms, such as linear regression, decision trees, and random forests, will be explored to identify the best model for the task.

**Expected Outcomes:**

The project aims to provide a robust and accurate sales forecasting model. By leveraging the insights derived from the model, Walmart can better anticipate customer demand and make informed decisions to maximize sales and profitability.

**Conclusion**

![Screenshot 2024-03-03 at 19-16-04 SALES_PREDICTION-Copy1 - Jupyter Notebook](https://github.com/danielayikugeorge/WALMART-SALES-FORECASTING/assets/159738648/43ae58cc-2ead-4c34-91df-2132c53f1057)

 
Overall, the Random Forest model seems to perform the best among the evaluated algorithms,
as it has the highest Test_R2  value of 0.94160,
indicating a strong correlation between the predicted and actual values in the test dataset.
Additionally, it also has the lowest Test_RMSE and Test_MSE values, suggesting that it has the smallest error in
predicting the sales.
