# Customer_Churn_Prediction

Problem Statement: Customer Churn Prediction
Business Context:
AlphaCom, a leading telecommunications provider, has recently experienced a concerning rise in customer churn despite offering competitive services and a wide product portfolio. This increase is directly impacting revenue and undermining brand reputation in an intensely competitive market. Traditional retention strategies have proven inadequate because customer churn is influenced by a complex mix of factors, including service usage, billing preferences, contract types, and demographics. Without clear insights into these patterns, the company is left reacting to churn instead of preventing it.





Objective:



As a data scientist at AlphaCom, you are tasked with developing a predictive model to identify customers at high risk of churn and uncover the key factors driving their decisions. Solving this problem will enable the company to proactively design targeted retention strategies, reduce churn-related losses, and improve customer lifetime value, ultimately safeguarding revenue and strengthening AlphaCom’s competitive position.





Data Description:


The data contains different attributes related to churn. The detailed data dictionary is given below:

Gender: The customer’s gender (e.g., Male or Female). This demographic feature may correlate with customer behavior.
Age Range: Indicates the customer’s age bracket (e.g., 18–25, 26–35, etc.), offering demographic insights that can impact churn analysis.
SeniorCitizen: A binary indicator (if included) that identifies whether the customer is a senior citizen (commonly 1 for senior, 0 for non-senior). Senior status can influence service preferences and retention strategies.
Partner: Indicates whether the customer has a partner. This factor can affect customer loyalty and service usage patterns.
Dependents: Specifies whether the customer has dependents. This information can provide context on the customer’s household and influence their service needs.
Tenure: The number of months the customer has been with the company. Longer tenure may indicate higher loyalty, while shorter tenure could be a churn risk indicator.
PhoneService: Denotes whether the customer subscribes to telephone services. This binary feature (Yes/No) helps understand service adoption.
MultipleLines: Indicates if the customer has multiple phone lines. This feature can provide insight into customer behavior and service complexity.
InternetService: Describes the type of internet service the customer uses (e.g., DSL, Fiber optic, or None). The type of internet service can be a critical factor in churn analysis.
OnlineSecurity: Shows whether the customer subscribes to online security services. This value (Yes/No) may influence customer satisfaction and retention.
OnlineBackup: Indicates if the customer has an online backup service. Similar to online security, this can be a part of the overall service bundle affecting churn.
DeviceProtection: Specifies whether the customer is enrolled in a device protection plan, providing an added layer of service value.
TechSupport: Denotes if the customer subscribes to technical support services. Access to tech support can improve customer experience and reduce churn.
StreamingTV: Indicates whether the customer subscribes to a streaming TV service. Media consumption patterns can be a differentiator in customer preferences.
StreamingMovies: Specifies if the customer subscribes to a streaming movies service. This, combined with other services, can highlight trends in customer behavior.
Contract: Describes the type of contract the customer holds (e.g., month-to-month, one-year, or two-year). Contract type is a strong indicator of churn risk—shorter contracts are often associated with higher churn.
PaperlessBilling: Indicates whether the customer is enrolled in paperless billing. This operational feature can sometimes correlate with customer engagement levels.
PaymentMethod: Details the payment method used by the customer (e.g., electronic check, mailed check, bank transfer, or credit card). Payment methods can affect both churn and overall customer satisfaction.
MonthlyCharges: The monthly amount in $ USD charged to the customer. Higher charges might increase the likelihood of churn if customers perceive the cost as too high for the value provided.
TotalCharges: The cumulative amount in $ USD charged over the customer’s tenure. This helps in understanding the long-term value of each customer and can be a predictor of churn.
Churn: The target variable indicating whether the customer has left (typically denoted as “Yes” or “No”). This is the primary outcome you aim to predict with your machine learning model.


