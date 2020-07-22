# PURCHASING BEHAVIOR IN A B2B ONLINE RETAILER

**_Are there any purchasing patterns in these online retailer’s UK customers based on their transactions?_**

The question above can be solved from different perspectives. For instance, this database can be analyzed taking a **product-centric approach** through the use of association rules and the Apriori algorithm in order to understand what products are usually bought together, allowing the business to offer special discounts and promotions that can increase sales in the future. Another way to analyze it is through a **customer-centric approach**, as this can provide information on patterns or special needs these customers may have; clustering may be the strategy to consider in order to get those insights relevant for the business. 

## ORDER IN WHICH THE CODE SHOULD BE RUN

1. 01_DataWrangling.Rmd
2. 02_Clustering.Rmd
3. 03_AR_Preprocessing.Rmd
4. 04_AR_Selection.Rmd
5. 05_Results.Rmd

## FINAL REPORT
Final Report.pdf

##  DATASET
[Online Retail Data Set](https://archive.ics.uci.edu/ml/datasets/Online+Retail#)

**Source:**
Dr Daqing Chen, Director: Public Analytics group. chend '@' lsbu.ac.uk, School of Engineering, London South Bank University, London SE1 0AA, UK.

**File in this Repo**
Online Retail.csv

The Online Retail dataset (available since 2015) provides information about all the transactions an online UK company has had between 2010 and 2011. It sells unique all-occasion gifts to mostly wholesalers. 

Its attributes are: 

- Invoice number

- Stock Code  

- Description of the product

- Quantity

- Invoice Date 

- Unit Price

- Customer ID

- Country

## METHODOLOGY

1. Data wrangling
2. Transformation into a RFM dataset
3. Clustering (selection of potential cluster arrangements) 
4. Each cluster group is transformed into a transactional dataset
5. The Apriori algorithm (association rules) is applied to each group
6. Selection of the best cluster arrangement based on lift
7. Results and Analysis
8. Conclusion
9. Further Considerations

