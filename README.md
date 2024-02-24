# meriskill_Internship-sales-analysis

### PROJECTOVERVIEW
This data analysis aims to provide insights into the sales performance of an e-commerce company over the past yearBy analyzing various asppects of the sales data,we seek to identify trends,make dat deriven recommendation,and gain a deeper understanding of the commpan,s preformance.

### DATA SOURCE
sales Data:The primary dataset used for this analysis is "SALES_DATA_CSV"FILE,containg detailed information about each sale made by the company."

### DATA DESCRIPTION
Column description for sales data analysis:
- Order_id
- Product
- Quantity_ordered
- Price_each
- Order_date
- Purchase_address
- Month
- Sales
- City
- Hour
- 
### TOOLS
# POWER BI FOR
- DATA CLEANING
- DATA ANALYSIS
- CREATING VISSUALS AND REPORTS

[DOWNLOAD HERE](HTTP://MICROSOFT.COM)


### DATA CLEANING/PREPARATION
## step1
In the intial data preparationphase,i performed the following after i downloaded the dataset using the "Get Data" option in Power BI
- Data loading and inspection

## step2
- Data cleaning and formatting
  The column headers are identified in the first row and should be kept as headers by the following steps below.
  

  ## steps 3
  After promoting the headers,navigate to the transform tab and select 'Deetect Data Type'.This action will automatically identify the data type of ech column and convert them as needed.


  ## step 4

  split the datetime into date and time stamp
  - the aforementioned process starts with selecting the desired column.following the selection,the option to split the column becomes visible
  - choose the split column option and select space as the delimeter
  - upon completing the data transformation ,click on close &apply located at the top left
  - remeber,this step is crucial after any data transformation process.

 ### Exploratory Data Analysis

EDA involves exploring the sakes data to answer key questions,such as:
- what is the overall sales trend?
- which product are top sellers?
- what are the peak sales period?

### Data Analysis
 I calculated for all the revenue metrics as follows
 - total cost =sum [price each]
 - total sale =sum[sales]
 -  profit=total sales -total cost
 -  total profit=sum[profit]
 -  profit margin= [(total sales-total cost)/total sales*100]



### VISUALIZATION OF DATA
# step1
Sales trend over time using line chart
- simply click on the month name and sales column,drag it to the desired position
# step2
best selling product using tree map
# step3
top 5 best selling product using stacked bar chart
# step4
top 5 citiec by sales using map
# step5 
weekly sales distibution by weekday using column chart
# step6
slicer 
### DASHBOARD


