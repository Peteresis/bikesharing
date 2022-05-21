![cosmo-hero22](https://user-images.githubusercontent.com/98360572/169594155-8be04a88-e352-40c8-a1aa-c08518ced21b.png)
# Analysis of NYC CitiBike Trip Data Using Tableau
---

## :one: Overview of the analysis 

Citi Bike is the nation's largest bike share program, with 25,000 bikes and over 1,500 stations located throughout Manhattan, Brooklyn, Queens, the Bronx, Jersey City, and Hoboken. Citi Bike is a fun and affordable way to get around town. It was designed with convenience in mind for quick trips. Citi Bike is frequently faster than other modes of transportation (particularly when traveling across town), and it is more convenient than owning a bike. Using Citi Bike instead of taxis can save you a lot of money. A year of Citi Bike is also less expensive than two monthly subway passes.

Kate is a tourist from Des Moines, Iowa, who recently visited New York. During her trip, she mostly used CitiBike to get around New York. She was amazed after the trip that she could save a lot of money on taxis and bus fares by using CitiBike, and that she could get around town without getting stuck in traffic. Her enthusiasm for the service prompted her to meet with an angel investor and try to persuade them that it would be a good idea to launch DesBikes, a service similar to CitiBike for the city of Des Moines.

Before deciding whether to fund the DesBikes project, investors could also learn more about the results of CitiBike in New York.

To gain a better understanding of the company's operations, we will use public data available from CitiBike's website and analyze it with Tableau.


## :two: Results

The data received consists of a CSV file for the month of August 2019.  This file only contains 2.3 million records with information about the number of rides for the month, the start point, end point and ride duration.  It also contains basic demographic data such as gender and age of the person renting the bike.  The data does not contain any financial information, so our analysis is going to focus on the operational side of the business as we do not have any financial reports of the incomes and expenses generated by the 2.3 million rides.

Below are the worksheets generated using Tableau.

|   ⚠️ **NOTE: Please click on any image to zoom**     |
| ----------- |


#### Worksheet 1: NYC CitiBike Basic Data
It shows that the data received contains 2,344,244 records of individual rides and there were 13,983 bikes in use during the month of August 2019. `That is about 6 trips per bike per day`.
<p align="center">
 <img src="https://user-images.githubusercontent.com/98360572/169608636-105526d8-ba1d-4e41-b4c8-20aee31d48af.png" width="50%" height="50%">
</p>

#### Worksheet 2: Top Starting Stations
Map of the Stations with more than 10,000 trips in the month of August 2019.  `Top stations are concentrated in lower Manhattan`.
<p align="center">
 <img src="https://user-images.githubusercontent.com/98360572/169657635-dc5905b4-5522-4578-83f2-6b1f9481467a.png" width="50%" height="50%">
</p>

### Worksheet 3: Top Starting Stations by Number of Rides
Chart of the top stations. `Each of the top 10 stations generated more than 11,500 rides`. 
<p align="center">
 <img src="https://user-images.githubusercontent.com/98360572/169657755-efc2dd36-c329-421a-bdcf-9c9e64cc42e4.png" width="50%" height="50%">
</p>

### Worksheet 4: Trip Duration
Duration per ride. `Most rides have a duration of 30 minutes or less`.
<p align="center">
 <img src="https://user-images.githubusercontent.com/98360572/169658015-ed83c53e-8ef5-4b8a-8e85-2ab7c9907dd7.png" width="50%" height="50%">
</p>

### Worksheet 5: Trip Duration by Gender
Trip duration by Gender. `The service is used predominantly by men at an approximate ratio of 3 to 1`.
<p align="center">
 <img src="https://user-images.githubusercontent.com/98360572/169657935-c13030b9-ca30-4078-9201-08147cfaf06b.png" width="50%" height="50%">
</p>

### Worksheet 6: Number of Rides per Weekday
`Thursdays, Fridays and Saturdays are the days with more rides`.
<p align="center">
 <img src="https://user-images.githubusercontent.com/98360572/169658152-94b4e9a9-8811-4aee-bf5c-dc7b19aae7f6.png" width="50%" height="50%">
</p>

### Worksheet 7: Heatmap of Trip Time of the Day vs Weekday 
There are two peak times during weekdays: `from 7 am to 9 am (beginning of workday) and 4 pm to 7 pm (ending of workday)`.  
During weekends the rides are more evenly distributed.
<p align="center">
 <img src="https://user-images.githubusercontent.com/98360572/169658205-fc2d4064-7b30-40ad-905f-1ecfe33c3d7f.png" width="50%" height="50%">
</p>

### Worksheet 8: Hour of Start Time vs Gender vs Weekday
`Men use the service more than women`.  Both genders ride bikes at about the same time of the day.
<p align="center">
 <img src="https://user-images.githubusercontent.com/98360572/169658267-0aeaec17-ff58-4392-9295-2ebb0568ef34.png" width="50%" height="50%">
</p>

### Worksheet 9: Heatmap of User Type vs Gender vs Day of the Week
`Male suscribers are the main users of the system`, followed by female suscribers.  The rate of 3:1 is maintained.  
Based on the number of 'Unknown' gender, the quality of demographic data among suscribed users is better than the quality of data of 'Customer' users.
<p align="center">
 <img src="https://user-images.githubusercontent.com/98360572/169658621-882d3316-9463-4392-803e-537e8abc5369.png" width="50%" height="50%">
</p>

### Worksheet 10: Top Users by Age and Ride Duration
`The 'Top 10' user group, by Ride Duration, ranges from 24 to 34 years`.  There is a spike of users of 50 years of age that looks odd.  The data needs to be cleaned. 
<p align="center">
 <img src="https://user-images.githubusercontent.com/98360572/169659171-0bf06f51-963e-41fd-bda8-2389750e9e69.png" width="50%" height="50%">
</p>

### Worksheet 11: Summary Worksheet - CitiBike in NYC User Profile
* Gender: Male.
* Age: 24 to 34 years old.
* Rides mostly in the lower Manhattan.
* Based on the peak hours of the service, most riders use CitiBike to get to and from work.
* Rides last less than 30 minutes
* Each bike is used an `average` of 6 times per day

<p align="center">
 <img src="https://user-images.githubusercontent.com/98360572/169659221-adf6c801-1e57-45a8-af34-d07b54885b20.png" width="50%" height="50%">
</p>

## :three: Summary

Based on the data analyzed, it seems like the CitiBike service in NYC is a successful venture but, can DesBikes succeed in Des Moines, Iowa?

The site `BestPlaces.net` offers a comparison between both cities using census data.  From the table below the first line of information calls our attention immediately.  The population in Des Moines is `212,312` inhabitants while New York has `8,253,213`, so New York's population is almost 40 times bigger than Des Moines (the exact figure is 38.9).  The number of rides per inhabitant in NYC is `2,344,244 rides / 8,253,213 inhabitants = 0.284 rides/inhabitant`.  If we apply the same proportion to Des Moines, the potential market would be `212,312 inhabitants * 0.284 rides/inhabitant = 60,305 rides per month`, a far cry from the 2.3 million rides per month of NYC.

The comparison of other factors are not conclusive.  The median age in Des Moines and NY is very similar, although the median income in Des Moines is 12% lower but the living costs in NY are much higher, so in relative terms the inhabitants of Des Moines are better off than New Yorkers.  It is worth noting that according to the data in `BestPlaces.net`, the housing costs in NY are 287.8% higher than Des Moines.

### Data from BestPlaces.net ([2022 Compare Cities Overview: Des Moines, IA vs New York, NY](https://www.bestplaces.net/compare-cities/des_moines_ia/new_york_ny/overview))

|   ![image](https://user-images.githubusercontent.com/98360572/169660596-a761bdb2-e74f-47e7-8cd2-49363e41922b.png)     |
| ----------- |

The second factor to consider is geography.  As can be seen in the image below, the city of Des Moines is much smaller than New York.  The average commute time in Des Moines is 18.83 minutes (see table above) while in NY is 40.78 minutes, so it seems like the size of the city and the relative fluid traffic in Des Moines makes a bike share program less attractive than in NYC.

### Map of Des Moines superimposed on the map of New York
![image](https://user-images.githubusercontent.com/98360572/169661488-a4120ced-30c5-4c22-9369-89bf7df1bff8.png)

[Des Moines map overimposed on New York map](https://www.size-explorer.com/en/compare/cities/newyork2/desmoines2/) 

## :four: References

**Module 14: Tableau Basics**, https://courses.bootcampspot.com/courses/1145/pages/14-dot-0-1-tableau-basics, :copyright: 2020-2021 Trilogy Education Services, Web 21 May 2022.

**Tableau Demo**, https://www.youtube.com/watch?v=lR5Aiy5umvw

**2022 Compare Cities Overview: Des Moines, IA vs New York, NY**, https://www.bestplaces.net/compare-cities/des_moines_ia/new_york_ny/overview

**Size Explorer: Comparing the size of New York and Des Moines**, https://www.size-explorer.com/en/compare/cities/newyork2/desmoines2/
