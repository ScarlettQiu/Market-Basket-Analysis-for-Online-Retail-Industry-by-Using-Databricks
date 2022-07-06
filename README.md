# Market-Basket-Analysis-for-Online-Retail-Industry-by-Using-Databricks  

In this project, we created a Manual with instructions of doing data analysis, especially the Market Basket Analysis by using Apriori Algorithm for retail companies. The purpose of this report is to help analysts who have no experience using the big data management tool – Databricks to understand how to use it to tackle the real big data. 

We provided the steps from registering the Databrick Community Edition, creating a cluster and a notebook, to writing commands in Notebook and export the final Notebook. Also, we provided instructions on how to collaborate with team members by using Community Edition. 

Moreover, we have used a dataset of an online retail company to do the analysis and Market Basket analysis. We also provided the insights and findings from our analysis.

At the end of the report, we analyzed the pros and cons of using Databricks to manage big data and the challenges we met through the whole process. The programming languages used in our analysis involve Python and SQL.

#### Dataset Source and Introduction

The dataset we use is from Kaggle (Cagirici, n.d.). According to Cagirici, (n.d.), the dataset is from a UK-based online sales store which contains the transaction data from January 12, 2009, to September 12, 2011. 

https://www.kaggle.com/datasets/ozlemilgun/online-retail-dataset?resource=download 

There are 2 sheets in the original dataset. After merging the 2 sheets, there are 1,067,371 rows/observations and 8 columns/variables in the dataset. 





#### Information about Variables  

1	<b>Invoice</b>	The invoice number made by a customer; those starts with “C” are the canceled transactions. 	Categorical   
2	<b>Stock Code</b>	Unique product code for each product	Categorical   
3	<b>Description</b>	Product name	Categorical   
4	<b>Quantity</b>	Number of products sold in each transaction	Numeric: discrete  
5	<b>Invoice Date</b>	The date of invoices happened	Date & Time  
6	<b>Price</b>	The price of the product	Numeric: continuous  
7	<b>Customer ID</b>	Unique customer ID for each customer; customers who do not register will have not customer ID	Categorical   
8	<b>Country</b> 	The customers’ location	Categorical   

#### A real-world problem  

A real-word problem we aim to solve in this analysis is how to create a better product bundle sales strategy for online retail companies. 
