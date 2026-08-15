# webRestaurant
Note that the jmeter script needs to be run on java version 17.
Ran the test and controlled the throughput (5 RPM for 15 mins) using "Constant Throughput Timer"
The metrics from the "Aggregate Report" gives you the Throughput and 90th percentile response times for product page and Outlet page
---
Basically i captured all the products in the Outlet HTML response using the "Regular Expression Extractor" and name of the variable is "PRODUCTS"   
then , in the JSR Post Processor, created a list and randomised in it
passed the random list using "ForEach Controller"



