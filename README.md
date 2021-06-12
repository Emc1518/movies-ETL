# Movies - ETL 

##  Overview

The purpose of this analysis is to pull data from multiple sources, remove unnecessary data and store the data into a database. 

## Results

#### Step 1: Extract the Data

The first step in the process is to read and gather the data from the two sources, (movies_metadata.csv and wikipedia-movies.json) using Python.

#### Step 2: Transform the Data

The following step is to transform the data by using an iterative process to continously inspect the data and remove any unnecessary information until you have a code that is the most efficient. 

#### Step 3: Load the Data

The last step in the process is the load the transformed data into PostgreSQL where it will be stored and can be delivered to the client.


## Summary

The process of Extracting, Transforming and Loading large amounts of data from many sources is a long process that requires close inspection of the data to determine what information is not needed. It is important to plan cleaning strategies before actually implementing them to ensure that the data is as clean as possible. 
