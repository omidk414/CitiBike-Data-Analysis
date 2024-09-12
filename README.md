## CitiBike Data Analysis for January 2023

Tableau Public Link:
https://public.tableau.com/app/profile/omid.khan/viz/citibikes_17261112802020/Story?publish=yes

### 1. Data Overview

The analysis is based on CitiBike's Trip History Logs for January 2023, which consist of 1,000,000 records. The dataset can be downloaded from this link https://s3.amazonaws.com/tripdata/2023-citibike-tripdata.zip. The dataset contains the following columns:

- **ride_id**: Unique identifier for each ride
- **rideable_type**: Type of bike used (e.g., classic, electric)
- **started_at**: Start timestamp of the ride
- **ended_at**: End timestamp of the ride
- **start_station_name**: Name of the station where the ride started
- **start_station_id**: Unique ID for the starting station
- **end_station_name**: Name of the station where the ride ended
- **end_station_id**: Unique ID for the end station
- **start_lat**: Latitude of the starting station
- **start_lng**: Longitude of the starting station
- **end_lat**: Latitude of the end station
- **end_lng**: Longitude of the end station
- **member_casual**: User type (either member or casual rider)
![CSV](https://github.com/omidk414/tableau-challenge/blob/main/images/Excel.png)

### 2. Top and Bottom 10 Stations for Start and End of Journeys

From the analysis of the top and bottom 10 CitiBike stations where journeys began and ended, the station **W 21 St & 6 Ave** is the most frequently used station for both starting and ending rides in January 2023. The visualizations highlight the most popular stations in the system, showing high levels of activity at central Manhattan locations.

- **Top 10 Stations Started At**: The busiest starting stations include central locations such as **6 Ave & W 33 St**, **E 40 St & Park Ave**, and **Broadway & W 58 St**. Each of these stations handled a large volume of rides, with **8 Ave & W 33 St** having 3,069 recorded starts.
  
- **Top 10 Stations Ended At**: Similarly, popular end stations match the top start stations, with **W 21 St & 6 Ave** leading with 8,575 recorded ends. This demonstrates a significant volume of trips both starting and ending within central Manhattan areas.
  
- **Bottom 10 Stations Started At and Ended At**: The least frequented stations, such as **57 Rd & 58 St** and **Lab - NYC**, had only a few rides originating or ending there, highlighting lower usage in some outlying areas of the network.
![Stations](https://github.com/omidk414/tableau-challenge/blob/main/images/Stations.png)   


### 3. Popular Start and End Stations: Geospatial Representation

#### Start Stations

The map visualization of start stations demonstrates the density and popularity of CitiBike stations in various parts of New York City. The size of the circles represents the number of rides originating from each station. The densest areas include midtown Manhattan, especially stations near landmarks and high-traffic areas.

- **Popular Start Station**: For January 2023, **W 21 St & 6 Ave** stands out as the most popular station, with 3,873 recorded starts, as seen in the map. Many stations in central Manhattan show significant activity, indicating high ridership in those areas.
   ![Map1](https://github.com/omidk414/tableau-challenge/blob/main/images/Start_Map.png)

#### End Stations

Similarly, the map of end stations provides insight into where trips most commonly conclude. As with start stations, the largest concentration of end rides is also in midtown Manhattan, with **W 21 St & 6 Ave** leading the list with 8,575 recorded end rides.

- **Popular End Station**: The visual representation confirms the concentration of bike drop-offs at **W 21 St & 6 Ave**. This area, along with other dense clusters of end stations, reflects major transit hubs and commercial areas with high foot traffic.
![Map2](https://github.com/omidk414/tableau-challenge/blob/main/images/End_Map.png)   

### Conclusion

The data analysis reveals clear patterns of CitiBike usage, with the majority of trips concentrated in Manhattan, particularly around major streets and avenues. Stations such as **W 21 St & 6 Ave** serve as key hubs for both starting and ending trips, while certain outlying stations exhibit minimal activity. This insight helps inform future decisions regarding station placement and expansion, as well as operational adjustments based on user demand in high-traffic areas.   

