# Exploration Of Ford GoBike Data
## by Hassan Abbas Jaffri


## Introduciton

> Ford GoBike is a convenient way to get around the city. It’s great for short/one-way trips as well as longer recreational rides. Ford GoBike is a regional public bicycle sharing system in the San Francisco Bay Area, California. Beginning operation in August 2013, the Ford GoBike system currently has over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose. The system is expected to expand to 7,000 bicycles around 540 stations in San Francisco, Oakland, Berkeley, Emeryville, and San Jose. The system is operated by Motivate in a partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District. Ford GoBike is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States. As of January 2018, the system had seen nearly 500,000 rides since the launch in 2017 and had about 10,000 annual subscribers. The bikes are available for use 24 hours/day, 7 days/week, 365 days/year and riders have access to all bikes in the network when they become a member or purchase a pass.


## Dataset

> There are 1926960 rows and 28 columns in new cleaned dataset as opposed to the original dataset which comprised of 2055803 rows and 16 columns. For the exploration and analyses, i have added the following features in the dataset:
1. member_age
2. start_time_month_name
3. end_time_month_name
4. start_time_month_number
5. end_time_month_number
6. start_time_weekday
7. end_time_weekday
8. start_time_day
9. end_time_day
10. start_time_hour
11. end_time_hour
12. duration_min

The features that were already in the dataset are:
1. duration_sec
2. start_time
3. end_time
4. start_station_id
5. start_station_name
6. start_station_latitude
7. start_station_longitude
8. end_station_id
9. end_station_name
10. end_station_latitude
11. end_station_longitude
12. bike_id
13. user_type
14. member_birth_year
15. member_gender
16. bike_share_for_all_trip


## Summary of Findings

> This investigation of the Ford GoBike dataset answers all of the questions asked earlier in the nothebook. The average height of the bike users is around 31 while most of the users lie between the ages of 24-40. Our investigation was successful in providing us the insights about the relationship between the genders and user types aswell as the user types and member ages which have been explained in detail in the insights stated above. The most trips are done on weekdays from 8am-10am and 5pm-7pm in the months of summer. This is the time when the bikes are most high in demand as opposed to weekend and winters when they are least in demand. The investigation further tells us that the average trips takes around 12 minutes. The facts are quite different and change altogheter when we compare customers from subscribers because of the difference nature and purpose of these user types.


## Key Insights for Presentation

> For the presentation, I focused on the influence of age, user group, genders, trip durations, weekday, month and hour data. I started by introducing the point plot for monthly bike usage for both of the user groups, followed by a box plot of age per user type and gender distribution, and at the last i bar plotted the trip duration per user type and gender data.  I tried to use different color palettes for each variables to make sure it is clear.