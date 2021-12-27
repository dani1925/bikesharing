
# CitiBike Data
## Overview

This repository contains general information on the use of the "CitiBike" service for the city of New York in the month of August of the Year 2019.m
The objective of this analysis is to provide information to potential investors to replicate this business model in another city.

In this first analysis a central part is the comparison of the use of the service according to the gender of the user.

It was decided to use the month of August since it is in the month where the greatest demand for the service is reported,

### Date Convertion

The original source of the data contains a field that contains the information of the duration of the trips, however, the provider of the information used an integer as timestamp.

In order to perform a correct analysis in Tableau, it is necessary to convert this data into a variable datetime. To solve this problem, a python program was made to replace this type of data.

## Results

## Popular "Start Trip Station"

The first graph shows a map of New York City and each circular marker represents a bicycle station.

Specifically, these stations show where the beginnings of the trips are made. The color and size of the circular marker is used to better show where bike trips are starting.

The first graph shows a map of New York City and each circular marker represents a bicycle station.

Specifically, these stations show where the beginnings of the trips are made. The color and size of the circular marker is used to better show where bike trips are starting.

Although this information will be totally different in the city in which you want to replicate the business model, a possible future analysis may be to determine what parameters are triggering the start of travel in these areas and replicate it in other cities

## CheckOut Time for users

It is interesting to note how a large number of trips take place just at midnight, the data shows a time of approximately 5 min. Even the behavior of this graph may be due to a data update just at midnight

## CheckOut Time for users

Continuing with the analysis of the data, an interesting piece of information for the future marketing team of the new start up that we want to start is to notice that most of the users are men.

A future analysis would be to determine why women are not so interested in the service

## Trips by Weekday by Hour

This graph helps us to understand at what time of a certain day of the week the highest demand for service is being reported, of course this data is important to have the largest number of bicycles available at these times and to provide services or maintenance for other times of the day.

The data shows that the highest demand for the service is reported between 5 and 6 pm.

## Trips by WeekDay by Hour by Gende

It is incredible to see how this graph shows the hours of greatest demand just in the hours of entry and exit from work between Monday and Friday, and a clear use during the weekend, regardless of whether you are a man or a woman.

Of course, the difference in tonality is because, as already stated, men use the service much more than women.

## User trips by Gender by weekday

For an investor the following information is key:
The largest number of users are both male and female subscribers. therefore, any marketing and advertising campaign should be focused in this regard since users seem to prefer a subscription, regardless of gender.

## Last but not Least

It shows the most popular stations in which users end their trips, of course downtown manhattan with the most important tourist and corporate places have the highest travel termination places

[link to dashboard](https://public.tableau.com/shared/3XZZDGNHQ?:display_count=n&:origin=viz_share_link)
