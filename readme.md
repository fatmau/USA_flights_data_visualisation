# Airline On-Time Statistics and Delay Causes Data Exploration
## by Fatma Urek Uludag


## Dataset

> I chose to use **Flights** data set for my Data Visualisation project. Dataset contains below fields per month, airport and carrier for all domestic flights of USA from January 2019 to March 2020;
- the count of delayed flights split by causes, 
- the count of arrived flights, 
- the count of cancelled flights,
- the count of deprived flights,
- delay durations (in minute) split by causes.


## Summary of Findings

> Even though NAS reason has a high ratio on delayed flight count spread, its impact lowers for duration whereas carrier, weather and late aircraft reasons have an opposite impact. Therefore carrier, weather and late aircraft reasoned delays should tend to take longer than security or NAS related delays.

> LGA airport does not only have the highest rate of delayed flights but also the highest delay duration per flight. There must be a special case with this airport.

> F9 carrier has the highest delayed vs arrived flight rate, however delay duration per flight is 15 min (lower than EV and B6 carriers). Even though F9 carrier has delays more than 20% of flights, they seem to keep delays shorter.

> **WN** airline has the highest flight rate; **AA, DL and UA** follow it. Parallel to flight numbers, **WN** airline has the highest delayed flight rate and **AA** follows it; but the order for the rest is different: **UA, B6**. 

> highest number of flights were in July 2019, but in general distribution looks balanced in general except the decrease on Februaries.


## Key Insights for Presentation

> My main insight for presentation os the significant decrease on delayed flight numbers at March 2020. Delayed flight ratio and duration per flight tend to decrease since August 2019 however it drops dramatically at March 2020. When I look at the arrived flight per month bar plot, I could easily see there is no decrease on flight counts at March 2020. On the other hand, we see 6% decrease in the count of late aircraft caused delayed flights at March 2020. Thetefore, I presume this as a side effect of international flight bans (started early March '20) to domestic flights.