#Gett Order Failure & Cancellation Analysis;
 This project analyses failed ride orders from Gett to identify key reasons behind cancellations and system rejections using Python and Pandas. It examines how driver assignment, time of day, and ETA influence order failures to enhance operational efficiency.
Gett Order Failure & Cancellation Analysis Project Overview
This project analyses failed ride orders from a ride-hailing company (Gett) to understand why orders are cancelled or rejected. Failed orders directly impact revenue, customer satisfaction, and operational efficiency. The objective of this analysis is to identify when, why, and under what conditions ride orders fail and to derive actionable business insights.

Business Problem
1.	Gett faces a significant number of failed ride orders due to:
2.	Customer cancellations
3.	System rejections
4.	Orders failing before a driver is assigned
5.	Long waiting times, high ETAs, driver shortages, or peak-hour demand may cause these failures.
   
This project answers the following key questions:
1.	Why do orders fail?
2.	When do failures occur most frequently?
3.	How long do customers wait before cancelling?
4.	Does ETA influence cancellation behaviour?

 Data Used

Two datasets are used in this analysis:
1.	data_orders.csv
2.	Order time
The datasets are merged using order_gk to create a unified view of each order and its driver offers.
Tools & Technologies
1.	Python
2.	Pandas
3.	NumPy
4.	Matplotlib
5.	Jupyter Notebook

