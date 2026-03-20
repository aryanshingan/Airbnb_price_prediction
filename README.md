# Airbnb_price_prediction
This project aims to predict Airbnb listing prices in New York City using machine learning models. The objective is to understand how factors such as location, room type, availability, and customer reviews influence the pricing of Airbnb listings.

# Dataset
Dataset Name: New York City Airbnb Open Data
Source: Kaggle

Description:
The dataset contains detailed information on Airbnb listings in NYC, including host details, neighborhood, room type, availability, reviews, and pricing.

Key Columns:

neighbourhood_group, neighbourhood, room_type, price
minimum_nights, number_of_reviews, reviews_per_month
calculated_host_listings_count, availability_365
Target Variable: price

# Process
1-Data Collection:
Imported NYC Airbnb listing dataset from Kaggle using the Kaggle API.
Ensured data completeness and accuracy.

2-Data Preprocessing:
Handled missing values and removed outliers.
Encoded categorical features (e.g., neighborhood, room type).

3-Exploratory Data Analysis (EDA):
Visualized price variations across neighborhoods and room types.
Analyzed the relationship between reviews, availability, and price.

4-Model Training:
Applied Linear Regression and XGBoost models.
Split data into training and testing sets (80:20 ratio).

5-Model Evaluation:
Compared models using MAE, RMSE, and R² Score.
Identified key features influencing Airbnb prices.


# Conclusion

-Airbnb prices vary significantly by neighborhood group and room type.
-Features such as availability, number of reviews, and host activity strongly influence pricing.
-XGBoost outperformed traditional regression models, providing more accurate predictions.
-This analysis can assist both hosts and guests in understanding price dynamics and setting optimal rates.

