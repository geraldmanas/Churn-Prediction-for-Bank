# Churn-Prediction-for-Bank

Customer churn is a loss of clients because of customers stopping doing business with a company. It is an important metric for businesses to track, as it can have significant financial implications. For example, acquiring new customers can be more expensive than retaining existing ones, so reducing churn can help a company save on marketing and sales costs.

In the context of banking, customer churn refers to customers leaving a bank and taking their business elsewhere. This can be a significant issue for banks, as acquiring new customers can be more expensive than retaining existing ones. Therefore, banks may implement strategies to reduce customer churn and retain valuable customers.

There are many factors that can contribute to customer churn in the banking industry, such as dissatisfaction with service, high fees or charges, or a lack of convenient or innovative services. Banks may also face competition from other financial institutions that offer more attractive products or services.

in this project, i did analysis about why customer churn from bank and how to retain them based on data.

Why?

<img width="169" alt="image" src="https://user-images.githubusercontent.com/85125450/209783056-73eb1037-8892-4e11-bc94-1b8aecffa1d1.png">

around 20.37% customer is churning. if we can know why they are churning, it can increase company profits by 25-95% ( Gallo in Harvard Business Review (2014)).
After we did the analysis, we know that

<img width="408" alt="image" src="https://user-images.githubusercontent.com/85125450/209783603-69e5037c-6e15-4657-8a66-bbcddf34cb8d.png">

Germany and France customer are churning the most,

<img width="427" alt="image" src="https://user-images.githubusercontent.com/85125450/209783738-e672fa25-184a-4741-8642-d09c3885ff4d.png">

we can also conclude that Customers with an age range of over 20 years to under 40 tend not to churn. However, from the age of 40, the level of churn starts to increase until around the age of 60.

<img width="456" alt="image" src="https://user-images.githubusercontent.com/85125450/209783854-d9d6c5b9-b1ae-4d73-9d8f-fff3e0054c90.png">

we also conclude that As many as 13.02% of customers who do churn are inactive customers.

<img width="446" alt="image" src="https://user-images.githubusercontent.com/85125450/209783932-54cb5b8f-6719-4c80-813f-b27f01c64db1.png">

also Customers with more than 2 products tend to churn.

In this project, we are using machine learning to predict customer churning based on data that we have. We did it using difference model such as XGBoost, Random Forest Classifier, Adaboost Classifier, Decision Tree, K-Nearest Neighbor, and Logistic Regression. 

<img width="803" alt="image" src="https://user-images.githubusercontent.com/85125450/209784377-13858a1e-a15c-49e7-8044-5183a3e40ea5.png">

Based on all the tuned models, the model that has the best AUC metric results is the XGBoost Classifier. From the tuned Machine Learning model, we select the top four (4) Feature Importance for us to provide Business Recommendations which is Number Of Products, Age, Active Member, and Geography. 

<img width="445" alt="image" src="https://user-images.githubusercontent.com/85125450/209784614-935dcd1e-2afe-480a-ad78-44c5cbca9418.png">

Based on it, we can give our recommendation which is Add value and/or bonus schemes to purchases of more than two products (bundling packages, reduce tax and interest costs, provide small-scale vouchers/rewards, add product services), Providing financial offers to customers in the age range of 40-60 years (home loan programs, car loans) and offering a Financial Wellness Program for each customer, Provide non-provocative notifications for inactive members and provide several promotions/one-time big promotions (cashback/discounts/bundling deals) based on previous product usage/purchases, and Adding product value to branches in Germany (bundling packages, reducing tax and interest costs, providing small-scale vouchers/rewards, adding product services), and speeding up and simplifying Customer Service schemes to make it more convenient to access.


