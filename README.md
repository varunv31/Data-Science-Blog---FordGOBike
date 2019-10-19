# Data-Science-Blog---FordGOBike
Ford GoBike is the Bay Area's bike share system. Bay Area Bike Share was introduced in 2013. It services San Francisco, the East Bay and San Jose.  Similar to other bike share systems, Ford GoBike consists of a fleet of bikes that can be unlocked in one station and returned in any other network station. Thus, this is ideal for one-way trips. These bikes are available for use thorughout the year and riders have access to all bikes in the network.

# Project Motivation:
I have worked with the Ford dataset before and the dataset comes from Ford bike-share program. This data provides a lot of information about the people renting the bike and the routes

# File Descriptions:
Ford GoBike is a publicly available dataset that will enable different folks with different skillsets to play around with.
Data is downloaded from https://s3.amazonaws.com/fordgobike-data/index.html
For the current analysis, 2018 data is downloaded
Brief description about the data Each trip is anonymized and includes:

1. Trip Duration (seconds)
2. Start Time and Date
3. End Time and Date
4. Start Station ID
5. Start Station Name
6. Start Station Latitude
7. Start Station Longitude
8. End Station ID
9. End Station Name
10. End Station Latitude
11. End Station Longitude
12. Bike ID
13. User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
14. Member Year of Birth
15. Member Gender

# Business questions:
After reviewing the data, it is evident that the Ford GoBike is focused in the bay area with many people already subscribed to this service. There are others who would like to try this out for once before availing the service. 

In a crowded area like Bay Area, people often use such bike services to commute short distances within the city on a regular basis.

Hence, to understand the true use of such service, it is very important to evaluate some basic questions

Listing down the different questions that we would like to answer:
1. Who are Ford GoBike's customers? (w.r.t Deomgraphics)
2. When is the service often used? (weekdays vs. weekends)
3. What is the average ride across different cities? What is the average duration of each ride?
4. Which city has the highest usage of this service?
5. What are the characteristics of Customers vs. Subscribers?
6. Is the 'Bike Share For All program' successful?
7. Which are the famous starting and destination station?
8. Which are the famous routes?
9. What time of the day do users use this service?

# Conclusion
From the above exploratory analysis, it is evident that
**Persona of the user**
The user of Ford GoBike is a male between 20 and 40 years of age for their <30 min rides, primarily on weekdays

    1.The age of population who use Ford GoBike service is spread between 20 and 40 years
    2.73.3% of the population is Males
    3.We observe a bi-modal distribution for Male age 25 years and 30 years
    4.Whareas, 50% Female population is <30 years of age
    5. 83.4% of the trips are taken during weekdays
    6. And thse trips are primiarly taken on Tuesday, Wednesday and Thursday (~17% each)
    7. The service is used more during weekdays than weekends
    8. Most of the trips are taken for short durations (0-30)

**Subscriber vs. Customer**
Subscriber is a male between 25 and 35 years of age who takes multiple trips within the year, but very short trips
Customer is also a male between 20 and 40 years of age largely who takes fewer trips, but rents the service for ~2.5 times the average trip duration of a Subscriber


    1.Subscribers are heavily skewed between 25 and 35 years of age
    2.~75% of the subscribers are males
    3. Customers use the service for ~2.5time longer than Subscriber
    4. Whereas, Subscribers rent this service ~8times more than a Customer
    5. Hence, when calculating #trips x Avg trip duration, a subscriber is 3 time more valuable than customer
    6. These Subscribers rent the service on Tuesday, Wednesday and Thursday mornings
    7. Whereas customers rent the service on Friday mornings

**Overall business trend vs. Bike For All program**
The overall business and the "Bike for All" are seeing a growing trend, thereby, proving that there is confidence on this mode of transportation as an alternative
    1. Ford GoBike service is also growing overall, the subscirber base increased from 75k in Jan through ~175k in Oct
    2. The holiday season has an impact on the service and we see a dip in Nov and Dec
    3. The service is also catching up with one time users
    4. The "Bike Share" program in general is growing through the year: it started off with 6k and grew to 18k in Oct
    5. The service is also catching up with one time users.
    6. All bikes are rented out primarily in the morning
    7. Majority of Subscribers rides are taken on Tue and Web
    8. Whereas a few of our customers prefer
 
**Routes**
The most common route taken by the users is between Harry Bridges Plaza and The Embarcadero at Sansome St
    1. Harry Bridge Plaza is a hangout place in SF where one can find may folks throughout the day
    2. The Embarcadero center has an office space along with restaurants and shopping complex
    3. Both these places are less than a mile in distance
    
**Station mark**
    1.The top 10 sites contribute to ~20% of the total bike rides
    2.The remaining 321 sites contribute to 80% of the rides
    3.The most common route taken by the users is between Harry Bridges Plaza and The Embarcadero at Sansome St
    4.Harry Bridge Plaza is a hangout place in SF where one can find may folks throughout the day
    5.The Embarcadero center has an office space along with restaurants and shopping complex
    7.These 2 places are ~1 mile away
    
**Other details**
    1. All bikes are rented out primarily in the morning
    2. Majority of Subscriber rides are taken on Tue and Web
    3. Whereas customers rides on Friday is less


