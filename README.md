#Gett Order Failure & Cancellation Analysis;
 This project analyses failed ride orders from Gett to identify key reasons behind cancellations and system rejections using Python and Pandas. It examines how driver assignment, time of day, and ETA influence order failures to enhance operational efficiency.
Gett Order Failure & Cancellation Analysis Project Overview
This project analyses failed ride orders from a ride-hailing company (Gett) to understand why orders are cancelled or rejected. Failed orders directly impact revenue, customer satisfaction, and operational efficiency. The objective of this analysis is to identify when, why, and under what conditions ride orders fail and to derive actionable business insights.

Business Problem
1.	Gett faces a significant number of failed ride orders due to:
2.	Customer cancellations
3.	System rejections
4.	Orders failing before a driver is assigned
5.	These failures may be caused by long waiting times, high ETAs, driver shortages, or peak-hour demand.
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

Analysis Performed

The project follows a structured analytical workflow:
1.	Data understanding and quality checks
2.	Merging orders and offers datasets
3.	Cleaning and renaming coded columns
4.	Distribution analysis of failed orders
5.	Hourly trend analysis of failures
6.	Average time to cancellation analysis
7.	ETA analysis by hour
Key Insights
1.	Most failed orders occur before a driver is assigned, indicating supply shortages.
2.	Order failures peak during high-demand evening hours.
3.	Customers wait longer before cancelling when a driver is assigned, showing higher trust.
4.	Higher ETA strongly correlates with increased cancellations.
5.	A significant number of orders never receive any driver offers.
 Business Recommendations
1.	Increase driver availability during peak demand hours.
2.	Reduce ETA through improved driver matching and dynamic pricing.
3.	Monitor high-cancellation hours to proactively manage supply.
4.	Improve early-stage order handling to reduce pre-assignment cancellations
Conclusion
This project demonstrates how operational data can be transformed into meaningful business insights. By analysing cancellation behaviour, driver assignment patterns, and ETA trends, the analysis highlights key areas where Gett can improve efficiency, reduce failed orders, and enhance customer experience.
