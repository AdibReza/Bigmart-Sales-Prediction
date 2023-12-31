# Bigmart-Sales-Prediction

**Overview of the BigMart Sales Prediction Project**

In the "BigMart Sales Prediction" project for the CSE422: Artificial Intelligence course, our group aimed to forecast the sales of various products across BigMart outlets. By leveraging machine learning techniques, we developed a predictive model to assist businesses in optimizing their marketing strategies, understanding sales patterns, and making informed decisions.

![Big Mart Sales](https://github.com/AdibReza/Bigmart-Sales-Prediction/assets/92293886/39c62c4f-5956-45e7-ac32-2dbbdd729d2f)

**Key Steps and Contributions:**

1. **Understanding the Dataset:** We began by exploring the BigMart sales dataset sourced from Kaggle, which comprised 12 features including product details, outlet information, and sales data. Recognizing it as a regression problem, our goal was to predict the 'Item_Outlet_Sales' value.

2. **Data Pre-processing:** Addressing missing values in the dataset was crucial. We imputed the mean for 'Item_Weight' and utilized mode imputation for 'Outlet_Size'. Additionally, we standardized categorical features and addressed inconsistencies in categorical values.

3. **Feature Scaling:** To ensure uniformity and enhance model performance, we applied standard scaling to certain numerical features.

4. **Model Training and Evaluation:** We experimented with four regression models: RandomForestRegressor, LinearRegression, Lasso, and XGBRegressor. After training these models, we evaluated their performance using metrics like R-squared and Root Mean Squared Error (RMSE).

5. **Analysis and Conclusion:** Based on our analysis, RandomForestRegressor emerged as the most effective model, achieving the highest R-squared value and the lowest RMSE. Our findings underscored the potential of machine learning in providing accurate sales predictions, aiding businesses in strategic planning and decision-making.


Overall, this project provided a comprehensive learning experience, bridging theoretical knowledge with practical application in the domain of artificial intelligence and predictive analytics.
