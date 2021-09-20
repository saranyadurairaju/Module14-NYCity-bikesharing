# Citibike Business Proposal with Tableau

* Tableau is a powerful and fastest growing data visualization tool used in the Business Intelligence Industry. It helps in simplifying raw data in a very easily understandable format. 

* Data analysis is very fast with Tableau tool and the visualizations created are in the form of dashboards and worksheets.

* It is one of the most user-friendly data visualization tools available. It requires minimal technical knowledge and the only coding required adopts a similar syntax to that of Python's!

## Overview of Project

Me and my friend Kate are planning to start a citibike Business in our home town Den Moines after our long trip to New York City. As New York City is famous for its Citibike and its a convenient way of transportation in a busy city. By using a similar data released to public, we are planning to give a business proposal to the investor. 

For this analysis we are using Pandas for data conversion and Tableau for Visualization. Then we are creating a Story to show the Investor with a Report. 

![image](https://user-images.githubusercontent.com/85472349/134023975-d53052bb-b02e-4286-9a9e-622862df97bb.png)

## Analysis 

We are using Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, we have to create a set of visualizations:

* Show the length of time that bikes are checked out for all riders and genders

* Show the number of bike trips for all riders and genders for each hour of each day of the week

* Show the number of bike trips for each type of user and gender for each day of the week.

Finally, we are adding these new visualizations to the two we created already for our final presentation and analysis to pitch to investors. 

Below is the fields and corresponding datatypes of our initial data we are going use for Business proposal:

![image](https://user-images.githubusercontent.com/85472349/134024871-4fc29a4f-0d13-4225-9719-1a01384b8c2b.png)


## Changing Trip Duration to a Datetime Format

We are using Python and Pandas functions to convert the "tripduration" column from an **integer to a datetime** datatype to get the time in hours, minutes, and seconds. After convertion we will export the DataFrame as a CSV file to use for the trip analysis. 

![image](https://user-images.githubusercontent.com/85472349/134028234-2bcb2494-24de-4498-a219-ccda2a7c63ba.png)

**Datatype Verification**

![image](https://user-images.githubusercontent.com/85472349/134028330-226c5ecf-c722-445a-abf1-a83c67a48841.png)

**Exporting DataFrame as a CSV**

![image](https://user-images.githubusercontent.com/85472349/134028424-0d21e59e-bd41-4c2e-a325-631a01e1716e.png)

**Data Verification in Tableau**

![image](https://user-images.githubusercontent.com/85472349/134028603-9b6947b8-f009-4b74-a8e0-9b0050a8364d.png)



## Creating Visualizations for the Trip Analysis


**Creating the Checkout Times for Users Viz**

This is a line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour:

![image](https://user-images.githubusercontent.com/85472349/134031093-8a91c6f6-0415-4f54-900e-67a2db60d57d.png)

**Creating the Checkout Times by Gender Viz**

This is a line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender.

![image](https://user-images.githubusercontent.com/85472349/134031709-a5a72641-1158-4c7a-884b-c02d1205c5f5.png)

**Creating the Trips by Weekday for Each Hour Viz**

A heatmap showing the number of bike trips for each hour of each day of the week.

![image](https://user-images.githubusercontent.com/85472349/134032094-15177c68-4093-4656-bdf8-7543beca7d57.png)

**Creating the Trips by Gender (Weekday per Hour) Viz**

A heatmap showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender.

![image](https://user-images.githubusercontent.com/85472349/134032302-0fbdd7b1-e9be-40ee-855a-cdc070674ec2.png)

**Creating the User Trips by Gender by Weekday Viz**

A heatmap showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender.

![image](https://user-images.githubusercontent.com/85472349/134032621-9ee7952f-0fcb-4337-995c-01c2d32ffac2.png)


## RESULTS

With the above five visualizations we created below viz for better understanding and clear proposal:

**Trips by Age**

![image](https://user-images.githubusercontent.com/85472349/134033397-7c8d1144-89fd-4390-817f-f9aab967a3af.png)

**Bike Maintenance**

![image](https://user-images.githubusercontent.com/85472349/134033670-4c65b161-eb57-4b52-b275-4bd6f2ded85b.png)


### Bike Usage Hours

![image](https://user-images.githubusercontent.com/85472349/134033793-ea0d51c7-165f-404a-a836-b54bdf525fd3.png)


### Gender & Subscriber

![image](https://user-images.githubusercontent.com/85472349/134033928-1082d1dd-7403-45b0-b24f-cf264f27c21d.png)

### Busy Hours

![image](https://user-images.githubusercontent.com/85472349/134034028-30889af1-7094-4287-998b-0278fc978cc3.png)


## SUMMARY

The final Story for Business proposal is ready with all Visualizations. From our Analysis we can come to below conclusion:

1) Bikes are utilized for more number of people. 

2) Most of the bikes will be busy during Peak Office hours. 

3) Both Genders are using bikes, though Men uses a lot.

4) Business can run all days and weekdays are more busy. 

5) Bike Maintenance can be done very easily by calculating the number of hours.


### Recommendations

![image](https://user-images.githubusercontent.com/85472349/134035200-83416762-ca32-4a47-9750-3e51c7f6b8e1.png)


## Final Tableau Link

![link to dashboard](https://public.tableau.com/app/profile/saranya.durairaju/viz/citibike_proposal/CitiBikeProposal?publish=yes)


**From our Analysis, we can conclude that starting citibike business in Des Moines is a great idea and it will definitely be profitable !!!**

**Get! Set!! Go!!!**

