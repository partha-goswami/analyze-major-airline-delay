# Airline On-Time Statistics and Delay Causes
## by Partha Goswami


## Dataset

> The U.S. Department of Transportation's (DOT) Bureau of Transportation Statistics (BTS) tracks the on-time performance of domestic flights operated by large air carriers. Summary information on the number of on-time, delayed, canceled and diverted flights appears in DOT's monthly Air Travel Consumer Report, published about 30 days after the month's end, as well as in summary tables posted on this website (https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp). BTS began collecting details on the causes of flight delays in June 2003. Summary statistics and raw data are made available to the public at the time the Air Travel Consumer Report is released. (Data referred from - https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp)

> Our data frame contains flight delay information. Initially it had the following columns: 'year', 'month', 'carrier', 'carrier_name', 'airport', 'airport_name', 'arr_flights', 'arr_del15', 'carrier_ct', ' weather_ct', 'nas_ct','security_ct', 'late_aircraft_ct', 'arr_cancelled', 'arr_diverted',' arr_delay', ' carrier_delay', 'weather_delay', 'nas_delay','security_delay', 'late_aircraft_delay'.

> Later we performed some transformations, renaming and also added/dropped some columns. Finally, we have the following columns with us, namely: 'year', 'month', 'carrier_name', 'arrival_flight_count', 'arrival_delay_in_min', 'air_carrier_related_delay_count','weather_related_delay_count', 'NAS_related_delay_count', 'security_related_delay_count', 'late_aircraft_related_delay_count', 'arrival_canceled_count', 'arrival_diverted_count', 'carrier_delay_in_min', 'weather_delay_in_min', 'nas_delay_in_min', 'security_delay_in_min', 'late_aircraft_delay_in_min', 'airport_name',
 'city_name', 'state_name'.
 
> In total, we have 1769 observations.


## Summary of Findings

> Since we were seeing the flight delay data, corresponding to the months of february, so we would assume that, there would be a number of states is US, which still have winter/snowy conditions. This in fact inflicted a huge amount of delay in flight operations, especially for the states like Montana, Wyoming, Alaska, Minnesota etc.

> Also we have noticed a handful of carriers, for example, delta & PSA, continued operations with minimal delay across the US, while including those cold states as well.

> Airports like/including McCarran, Dallas Love Field, Seattle and Atlanta have handled enormous amout of traffic, without significant delay. These should be role-model for flight operations, for other bigger airports to follow.


## Key Insights for Presentation

> Certain states like Georgia, Illionois, Massachusetts and new jersey caused enormous NAS related delays. They might figure out ways to reduce the National Aviation related delays.

> Charlotte Douglas, Chicago O'Hare & Dallas Fort Worth had security related delays in the past. So, probably some security hindrances might have happened in those airports. So, it might be better to modernize/automate secury in those airports, thus ensuring lesser delays in future, for huge number of passengers.