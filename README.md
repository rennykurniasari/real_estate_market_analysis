# Real Estate Market Analysis

## Business Overview
The real estate market is a multifaceted and dynamic sector of significant interest to professionals, investors, policymakers, and data analysts. A thorough understanding of market conditions and customer behavior is crucial for making informed decisions. In this Real Estate Market Analysis project, our client, a leading company in the industry, has gathered data on properties and customers, seeking insights and assistance in real estate analysis.

## Business Objective
1.   **Customer Profile**
<br>Develop an ideal customer profile, considering age and other characteristics, to facilitate targeted marketing efforts.

2.  **Building Characteristics:**
<br>Analyze building types and their characteristics to inform strategic decisions for real estate developers.

3.   **Sales by Country**
<br>Examine geographical data to understand the distribution of sales and identify key markets.

4.  **Total Number of Sales per Year**
<br>Visualize sales trends over the years to comprehend historical patterns and inform future strategies.

## Business Impact
The analysis aims to provide actionable insights for real estate owners, developers, and industry professionals, impacting marketing strategies, investment decisions, and customer targeting.

---

## Project Highlights
1.   **Customer Profile Insights**
<br>Understand the age distribution of customers, aiding in the creation of targeted marketing strategies.

2.   **Building Characteristics Analysis**
<br>Identify popular building types, average prices, and deal satisfaction to inform real estate development strategies.

3.   **Geographical Distribution**
<br>Analyze sales by country, revealing key markets and opportunities.

4.   **Temporal Analysis**
<br>Explore total sales per year, identifying trends and market fluctuations.

5.   **Data Visualization**
<br>Utilize charts and tables for effective communication of key findings.

## Methodology
The project involves preprocessing, analyzing, and visualizing real estate property data to derive meaningful insights. Techniques include customer segmentation, building type analysis, geographical distribution analysis, and temporal trends assessment.

## Key Components
1.   **Data Cleaning and Preprocessing**
<br>Ensure data quality and relevance for subsequent analysis through meticulous cleaning and preprocessing.

2.   **Statistics**
    *   **Breakdowns by Building:** Explore building-related statistics to understand their characteristics and market trends.
    *   **Breakdowns by Country and State:** Analyze sales distribution across countries and states to identify key markets.

3.   **Data Analysis**
    *   **Customers Age:** Analyze the age distribution of customers to understand demographic trends.
    *   **Analysis of the Price of Properties:** Explore property prices and identify patterns or anomalies.
    *   **Relationship Between Age and Price:** Examine the correlation between customer age and property prices.

4.   **Data Visualization**
    *   **Deal Satisfaction Across Countries:** Visualize deal satisfaction levels across different countries.
    *   **Customer Age Distribution:** Present a graphical representation of the age distribution of customers.
    *   **Segmentation by State:** Explore customer segmentation based on states.
    *   **Total Sales per Year:** Visualize the total number of sales per year to identify trends.
    *   **Yearly Sales Distribution Across Buildings:** Examine the distribution of sales across different building types each year.

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

---

## Result Interpretation

