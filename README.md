# Churn-rate-analysis
Customer Churn Analysis
Overview
This analysis investigates the relationship between various customer attributes and churn in the customer churn dataset. We performed chi-square tests to determine the association between categorical variables and churn, as well as correlation analysis between numerical variables and churn.

Chi-Square Test Results
The chi-square test results show the p-values for the association between various categorical variables and customer churn:

PhoneService (p = 0.175)
Contract (p = 0.201)
MultipleLines (p = 0.384)
DeviceProtection (p = 0.404)
Partner (p = 0.453)
TechSupport (p = 0.470)
Gender (p = 0.546)
OnlineBackup (p = 0.650)
StreamingMovies (p = 0.683)
StreamingTV (p = 0.841)
OnlineSecurity (p = 0.854)
PaymentMethod (p = 0.895)
InternetService (p = 0.906)
Dependents (p = 0.957)
PaperlessBilling (p = 0.994)
Key Takeaway
None of the p-values are below the 0.05 significance level, indicating that none of the tested categorical variables show a statistically significant association with churn. This suggests that individually, these variables do not strongly impact customer churn.

Correlation Analysis Results
The correlation coefficients measure the linear relationship between Churn and several numerical variables:

SeniorCitizen (-0.0047)
Tenure (0.0086)
MonthlyCharges (0.0150)
TotalCharges (0.0143)
Key Takeaway
The correlation coefficients between Churn and the numerical variables are all very close to zero, indicating almost no linear relationship between these variables and churn.

Conclusion
Based on the chi-square test results and correlation analysis:

Categorical Variables: The lack of significant p-values indicates that none of the tested categorical variables have a strong individual impact on churn.
Numerical Variables: The very weak correlation coefficients suggest that the tested numerical variables do not have a strong linear relationship with churn.
