# Zuber Rideshare 

## Description
Understand passenger preferences and the impact of external factors on rides.
Working with a database, analyze data from competitors and test a hypothesis about the impact of weather on ride frequency. 

## Introduction
The task is to find patterns in the available information. You want to understand passenger preferences and the impact of external factors on rides.

## Main Body

https://www.loom.com/share/912929e450da412dbfe5f0e3410b0883?sid=75cf91bb-0875-41c8-9a0a-2120efa70af6

1.Print the company_name field. Find the number of taxi rides for each taxi company for November 15-16, 2017, name the resulting field trips_amount and print it, too. Sort the results by the trips_amount field in descending order.
![Screenshot 2024-06-26 210620](https://github.com/amely314/Data-Projects/assets/166257466/09666ec4-4d22-4f42-8af0-5abe80a0819b)

2.Find the number of rides for every taxi companies whose name contains the words "Yellow" or "Blue" for November 1-7, 2017. Name the resulting variable trips_amount. Group the results by the company_name field.
![Screenshot 2024-06-26 210641](https://github.com/amely314/Data-Projects/assets/166257466/085cb9f2-708e-4a92-ab6c-9cfea7a4a220)

3.For November 1-7, 2017, the most popular taxi companies were Flash Cab and Taxi Affiliation Services. Find the number of rides for these two companies and name the resulting variable trips_amount. Join the rides for all other companies in the group "Other." Group the data by taxi company names. Name the field with taxi company names company. Sort the result in descending order by trips_amount.
![Screenshot 2024-06-26 210658](https://github.com/amely314/Data-Projects/assets/166257466/63592dc8-0cae-4d9b-872b-fbd3d1f1f784)

4.Retrieve the identifiers of the O'Hare and Loop neighborhoods  from the neighborhoods table.
![Screenshot 2024-06-26 210713](https://github.com/amely314/Data-Projects/assets/166257466/7f7e550c-fefa-4389-84e4-e488747b5059)

5.For each hour, retrieve the weather condition records from the weather_records table. Using the CASE operator, break all hours into two groups: Bad if the description field contains the words rain or storm, and Good for others. Name the resulting field weather_conditions. The final table must include two fields: date and hour (ts) and weather_conditions.
![Screenshot 2024-06-26 210730](https://github.com/amely314/Data-Projects/assets/166257466/051e9e87-1d19-437d-a96b-b1de065cc724)

6.Retrieve from the trips table all the rides that started in the Loop (pickup_location_id: 50) on a Saturday and ended at O'Hare (dropoff_location_id: 63). Get the weather conditions for each ride. Use the method you applied in the previous task. Also, retrieve the duration of each ride. Ignore rides for which data on weather conditions is not available.
![Screenshot 2024-06-26 210745](https://github.com/amely314/Data-Projects/assets/166257466/0d3ba669-4e91-44f5-ab8f-a093f86d978a)



## Conclusion
Out of all the companies in the database, on November 15-16 2017 Flash Cab had the highest amount of trips available.
For November 1-7 2017 Flash Cab and Taxi Affiliation Services were the most popular rides.
Most rides are taken when weather conditions are good.
