# Spark-in-R

## Using Spark in R with the sparklyr package

In this blog posted on [here](https://dhcrc.github.io/spark-in-r/) will be touching on several topics related to the usage of Spark and R as an analytical tool. 
The Medicaid data that have been made available by [HMS](https://hms.com/) and [Digital Health CRC](https://www.digitalhealthcrc.com/hms-data-sets/) and can be accessed through the RONIN platform are massive, and will most likely require the use of some form of distributed computing in order to analyze them. Spark is a natural option in terms of distributed computing. Since many DHCRC researchers are familiar with R it seems useful to discuss how R can be used to run Spark processes without having to know too much about Spark. A similar reasoning applies to Python, but since I am more familiar with R than Python I am starting with R.

[RONINR](https://ronin.cloud/) is an user-friendly web application that allows anyone to launch complex computing and storage resources on AWS while keeping tracking of spending.

The first part of this blog will focus on Spark and R, independently of the RONIN platform and the specifics of the Medicaid data, and  will show how to run Spark and R locally on a desktop/laptop for training purposes. The second part  will address the specifics of Ronin and we will see Spark in action on clusters of machines using Medicaid data.
