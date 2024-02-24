# meriskill_Internship-sales-analysis

### PROJECT OVERVIEW
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

  # BEFORE PROMOTING HEADER
![MERISALES1](https://github.com/asogwachinenye1/meriskill-sales-analysis/assets/161091047/a90afe8f-7fa6-407d-bfb4-ef80a7b4baab)
# AFTER PROMOTING HEADER
![MERSALES2](https://github.com/asogwachinenye1/meriskill-sales-analysis/assets/161091047/9caa70f9-9c94-4ff3-9b8e-263044e46add)


 ## steps 3
  After promoting the headers,navigate to the transform tab and select 'Deetect Data Type'.This action will automatically identify the data type of ech column and convert them as needed.

![MERISALES3](https://github.com/asogwachinenye1/meriskill-sales-analysis/assets/161091047/a69bd191-46f6-4a87-b52a-1429d26efbcc)

## step 4
 split the datetime into date and time stamp
  - the aforementioned process starts with selecting the desired column.following the selection,the option to split the column becomes visible
  - choose the split column option and select space as the delimeter
  - upon completing the data transformation ,click on close &apply located at the top left
  - remeber,this step is crucial after any data transformation process.

# BEFORE SPLITING
![MERISALES4](https://github.com/asogwachinenye1/meriskill-sales-analysis/assets/161091047/327352de-7820-44d3-bd03-afd1a2b022f3)

# SPLITING WITH SPACE DELIMETER
![MERISALES6](https://github.com/asogwachinenye1/meriskill-sales-analysis/assets/161091047/cf0d4f4c-44bc-4905-879d-b4bc555bc44c)
# AFTER SPLITING
![MERISALES5](https://github.com/asogwachinenye1/meriskill-sales-analysis/assets/161091047/200f6c1f-f296-4e5c-a6f0-bdd70bda9f15)
# CLOSING & APPLYING
 ![MERISALE7](https://github.com/asogwachinenye1/meriskill-sales-analysis/assets/161091047/26429d0b-3575-4a07-8d5c-e4d612649cc5)

 ### EXPLORATORY DATA ANALYSIS

EDA involves exploring the sakes data to answer key questions,such as:
- what is the overall sales trend?
- which product are top sellers?
- what are the peak sales period?

### DATA ANALYSIS
 I calculated for all the revenue metrics as follows
 - total cost =sum [price each]
 - total sale =sum[sales]
 -  profit=total sales -total cost
 -  total profit=sum[profit]
 -  profit margin= [(total sales-total cost)/total sales*100]
 -  total quantity=sum[quantity]

![MERISALES13](https://github.com/asogwachinenye1/meriskill-sales-analysis/assets/161091047/28742ae6-52f9-43de-b838-72b614c2666b)


### VISUALIZATION OF DATA
# step1
Sales trend over time using line chart
- simply click on the month name and sales column,drag it to the desired position
  ![MERISALES11](https://github.com/asogwachinenye1/meriskill-sales-analysis/assets/161091047/19e3ac73-becb-4a4f-bc33-ddc8946207c4)

# step2
best selling product using tree map
![MERISALES8](https://github.com/asogwachinenye1/meriskill-sales-analysis/assets/161091047/dc107b94-0dfc-4108-a913-650b6a3e1a6d)

# step3
top 5 best selling product using stacked bar chart
![MERISALES12](https://github.com/asogwachinenye1/meriskill-sales-analysis/assets/161091047/b2daae6a-42c5-4048-8b00-8a69439894b0)

# step4
top 5 citiec by sales using map
![MERISALES9](https://github.com/asogwachinenye1/meriskill-sales-analysis/assets/161091047/22d955d0-2e49-4d3a-ba14-c2c6f0992028)

# step5 
weekly sales distibution by weekday using column chart
![MERISALES10](https://github.com/asogwachinenye1/meriskill-sales-analysis/assets/161091047/b500439e-62e2-4e35-9d72-33bdc918cb95)

# step6
slicer 
![MERISALES14](https://github.com/asogwachinenye1/meriskill-sales-analysis/assets/161091047/cc2425e9-7669-4ef7-9be6-dcec3dff70c5)

### DASHBOARD


