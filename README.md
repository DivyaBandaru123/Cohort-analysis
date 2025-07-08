# Cohort Analysis on Online Retail Data
This project performs a Cohort Analysis on transactional data from an online retail store using Python (Pandas, Matplotlib, Seaborn). The objective is to analyze customer retention trends over time based on their first purchase month.

📂 Dataset:

The dataset used is a transactional Excel file (Online Retail.xlsx) containing records of purchases from an online store. It includes fields such as:

1.InvoiceDate

2.CustomerID

3.InvoiceNo

4.Quantity

5.UnitPrice

6.Country

🔧 Tools & Libraries:

Python: pandas, matplotlib, seaborn, datetime

Jupyter Notebook for exploration and visualization

📊 Analysis Workflow:

1.Data Preprocessing: 

a. Loaded and explored the dataset

b. Removed transactions with missing CustomerID

c. Created a new column InvoiceMonth to group by transaction month

2.Cohort Identification:

a. Assigned a cohort month to each customer (month of first purchase)

b. Calculated a cohort index to represent months since acquisition

3.Customer Grouping:

a. Grouped data by cohort month and cohort index

b. Counted unique customers to track retention over time

4.Visualization:

a. Created a retention matrix showing customer counts using a heatmap

b. Built a percentage-based cohort heatmap to normalize retention behavior

c. Used Blues and coolwarm colormaps to visually distinguish trends
