# surfs_up

##Module 9 Notes


##Deliverable 1: Determine the Summary Statistics for June (40 points)

Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June. You’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

Follow the instructions below to complete Deliverable 1.

1.	Download the SurfsUp_Challenge_starter_code.ipynb file into your surfs_up folder, then rename it SurfsUp_Challenge.ipynb.

2.	Use the instructions below to add code where indicated by the numbered comments in the starter code file. The starter code file includes all dependencies needed for this Challenge.

3.	In Step 1, write a query that filters the date column from the Measurement table to retrieve all the temperatures for the month of June.

4.	In Step 2, convert the June temperatures to a list.
 
![image](https://user-images.githubusercontent.com/117233641/229251871-6159c6b9-1694-4628-9348-22fd1cc28dcf.png)


5.	In Step 3, create a DataFrame from the list of temperatures for the month of June.

![image](https://user-images.githubusercontent.com/117233641/229251886-abf34b50-2b6e-4965-9e01-a9836574a65f.png)


6.	In Step 4, generate the summary statistics for the June temperatures DataFrame.

 ![image](https://user-images.githubusercontent.com/117233641/229251895-71e35ac7-da28-4863-a882-7ff45d68a7a5.png)



## Deliverable 2: Determine the Summary Statistics for December (40 points)

Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of December. You’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

Follow the instructions below to complete Deliverable 2.

6.	Use the instructions below to add code where indicated by the numbered comments in your SurfsUp_Challenge.ipynb file.

7.	In Step 6, write a query that filters the date column from the Measurement table to retrieve all the temperatures for the month of December.

8.	In Step 7, convert the December temperatures to a list.

![image](https://user-images.githubusercontent.com/117233641/229251928-d0f71ba6-c6df-45c0-88fd-fe89f5a8669c.png)
 

9.	In Step 8, create a DataFrame from the list of temperatures for the month of December.

![image](https://user-images.githubusercontent.com/117233641/229251945-2ee065a2-5a4a-4e6f-b914-a7ba7c2e4dc0.png)

10.	In Step 9, generate the summary statistics for the December temperatures DataFrame.

![image](https://user-images.githubusercontent.com/117233641/229251972-40329f8c-8699-47b6-8508-40d198c186b9.png)

 

##Deliverable 3: A written report for the statistical analysis (20 points)

For this part of the Challenge, write a report that describes the key differences in weather between June and December and two recommendations for further analysis.

The analysis should contain the following:

1.	Overview of the analysis: Explain the purpose of this analysis.

##Overview

(This module is built around a project that mirrors a real-world scenario that would require data analysis and visualization)

In this module, as assigned Data Analyst, I will work with the Client/ Investor, W. Avy, on new tools such as SQLite, SQLAlchemy, and Flask to build on your knowledge of SQL database structures and querying methods. SQLite provides a quick way to setup a database engine without requiring a server. It's essentially a flat file, but with most of the major capabilities of an SQL database. 


By the end of this module, as the assigned Data Analyst I will be able to: 
      •	Explain the structures, interactions, and types of data of a provided dataset.

      •	Differentiate between SQLite and PostgreSQL databases.

      •	Use SQLAlchemy to connect to and query a SQLite database.

      •	Use statistics like minimum, maximum, and average to analyze data.

      •	Design a Flask application using data.

##Purpose

During the first sets of meetings with the Client/ an investor, W. Avy, he has expressed his concern, what about the weather. As such the Client, requested some analytics on a weather data set he has from islands.

As Data Analyst, I can compare SQLite databases to a CSV or Excel file: each SQLite database can have one or more tables with columns and rows, and it is stored as a file on your computer. The key difference between SQLite databases and a CSV or Excel file is that we can write queries for it. I will also write and execute Python code in a Jupyter notebook and create graphs using Python.



2.	Results: Provide a bulleted list with three major points from the two analysis deliverables. Use images as support where needed.

•	June Descriptive Stats Temperature and Precipitation

![image](https://user-images.githubusercontent.com/117233641/229251993-ec141424-94c7-4400-b92f-28761b1a33b1.png)


•	Visualize summary statistics of June Results.

 ![image](https://user-images.githubusercontent.com/117233641/229252018-19227863-23a4-46ce-b869-0ca4002603cf.png)


•	December Descriptive Stats Temperature and Precipitation

 ![image](https://user-images.githubusercontent.com/117233641/229252028-4066e528-e845-4862-8e32-0f859c80f672.png)

•	Visualize summary statistics of December Results.

![image](https://user-images.githubusercontent.com/117233641/229252030-fb9b0882-b0ee-430a-8402-e8f64c154183.png)

•	Comparing June to December Data the mean temperature in June is ~75 degrees where the mean temperature in December was 71 degrees.

•	The frequency of temperatures recorded in June have a normal, tight bell curve distribution. Whereas the temperatures in December, has more variation.


3.	Summary: Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.

  Recommendation:  

      •	Create additional charts where the temperature and precipitation data is graphed as a scatterplot with a trendline. 

      •	Track additional variables such as “foot traffic” around a particular location and or, perhaps wind conditions for surfing. In addition, look for correlations to data sets already collected.
