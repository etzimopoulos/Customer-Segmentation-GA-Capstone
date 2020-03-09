<div>
    <img src="https://bit.ly/3atCapF" style="float: left; height: 200px; padding-right:0.8em">
</div>

 # Customer Segmentation using RFM Clustering
 ## Evangelos Tzimopoulos
 
 
 #### Online Retail Business Dataset
  **General Assembly, London, Feb 2020** 


<br>




#### Business Problem 
---

In Retail and E-Commerce (B2C), but also more broadly in B2B, a key element in shaping the business strategy of the firm would be the knowledge around customer behaviour. 

More specifically the segmentation of their customers based on different business metrics: how much they spend (revenue), how often they spend (frequecy), are they new or existing customer, which ones are their favorite products, etc... which would help direct marketing, sales, account management and product teams to support better this customer and improve the product offering. 

#### Stakeholders or Interested Parties
---
This would be useful to the following teams within a firm
1. **Product/Services**
Products selling more than others, would be an opportunity to evaluate the product offering or improve specific products. 

2. **Operations/Logistics**
From stock management perspective, understanding which products are in demand would reduce storage costs and improve delivery/logistics operations

3. **Marketing**
Understanding of the customer segmenets would allow for more effective marketing of some of the products to specific segments, or perhaps with little variations depending on the segment

4. **Sales / Account Management**
Identifing which customers are the most valuable and understanding their trends would help in order to build the relationship further, retain existing customers and attract new with the correct profile



#### Goal
---
Purpose of this project is to develop a system to 

* Capture key business metrics (KPIs) measuring customer behaviour related to Transactions and Products
* Identify and group customer segments using Recency, Frequency, Monetary Value (RFM) approach

#### Data Set
---

Online Retail Data Set
http://archive.ics.uci.edu/ml/datasets/online+retail

This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.



**Key Attributes information**

| Attribute Name | Summary | Description |
|:---|:---|:---|
| **InvoiceNo** | Invoice number| Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation | 
| **StockCode** | Product (item) code | Nominal, a 5-digit integral number uniquely assigned to each distinct product |
| **Description** | Product (item) name| Nominal |
| **Quantity** | The quantities of each product (item) per transaction | Numeric |
| **InvoiceDate** | Invice Date and time | Numeric, the day and time when each transaction was generated |
| **UnitPrice** | Unit price | Numeric, Product price per unit in sterling |
| **CustomerID** | Customer number | Nominal, a 5-digit integral number uniquely assigned to each customer |
| **Country** | Country name | Nominal, the name of the country where each customer resides |





#### Key Metrics and othe KPIs
---

1. Monthly Revenue & Revenue Rate
2. Monthly Active Customer
3. Monthly Order Count
4. Average Revenue Per order
5. Monthly Order average
6. Revenue per month for New and Existing customers
7. New Customer Ratio


#### Project Planning & Key Milestones
---

| Milestones | Weeks | Sprints | Key Tasks | Dates |
|:---|:---|:---|:---|:---|
| Proposal Draft | 1-2 | 1 | 1. Research on various project themes<br>2. Project Summary<br>3. Goals and Objectives<br>4. Dataset summary | 6th Jan - 17th Jan |
| Initial Project Brief | 3-4 | 2 | 1. Initial analysis & next steps<br>2. Basic EDA and visualizations<br>3. Understanding key metrics and features | 20th Jan - 31st Jan |
| Initial Findings | 5-6 | 3 | 1. Data processing<br>2. Full EDA & Feature selection<br>3. Core Data Science modelling, validation and testing | 3rd Feb - 14th Feb |
| Final Findings | 7 | 4 | 1. Final parameter tuning and model selection<br>2. Tidying up code and reports<br>3. Technical Notebook submission | 17th Feb - 21st Feb |
| Presentation | 8 | 4 | 1. Presentation write up and Submission | 24th Feb - 26th Feb |
