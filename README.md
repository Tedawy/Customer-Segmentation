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
 
<br>
 <h2> Resources </h2>
<hr>
* [Introduction to Customer Segmentation in Python](https://www.datacamp.com/community/tutorials/introduction-customer-segmentation-python)
* [Customer Segmentation in Python](https://learn.datacamp.com/courses/customer-segmentation-in-python)
* [RFM analysis for Customer Segmentation](https://clevertap.com/blog/rfm-analysis/)
 * [Clustering optimization in RFM analysis based on k-means](https://d1wqtxts1xzle7.cloudfront.net/63983488/20264-40355-1-PB20200721-118680-1taddep.pdf?1595348129=&response-content-disposition=inline%3B+filename%3DClustering_optimization_in_RFM_analysis.pdf&Expires=1619064235&Signature=hAGO4Ugg5aKRt3SJlFzL8ORkw~cl80AzeRrq0ZV9G9qGQOFWKZYUxc51ryKkGk~z5Ks5pOhzFEOesKvVLGC-H1CTRDAEejsx5C-cL5wX1NC83waOHvNOwspRZKr56Tw3iVauMefbyxIGtr3INpCffZlmRfRlJw8E~hfTykD~R29GYSe95WTHMTjdgE9AYes47a~ruSvD8-7BahG~HDrlJ5LNszI2g9faiC07ANLhhB47bupy7VHUXbx3bi6xnPrFuheZoKTgez84fJvEayTTqqk4WIJwjL9SzlRK9JQzd927TMxXPqfs5lkGY-BWmwAZhNVyAmo-I-N2~OEqA9CUvQ__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)
