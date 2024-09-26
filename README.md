# Maximizing-Customer-Loyalty-and-CLV-through-Data-Driven-Strategies

## Business Overview 
A mobile network operator, offering a variety of services including voice, data, and digital content, has been experiencing increasing customer churn rates over the past year. With fierce competition in the wireless communications industry and the high costs associated with customer acquisition, reducing churn has become critical for maintaining profitability and market share. Customer churn, defined as the rate at which users leave or cancel their mobile services, has been steadily rising, leading to concerns about customer loyalty and overall revenue retention.

The leadership team has tasked the data analytics team with uncovering the key factors driving customer churn and proposing actionable solutions to reduce it. A successful churn reduction strategy could potentially save millions of dollars in lost revenue and improve customer lifetime value (CLV).

## Project Overview
This project addresses the following critical business problems:
1. Increasing Customer Churn Rates
2. Ineffective Pricing Strategies
3. Low Customer Engagement and Loyalty

To tackle these business challenges, conducted an **exploratory data analysis** (EDA) using **Python** on a dataset of over 7,000 customer records, analyzing various features such as customer demographics, service usage, account details, and churn status. 

* Data Cleaning and Preparation: Using **Pandas**, cleaned the dataset by handling missing values, removing duplicates, and converting categorical variables into numerical formats for analysis.

* Descriptive Statistics: Employed **NumPy** to calculate key metrics and descriptive statistics, providing insights into customer demographics, churn rates, and service usage patterns.

* Visualization: Utilized **Matplotlib** and **Seaborn** for visualizing data distributions and relationships, helping to identify trends and patterns associated with customer churn.

* Correlation Analysis: By analyzing correlations between various features and churn status, pinpointed critical factors influencing customer retention, such as contract types, payment methods, and service engagement.

* Actionable Insights: Based on the analysis, we developed targeted strategies to improve customer loyalty, such as promoting long-term contracts, enhancing pricing models, and optimizing service offerings.

## Data Overview
The dataset provided for analysis contains 7,043 records representing individual customers, with 21 features, including:
1. Customer Demographics: Age, gender, and whether they are senior citizens.
2. Service Usage: Type of mobile plan (e.g., voice, data), subscription to additional services (e.g., mobile data, international calling, or device insurance).
3. Account Details: Contract type (e.g., month-to-month, annual), tenure (i.e., how long they’ve been with the company), billing preferences, and total monthly charges.
4. Churn Status: A binary variable indicating whether the customer has canceled their service.

## Analysis and Insights

Percentage of Churned Customers :

(Image)

The pie chart shows that the churn rate is relatively low, but even a small percentage of lost customers can impact profits significantly.

Next, investigating the relationship between contract types and customer churn.

(Image)

This graph reveals that customers with month-to-month contracts were more likely to churn than those with annual contracts. This highlights the importance of building long-term customer relationships.

Exploring the impact of tenure (how long they've been a customer) and monthly charges on churn :

(Image)

The box plots indicate that customers with shorter tenures and higher monthly charges are at greater risk of churn.

Investigating the impact of multiple other services usage on churn :

(Image)

The countplots revealed that some services, such as online security and tech support, were linked to lower churn rates.

Impact of payment methods on churn :

(Image)

### Analysis Outcome : 
1. Contract Type:
* Month-to-Month Contracts: Churn Rate = 42.7%
* One-Year Contracts: Churn Rate = 11.3%
* Two-Year Contracts: Churn Rate = 3%

**Insight:** Flexibility in contracts correlates with higher churn, indicating a need for longer-term commitments to enhance retention.

2. Tenure and Monthly Charges:
* Shorter Tenures (< 1 Year): Higher churn likelihood.
* Monthly Charges: Customers with premium rates (e.g., $80+) show increased churn, with those perceiving unfavorable pricing more likely to leave.

**Insight:** Newer customers and those facing high costs are at greater risk of churn.

3. Payment Method:
* Electronic Check Payments: Higher churn rate observed with cheque payemnts, significantly above credit card and automatic payments.

**Insight:** Manual billing processes may contribute to customer dissatisfaction.

4. Additional Services:
* Lack of Value-Added Services: Customers without add-ons (e.g., mobile data, device insurance) exhibit higher churn rates.

**Insight:** Engaging customers with supplementary services can reduce churn and enhance loyalty.

## Conclusion and Business Insights
Our analysis identified several key areas where improvements could reduce customer churn:

Contract Type: The majority of customers who churn are on month-to-month contracts. Encouraging customers to shift to longer-term contracts (e.g., one or two years) could significantly improve retention rates.
Pricing Sensitivity: Higher monthly charges correlate with a higher risk of churn. Developing more competitive pricing options or value-based bundles could help retain high-paying customers.
Billing Preferences: Customers using manual payment methods like electronic checks show a higher churn rate, indicating potential friction in the payment process.
Additional Services: The absence of optional services like device insurance and mobile data packages is associated with churn, suggesting that bundling these services might help retain customers.
Recommendations
Based on the analysis, I recommend the following targeted strategies to reduce churn:

Promote Long-Term Contracts:

Offer incentives for customers on month-to-month plans to switch to one-year or two-year contracts. Incentives could include discounted pricing, loyalty rewards, or enhanced service bundles. By doing so, the company could reduce the churn rate by 27.4% for this group.
Revise Pricing Strategy:

Implement a tiered pricing model that offers better value for high-paying customers. For example, offering bundled packages with services such as international calling or device insurance could make the premium price feel more justified. A revised pricing model could help reduce churn by 20% in customers with higher-than-average monthly bills.
Enhance Customer Support for New Users:

Newer customers tend to churn at higher rates, often because they haven’t fully adapted to the service or encountered issues. Improve the onboarding process with personalized communications, tutorials, and welcome offers. Addressing the concerns of these customers could reduce churn by 10-15%.
Offer Easier Payment Options:

Investigate why electronic check users are churning at higher rates and consider introducing more convenient payment options like digital wallets or auto-pay services. Reducing friction in billing processes will help retain customers and increase satisfaction.
Upsell and Bundle Services:

Create personalized upselling campaigns that encourage customers to subscribe to value-added services such as mobile data, premium streaming options, or device protection plans. This will not only boost revenue but also increase the stickiness of the service. Offering competitive bundles could reduce churn by increasing the perceived value of staying with the company.
Conclusion
By taking a data-driven approach to understanding customer churn, the mobile network operator can implement highly targeted strategies to retain at-risk customers. Offering longer-term contracts, adjusting pricing strategies, improving customer onboarding, and addressing payment preferences are key steps to reducing churn and improving customer lifetime value. If successfully executed, these strategies could significantly lower the churn rate, increase customer satisfaction, and protect the company's bottom line in a highly competitive market.



