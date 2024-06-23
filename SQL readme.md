# Zuber Rideshare 

## Description
Understand passenger preferences and the impact of external factors on rides.
Working with a database, analyze data from competitors and test a hypothesis about the impact of weather on ride frequency. 

## Introduction
The task is to find patterns in the available information. You want to understand passenger preferences and the impact of external factors on rides.

## Main Body

https://www.loom.com/share/912929e450da412dbfe5f0e3410b0883?sid=75cf91bb-0875-41c8-9a0a-2120efa70af6

1.Print the company_name field. Find the number of taxi rides for each taxi company for November 15-16, 2017, name the resulting field trips_amount and print it, too. Sort the results by the trips_amount field in descending order.

2.Find the number of rides for every taxi companies whose name contains the words "Yellow" or "Blue" for November 1-7, 2017. Name the resulting variable trips_amount. Group the results by the company_name field.

3.For November 1-7, 2017, the most popular taxi companies were Flash Cab and Taxi Affiliation Services. Find the number of rides for these two companies and name the resulting variable trips_amount. Join the rides for all other companies in the group "Other." Group the data by taxi company names. Name the field with taxi company names company. Sort the result in descending order by trips_amount.

4.Retrieve the identifiers of the O'Hare and Loop neighborhoods  from the neighborhoods table.

5.For each hour, retrieve the weather condition records from the weather_records table. Using the CASE operator, break all hours into two groups: Bad if the description field contains the words rain or storm, and Good for others. Name the resulting field weather_conditions. The final table must include two fields: date and hour (ts) and weather_conditions.

6.Retrieve from the trips table all the rides that started in the Loop (pickup_location_id: 50) on a Saturday and ended at O'Hare (dropoff_location_id: 63). Get the weather conditions for each ride. Use the method you applied in the previous task. Also, retrieve the duration of each ride. Ignore rides for which data on weather conditions is not available.


## Conclusion
Out of all the companies in the database, on November 15-16 2017 Flash Cab had the highest amount of trips available.
For November 1-7 2017 Flash Cab and Taxi Affiliation Services were the most popular rides.
Most rides are taken when weather conditions are good.
