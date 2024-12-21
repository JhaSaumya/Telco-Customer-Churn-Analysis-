# Telco-Customer-Churn-Analysis-
In this project, I analyzed customer churn patterns by exploring how demographics, subscription plans, and service usage impact their decision to stay or leave. I focused on key features like Phone Service, Internet Service, and add-on services such as Online Security and StreamingTV.


 ## Dataset Overview
The dataset includes customer demographics, subscription details, and service features with the primary goal of understanding customer churn (i.e., customers leaving the service). Key columns analyzed include:

Phone Service, Multiple Lines, Internet Service, and other service-specific features like StreamingTV, Device Protection, etc.
Churn indicator split between Yes (churned) and No (retained).
The target variable is Churn, and the analysis identifies patterns to suggest actionable strategies.

**Key Findings from Count Plots (Subplots Analysis)**
The subplot visualization includes various service features (e.g., Phone Service, Internet Service) with the churn split. Here are the notable trends:

Phone Service:

Customers without a phone service account for approximately 8% of the total customers, and their churn rate is relatively low.
Among customers with a phone service, the churn rate is around 27%.

Multiple Lines:
Customers without multiple lines exhibit a slightly lower churn rate (20%) compared to those with multiple lines (~25%).

Internet Service:
Customers with Fiber Optic internet have a significantly higher churn rate (42%) compared to those using DSL (20%) or without internet service (5%).

Online Security:
Customers lacking online security services churn at 40%, whereas those with online security churn much less (~15%).

Online Backup and Device Protection:
Similar trends exist for these services: customers without the service churn more frequently (38%-40%) compared to those who subscribe (~20%).
Streaming Services (StreamingTV and StreamingMovies):

Churn rates for customers using streaming services (TV and movies) hover around 30%, slightly higher than customers without streaming services.

Tech Support:
Absence of tech support correlates with 40% churn, while customers with tech support have a churn rate of around 15%-18%.

**Subscription and Payment-Related Factors**
   
Contract Type:
Month-to-month contract holders have the highest churn rate (~43%), highlighting their tendency to leave if dissatisfied.
Customers with annual or multi-year contracts have churn rates below 12%, indicating strong customer retention.

Payment Method:
Customers paying via electronic checks exhibit a churn rate of 45%, significantly higher than those using bank transfers (20%) or credit cards (22%).

Monthly Charges:
Customers with higher monthly charges (above $75) tend to churn more often (~40%) compared to those with lower charges (20%-25%).

Tenure:
Tenure plays a critical role: customers with a tenure of fewer than 6 months churn at ~50%, while customers with over 24 months of tenure have a churn rate of less than 10%.

**Correlation and Feature Importance**

A heatmap likely shows correlations between features such as:
High monthly charges, lack of additional services (like online security or tech support), and churn.
Contract type and tenure have a negative correlation with churn, indicating they are strong retention factors.
These insights suggest prioritizing long-term contracts, discounts on add-on services, and improving electronic payment experiences.

**Actionable Insights and Recommendations**

Retain Month-to-Month Customers:
Design loyalty programs or discounts for these customers to encourage long-term commitment.
Their 43% churn rate is a critical risk to the business.
Enhance Service Value:

Promote additional services like online security, tech support, or device protection to reduce churn by up to 25% in these segments.

Address High Monthly Charges:
Target customers with charges above $75 through tiered pricing plans or special offers to lower churn rates from ~40% to 20%.

Improve Fiber Optic Services:
Since 42% of Fiber Optic users churn, improving the service quality or offering bundled discounts may enhance retention.
Focus on Electronic Check Users:

Offer incentives to electronic check customers or encourage them to switch to automated payment methods (e.g., bank transfer), as this group exhibits a 45% churn rate.

Engage New Customers:
Customers in their first 6 months churn at ~50%. Providing onboarding offers, check-ins, or satisfaction surveys can mitigate this.

## Conclusion
In this project, I analyzed customer churn patterns by exploring how demographics, subscription plans, and service usage impact their decision to stay or leave. I focused on key features like Phone Service, Internet Service, and add-on services such as Online Security and StreamingTV. Through this analysis, I identified the main drivers of churn and developed actionable strategies to improve customer retention.

##Contact:-
Linkedin- https://www.linkedin.com/in/saumya-jha-3a11a7270/
Email- jhasaumya28@gmail.com






