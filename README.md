![Project Header](/images/mm_header.png)

# Purpose
This analysis was conducted to evaluate the impact of the Automated Camera Enforcement *(ACE)* program on bus performance 
in Brooklyn, with a specific focus on routes commonly used by **Brooklyn College** students. The goal is to determine whether  
the implementation of ACE has led to improvements in bus speeds and trip times, which are critical factors affecting the 
reliability and efficiency of public transportation for daily commuters.
By comparing two ACE-enforced bus routes **(B44 SBS and B41)** with a non-ACE route **(B6)**, we aim to answer the following questions:  
- Has the ACE program led to measurable increases in average bus speeds?
- Has there been a reduction in overall trip time on ACE-enforced routes?
- How do these changes compare to bus routes not enforced by ACE?
- Is there a relationship between bus lane violations and changes in performance over time?


The findings of this analysis will help assess the effectiveness of the ACE program in improving public transit, particularly on key routes
serving Brooklyn College students.

# Background
**Brooklyn is home to many bus routes, some of which happen to be some of the busiest in NYC.**
*https://www.mta.info/agency/new-york-city-transit/subway-bus-ridership-2023*
![Table showing busiest bus routes](/images/busy.png)

The ACE program is a bus-mounted camera system that issues violations to vehicles occupying bus lanes, double parked vehicles along bus routes, and vehicles blocking bus stops. It is currently active on 39 bus routes that carry over 775K average weekday riders. Of those 39 routes, 9 are in Brooklyn. 
*https://www.mta.info/agency/new-york-city-transit/automated-camera-enforcement*
![List showing ACE routes in Brooklyn](/images/ace_bk.png)

# Method
For our analysis we are focusing on 3 bus routes, *all ones that service Brooklyn College*
![B6, B41, B44+](/images/buses.png)

# Exploratory Data Analysis
Using the primary data set, we discovered the number of ACE violations on record for the B41 and B44+
![B41 ACE](/images/b41ace.png)
![B44+ ACE](/images/b44ace.png)

We also looked at the exemptions for ACE violations
![Exemptions](/images/exemptions.png)

We then examined the speed trends for each of the buses

The average speed trends in 2025:
- B6: 8.47 
- B41: 7.56
- B44: 8.25 

The B6 is not being affected and moves more efficiently than the buses with ACE implemented during that period of time. The reason why this could be happening can be affected by many factors such as traffic, route or period. The B6  speed average has been improving and becoming faster than the buses with ACE implemented. As observed in the tables it is noticeable that B6 speed average is 0.2 faster than B44 and 0.86 faster than B41 which demonstrates that ACE might not be as successful in this route than other ones in a different borough and that ACE does not guarantee immediate faster service.
![Speed Comparison](/images/speed_travel.png)

Here we compare the speeds of all 3 of our focus buses over time
![Change in bus speed over time](/images/3comparison.png)


# Insights and Conclusion
The number of violations decreasing appears to correspond with an increase in speed for the B41 and B44. Less violations being issues means that there are less cars blocking bus lanes, which occurs alongside an increase in bus speed. 

However, while ACE bus routes (B41 and B44+ ) have seen speed improvements, non-ACE bus routes (like the B6) have also seen speed increases. ACE does appear to be partially responsible for improving speeds along those routes, but citywide efforts to improve bus speeds may also be responsible. The Better Buses inititative *(https://www.nyc.gov/html/brt/html/betterbuses/betterbuses.shtml)* and Bus Network Redesign *(https://www.mta.info/project/bus-network-redesign)* are just some examples of how the city has been working to improve bus service overall. 

# Videos
[![Video 1](http://img.youtube.com/vi/fgpGO1mT07o/1.jpg)](http://www.youtube.com/watch?v=fgpGO1mT07o "Video 1")
[![Video 2](http://img.youtube.com/vi/ifTdYRWUDTA/1.jpg)](http://www.youtube.com/watch?v=ifTdYRWUDTA "Video 2")


# Contributors
- Mary, Brooklyn College '26, *https://www.linkedin.com/in/mary-mctarsney/*
- Lizzie, Baruch College '26 *https://www.linkedin.com/in/lizzietsk/*
- Martina, Brooklyn College '26 *https://www.linkedin.com/in/martina-garcia-vasquez-9b584b251/*
