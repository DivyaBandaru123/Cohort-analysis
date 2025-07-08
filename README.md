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

Data Preprocessing: 
Loaded and explored the dataset
Removed transactions with missing CustomerID
Created a new column InvoiceMonth to group by transaction month

Cohort Identification:

Assigned a cohort month to each customer (month of first purchase)

Calculated a cohort index to represent months since acquisition

Customer Grouping:

Grouped data by cohort month and cohort index

Counted unique customers to track retention over time

Visualization:

Created a retention matrix showing customer counts using a heatmap

Built a percentage-based cohort heatmap to normalize retention behavior

Used Blues and coolwarm colormaps to visually distinguish trends
