# E-commerce Market & Segmentation
This project demonstrates an end-to-end customer segmentation and retention strategy built on transactional data. The objective is to identify high-value and high-risk customer segments, quantify churn risk, and support data-driven retention decisions through interpretable models, deployment, and monitoring.

## Dataset

### Dataset Source: [Online Retail II](https://archive-beta.ics.uci.edu/dataset/502/online+retail+ii)

This Online Retail II data set contains all the transactions occurring for a UK-based and registered, non-store online retail between 01/12/2009 and 09/12/2011.The company mainly sells unique all-occasion gift-ware. Many customers of the company are wholesalers.


The dataset contains 1067371 entries and has 8 columns.

### Columns Description: 

- Invoice   : Invoice number. A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation.
- StockCode : Product (item) code.  A 5-digit integral number uniquely assigned to each distinct product.
- Description   : Product (item) name. 
- Quantity  : The quantities of each product (item) per transaction. 
- InvoiceDate   : Invoice date and time. The day and time when a transaction was generated.
- Price : Unit price.  Product price per unit in sterling (£).
- CustomerID    : Customer number. A 5-digit integral number uniquely assigned to each customer.
- Country   : Country name. The name of the country where a customer resides.

## EDA of the dataset

all the python analysis of the dataset are include in [here](https://github.com/Ensya/E-commerce-Market-Basket---Segmentation/blob/main/customer-segmentation-retention-analysis.ipynb)

## Conclusion 

The business is totally depended on top most best customers and it is failing to convert the 75% of other tier customers and that is resulting in more than 50 % churn rate. The actual problem is the conversion rate and not retention. In order to recover below Four strategic initiatives are recommended.

- Make the top most best customers happy by VIP programs.
- Recover the dormant customer who was previously the top most best customers through win-back campaigns
- Fix conversion pipeline for Best/Good customers
- Implement visibility system to predict churn
- We shall explore the churn prediction model in the next notebook.
