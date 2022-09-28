# Customer Churn Prediction

Customer churn is defined as the rate which customers cancel a subscription to a service they have been using. Customer churn prediction is important for many business because acquiring new clients often costs more than retaining existing ones. This problem is classified as **binary classification** because it will give only 2 outputs (0 for staying with the service and 1 for leaving the service). 

## About Dataset
Dataset used in this project is downloaded from [Kaggle](https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction)

The dataset has 20 features including :
- CustomerID                  : Unique customer ID
- Churn                       : Churn Flag
- Tenure                      : Tenure of customer in organization
- PreferredLoginDevice        : Preferred login device of customer
- CityTier                    : City tier
- WarehouseToHome             : Distance in between warehouse to home of customer
- PreferredPaymentMode        : Preferred payment method of customer
- Gender                      : Gender of customer
- HourSpendOnApp              : Number of hours spend on mobile application or website
- NumberOfDeviceRegistered    : Total number of deceives is registered on particular customer
- PreferedOrderCat            : Preferred order category of customer in last month
- SatisfactionScore           : Satisfactory score of customer on service
- MaritalStatus               : Marital status of customer
- NumberOfAddress             : Total number of added added on particular customer
- Complain                    : Any complaint has been raised in last month
- OrderAmountHikeFromlastYear : Percentage increases in order from last year
- CouponUsed                  : Total number of coupon has been used in last month
- OrderCount                  : Total number of orders has been places in last month
- DaySinceLastOrder           : Day Since last order by customer
- CashbackAmount              : Average cashback in last month

## Model Used
In this project, I compare several ML models (Logistic Regression, XGBoost, Random Forest, and SVM) and also ANN. 
