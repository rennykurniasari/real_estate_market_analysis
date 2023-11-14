# Real Estate Market Analysis

## Business Overview
The business landscape in real estate is a multifaceted and ever-evolving domain that holds significant appeal for industry experts, investors, policymakers, and data analysts seeking a comprehensive understanding of market dynamics and customer trends to guide well-informed decision-making.

## Objective
*   **Data Preprocessing:** Systematically clean and organize real estate property data to ensure accuracy and reliability in subsequent analyses.
*   **In-Depth Analysis:** Employ advanced analytical techniques using Python to delve into the intricacies of property transactions, pricing trends, and other relevant market indicators.
*   **Visual Representation:** Utilize data visualization tools to create insightful and easily understandable representations of market trends, enabling stakeholders to grasp key information at a glance.
*   **Insight Generation:** Derive meaningful insights from the analyzed data, such as identifying emerging market patterns, understanding customer preferences, and recognizing potential investment opportunities.
*   **Profile Identification:** Develop detailed customer profiles based on transaction history and behavior, shedding light on the target demographic and informing tailored marketing and business strategies.
*   **Strategic Decision Support:** Provide actionable recommendations and insights to guide strategic decision-making for professionals, investors, and other stakeholders in the real estate business.
*   **Continuous Improvement:** Establish a framework for ongoing analysis and adaptation, ensuring that the business remains responsive to evolving market conditions and customer dynamics.

By pursuing these objectives, the Real Estate Market Analysis project aims to empower stakeholders with the knowledge and insights necessary to navigate the complexities of the real estate market and make informed, strategic decisions for long-term success.

---

## Data Dictionary
> **Properties**

|variable                       |class     |description |
|:------------------------------|:---------|:-----------|
id           |int64| unique identifier for each property
building     |int64| building type or category
date_sale    |object| date when the property was sold
type         |object| type or category of the property
property#    |int64| unique identifier for each property (property number)
area         |float64| area size of the property
price        |object| sale price of the property
status       |object| current status of the property (e.g., available, sold)
customerid   |object| unique identifier for the customer associated with the property

> **Customers**

|variable                       |class     |description |
|:------------------------------|:---------|:-----------|
customerid          |object| unique identifier for each customer
entity              |object| legal entity or individual customer
name                |object| customer's first name
surname             |object| customer's last name
birth_date          |object| date of birth of the customer
sex                 |object| gender of the customer
country             |object| country of residence for the customer
state               |object| state or region of residence for the customer
purpose             |object| purpose of the customer's engagement or interaction
deal_satisfaction   |int64| level of satisfaction with deals or transactions
mortgage            |object| mortgage information for the customer
source              |object| source of the customer's information or engagement

## Dependencies
*   `pip install pandas`
*   `pip install numpy`
*   `pip install matplotlib`
*   `pip install datetime`
*   `pip install seaborn`
