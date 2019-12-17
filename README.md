# Assignment 2

In this assignment, we will work on map reduce algorithm. We have a dataset of size 1.6 GB (compressed, and 12 GB when uncompressed), with the records of nearly 120 million records. Our goal is to use map-reduce algorithm to get the **count** of **number of flights** for each carrier.

## The Data
The data consists of flight arrival and departure details for all commercial flights within the USA, from October 1987 to April 2008. 

Each row represents an individual flight record with details of that flight in the row. The information are:
- Time and date of arrival
- Originating and destination of airports
- Amount of time for a plane from taxi to takeoff

You can find more information about this dataset in the website of [Statistical Computing](http://stat-computing.org/dataexpo/2009/).

PS: Don't get overwhelmed with the shape of the data, or the size of it, we are only interested in the number of records, and distinct number of carriers.