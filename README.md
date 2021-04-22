# **Customer Segmentation**
<br>
 <h2> Dataset description and source </h2>
 <hr>   
The dataset used in this demonstration can be found in the UCI machine learning repository and it can be accessed via <a href = 'http://archive.ics.uci.edu/ml/datasets/Online+Retail'>this link</a>.
<br><br>

<b>Dataset Information: </b><br>
This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.
<br>

<b>Attribute Information: </b><br>
It contains 8 attributes which are fully described below:

- InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c',it indicates a cancellation.  
- StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.  
- Description: Product (item) name. Nominal.  
- Quantity: The quantities of each product (item) per transaction. Numeric.  
- InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.  
- UnitPrice: Unit price. Numeric, Product price per unit in sterling.  
- CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.  
- Country: Country name. Nominal, the name of the country where each customer resides.

<br>
 <h2> Flow of the project </h2>
 <hr>
 In this demonstration, we are going to process and analyze a dataset for a non-store online retail. The complete details of each step is provided inside the notebook. The summary of this project is as follows:
 
 **1. Data Understanding:** useful as a preliminary step to capture basic data property. Distribution analysis, statistical exploration, suitable transformation of variables and elimination of redundant variables, management of missing values. 
 
 **2. Perform RFM Segmentation:** The first step is to build an RFM model to assign Recency, Frequency and Monetary values to each customer. 
 
 **3. Customer segmentation with k-means:** The second step is to divide the customer list into tiered groups for each of the three dimensions (R, F and M), using clustering using K-means 
 

