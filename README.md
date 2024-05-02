# flight-traffic
Currently, the air transportation market is in the deepest crisis. The effects of the pandemic have left a huge impact on both airlines and airports. As the number of flights operated decreased significantly, airlines had to quickly change their development strategies in order to continue their activities. However, even despite a significant decrease in the number of flights, passengers continue to experience flight delays. For a more detailed study of this problem, it was decided to consider the causes of delays, which lead to various negative consequences.

Every year, due to flight delays, many airlines around the world suffer thousands and millions in losses. In turn, passengers experience significant inconvenience and thus suffer a variety of losses.

Each flight is operated at a specially allotted time according to the schedule in a dedicated slot for this flight. One of the main reasons for flight delays is adverse weather conditions. To take off and land, you need a relatively calm meteorological situation in the airport area. In addition to weather conditions, flight delays can occur due to the fault of the airline itself or the airport (service company). These reasons can be divided into technical and production (organizational). Production (organizational) reasons may be related to the airport. For example, due to the high traffic of aircraft on the apron or other reasons, i.e. forced waiting in parking lots for towing or taxiing operations. Technical related to malfunctions of the aircraft or airfield equipment. Delays due to the fault of the airline may be related to: 1)lack of an aircraft for this flight at the airport of departure (late arrival from the previous flight and lack of reserve aircraft), 2) waiting for transfer passengers from delayed flights upon arrival, failures of the check-in/landing system at the airport. 3) In some cases, delays arise due to unforeseen circumstances and for reasons beyond anyone's control.

Problem :
In our project, we tried to research which factors affect to the flight delays to improve management in airports and airlines. It helps to predict and avoid organizational resons of delay and keeps companies expenses. For this perpose we create next researches:

Calculated total number of flight delays for each airline

Analysis of flight delays by months

Analysis of flight delays by day of the week

Analysis of the relationship between a block of the time range of the day and air delays

Study: which airport, depending on its geographical location and trafic, has more delays

Analysis of how weather affects flight delays: snow and temperature at airports

Analysis of the timing block (block of the time range of the day) in relation to the delay

Developed a chart of the correlation matrix

Analysis segment number

Conclusion :
We researched сlassification dataset with detailed airline, weather, airport and employment information and delay reasons for multiclass applications. and the impact of various factors on flight delays. Initially, the annual Database data was more than 6.4 millon rows, so we reduced it to half a year. We use python in our study because it is most efficient when dealing with large amounts of data. Our findings showed how various factors affect flight delays, in particular that the most important factor affecting the delay is the segments, they showed what time it all happens:

Southwest Airlines Co has the most delays

For the first half of the studied database, the largest number of delays occurred in June (135 871) and then in May (113530), whichis almost 15000 more than in the rest of the months

Most flight delays occurred on Thursday and on Friday, however, the difference between other days of the week in delays is negligible

Most often, delays occurred during flights between 14:00 and 21:00. The max delays are 53145 between 6.00 PM and 7.00 PM.

Most delays occur at Chicago O'Hare International Airport (38,804). Further into the top three are Atlanta and Dallas airports. Their number of delays is from 34093, the following airports lag behind them by about 7,000 happens.

The heaviest traffic at the airport of Atlanta airport.

The presence of snow and cold weather does not affect the number of delays. This is due to the fact that the air service lays extra time during weather changes in the cold season.

The Segment number is the main factor influencing flight delays.

According to our studies, segment numbers 2,3,4 have the largest number of delays and it is more than 120.000. Segment numbers over 8 have a negligible number of delays.
