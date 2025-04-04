# Market Basket Analysis and Customers Segmentation
## Online Retail dataset
This is a [transactional data](https://archive.ics.uci.edu/dataset/352/online+retail) set which contains all the transactions occurring between `01/12/2010` and `09/12/2011` for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

#### Additional Variable Information

* `InvoiceNo`: Invoice number. **Nominal**, a `6-digit` integral number uniquely assigned to each transaction. If this code starts with letter **`'c'`**, it indicates a **cancellation**. 
* `StockCode`: Product (item) code. Nominal, a `5-digit` integral number uniquely assigned to each distinct product.
* `Description`: Product (item) name. **Nominal**.
* `Quantity`: The quantities of each product (item) per transaction. **Numeric**.	
* `InvoiceDate`: Invoice Date and time. **Numeric**, the day and time when each transaction was generated.
* `UnitPrice`: Unit price. **Numeric**, Product price per unit in sterling.
* `CustomerID`: Customer number. **Nominal**, a `5-digit` integral number uniquely assigned to each customer.
* `Country`: Country name. **Nominal**, the name of the country where each customer resides. 

**It's worth noting that the dataset website provides some information that are not correct. For instance, the dataset does not contain variables called `InvoiceNo` and `StockCode`**.

#### Citation
D. Chen. "Online Retail," UCI Machine Learning Repository, 2015. [Online]. Available: https://doi.org/10.24432/C5BW33.
