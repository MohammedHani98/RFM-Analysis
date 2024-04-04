# RFM-Analysis

<span style="display:block;text-align:center"><img src="https://github.com/MohammedHani98/RFM-Analysis/blob/main/RFM_Logo.png?raw=true" style="width:600px;height:500px;" alt="RFM"></span>

## Objective

Based on the dataset in hand, we aim to perform RFM (Recency, Frequeny, and Monetary Value) analysis on the data to be able to segment the customers based on their purchasing pattern and behavior.

## About the dataset

**Online Retail II** is a dataset provided by <a href = "https://archive.ics.uci.edu/dataset/502/online+retail+ii">UCI Machine Learning Repository</a>. The dataset can be described as:

*'A transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.'*

#### Variables Description
**InvoiceNo**: A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation.

**StockCode**: A 5-digit integral number uniquely assigned to each distinct product.

**Description**: Product (item) name.

**Quantity**: The quantities of each product (item) per transaction.

**InvoiceDate**: The day and time when a transaction was generated.

**UnitPrice**: Product price per unit in sterling (Â£).

**CustomerID**: A 5-digit integral number uniquely assigned to each customer.

**Country**: The name of the country where a customer resides. (Nominal)

| Variable | datatype |
|----------|----------|
| InvoiceNo | Nominal |
| StockCode | Nominal |
| Description | Text |
| Quantity | Integer |
| InvoiceDate | Timestamp |
| UnitPrice | Float |
| CustomerID | Nominal |
| Country | Nominal |

## Methodology

- **Cacluclating the RFM values:** Group the customers and determine the RFM values for each customer
- **Segmentation:** Based on the RFM values calculated, we will segment customers into multiple categories
- **Targeting:** Devise different strategies to better target each segment determined
