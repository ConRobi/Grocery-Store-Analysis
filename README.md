# Grocery-Store-Analysis

Author: Connor Robinson
Date: December 2025

This analysis uses a dataset from OM 420 (University of Alberta). The dataset is from a Canadian grocery store. 

Cleaning the Data
When querying the data in SQL, I inner-joined the important tables together to remove missing data. Additionally, I omitted transaction rows from subdepartments 6 and 7 because “Ecology Charges” and “Bottle Deposits” took up a significant amount of the data but didn’t provide any valuable information. When it comes to missing customer data, I omit transaction rows related to customers with no gender or age listed. 
The queries used to create the csv files needed for visuals in Power BI are saved as views in the database. 

Interesting Findings
* Some of the most notable findings are:
* The grocery department has the most transactions with most of these transactions not having specific subdepartments to categorize them (only the grocery subdepartment). 
* Most transactions were done in May, with May 1st being an outlier in the dataset because it has the most transactions. 
* Fresh cut flowers were the most profitable items purchased.
* Female customers who are 30 or older made up most of the transactions in the dataset.
* For females, the amount of transactions varied based on the age range, but for males, the amount of transactions were similar.

<img width="1310" height="473" alt="image" src="https://github.com/user-attachments/assets/f279d067-aa1d-47e5-8b72-ef15d42ba912" />
<img width="1315" height="633" alt="image" src="https://github.com/user-attachments/assets/d16758e6-7006-4118-b987-d226d0d89cfa" />
<img width="1274" height="683" alt="image" src="https://github.com/user-attachments/assets/509d4054-9207-44ce-ba7e-0ff52c591221" />
<img width="1235" height="634" alt="image" src="https://github.com/user-attachments/assets/a59efd99-640e-4e80-97d2-39f8cfbd00c0" />
