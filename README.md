CitiBike Analysis - Jersey City, New Jersey
===========================================

List of visualizations include the following:
---------------------------------------------

    - Maps of the starting stations and ending stations. 
    - Yearly rider count.
    - Quarterly rider count by gender and user type.
    - Bar graph representing the total ridership from 2018-2020 specifying user type.
    - Bar graph representing a quarterly breakdown of the total by gender.
    - Bar graph specifically representing female rider during 2018-2020.
    - Graphs represneting the top 20 stations to start and end a ride. 
    - Bar graph representing average ride duration split by gender. 
    - Bar graph reprenenting average ride duration when the gender is unkown. 
    - 2 Dashboards
    - 1 Story summarizing these graphs. 

* Overview 

    This data set is all the csv files of trip history between 2018-mid 2020. The data was compiled from this website. [CitiBike data](https://www.citibikenyc.com/system-data) The data specifically comes from the "Citi Bike Trip Histories" section and it's the csv files with the "JC-". Using just the New Jersey data from this time period proved to be a good robust dataset that can point out trends that may be specific to the system's performance and usage in New Jersey. These changes which may prove meaningful as Jersey City is a suburb of NYC and is catering to potentially a different kind of rider. 

* Analysis 

    To start out with we have two static maps that show all the Jersey City stations denoted with a marker of a size proportional to the stations usage. The stations usage is determined by the number of rides started. The largest place by far is the Grove St. PATH station. For a little background PATH in this case stands for Port Authority and appear to be responsible for the transit infrastructure in Jersey City. The Grove St. PATH station appears to be situated right in downtown Jersey City and likely provides transit to and from New York which would make it an ideal place for a bike sharing station to be located for PATH riders. 

    The first these two maps is all the Jersey Citi Bike stations where rides begin their ride. The second map represents where all the rides end. This map is zoomed out a bit by default to show that there are some, not very many rides that do end up in Manhattan and Williamsburg. Based on a google search from the Grove St PATH station to Central Park it is a 49 minute, 8.5 mile ride which is not an unreasonable length for a bike ride. However, a rider would need to take a ferry or go way out of the way to make the trip Given that information, as well as Citi Bike's pricing model of charging per half hour, it makes sense that most rides starting in Jersey City end in Jersey City. If a rider wanted to go to New York, it would make more sense to take the train or drive into the city and rent a bike upon arrival for transport while in the city. 

    Based on the charts for yearly ride count, quarterly ride count, and ridership by user type there are some pretty clear demographic breakdowns. The first being that subscribers are far and away more common than non-subscribers to use the system. This is something that I would attribute to both the pricing model and subscribers use the service as a means of transportation day over day. Non-subscribers on the other hand use this service for more lesuire and recreational purposes. This seems to show up when looking at the duration of the rides. Non-subscribers typically have far longer ride durations than do subscribers which would indicate a difference in why the system is being used. 

    One of the suggested phenomena in the directions is looking at female ridership. Based on the data it's pretty clear that males vastly outnumber females with respect to Citi Bike usage. There is a bar chart that details female ridership during the first half of 2018, 2019, and 2020. That shows that like men, there are far more female subscibers than there are non-subscribers.  Also, the data shows that in the previous two years female ride durations were slightly longer. There appears to be a pretty steady pattern of growth among female riders in the past two years with an aberation during the second quarter of 2020. An opportunity for clearer data comes from a relatively small percentage of the data where gender is not known. 

    Another phonomena that became clear was the potential effect of Covid 19 on the Citi Bike system as it relates to Jersey City. The year 2020 in Q1 was shaping up to be right on pace with rider growth seen in the previous two years. When Covid 19 hit really hard in Q2 there is a notable drop in rides taken by subscribers. Subscriber ride counts dropped to half. This is something that could be attributed to business closures, more workers working remote, and event cancellations. In Q2 during Covid, and even likely up to today, all the reason people would need transportation have kinda sorta evaporated causing a drop in rides being taken by Citi Bike subscibers. That said, there appear to be many  more non-subscribers using the system. Non-subscriber rides are up about 2.5x compared to Q2 of last year.  This change, taken with the longer trip duration, would indicate that in the age of Covid, Citi Bike is also being looked to as a form of recreation itself as a bike ride would fall within the guidelines of social distancing.  

