London-bike-sharing-dataset
Overview
The dataset that is being examined includes temporal and environmental variables, as well as information about bike-sharing activities. The dataset offers a thorough understanding of how weather, holidays, weekends, and seasons affect bike-sharing habits, with an emphasis on sustainability and business applications, furthermore, the dataset offers a thorough investigation of the dynamics of bike sharing, emphasizing temporal and environmental aspects. Because every data input is timestamped, it is possible to gain a detailed knowledge of the complex interactions that shape patterns of bike sharing. The dataset encompasses several important characteristics that provide insight into the complex interplay among meteorological factors, temporal components, and the demand for bike shares. 

Key Fields:
Timestamp: Represents time intervals for data observations.
Count (cnt): Indicates the number of new bike shares.
Temperature (t1): Real temperature in Celsius.
"Feels Like" Temperature (t2): Apparent temperature in Celsius.
Humidity (hum): Humidity percentage.
Wind Speed (wind_speed): Wind speed in km/h.
Weather Code (weather_code): Categorizes weather conditions.
Is Holiday (is_holiday): Boolean field denoting holiday (1) or non-holiday (0).
Is Weekend (is_weekend): Boolean field indicating weekend (1) or weekday (0).
Season (season): Meteorological season category (0-spring, 1-summer, 2-fall, 3-winter).
Temporal Representation:
The dataset's core is the timestamp field, which provides a thorough temporal representation of every observation. Because of its temporal granularity, bike sharing activities can be used to identify trends, cyclical fluctuations, and seasonality by recognizing patterns over a range of time intervals.

Environmental Factors:
The dataset is significant because it captures environmental factors that actually influence people's decisions to share bikes. A complex contextual background is provided by temperature—both actual and perceived, or "feels like"—humidity, wind speed, and categorization weather classifications. When considered as a whole, these variables help us develop a more complex picture of how weather affects prospective bike riders' choices.

Categorical and Binary Indicators:
The dataset gains depth with the addition of categorical variables like "weather_code," "season," "is_holiday," and "is_weekend." These indicators make it possible to investigate the ways in which various categories and binary conditions influence the fluctuations in bike sharing numbers. For example, the dataset makes a distinction between weekdays and weekends, holidays and ordinary days, and several weather seasons.
In summary, the dataset stands as a valuable resource for unraveling the complexities of bike sharing dynamics, providing a foundation for data-driven insights that can inform sustainable practices and strategic business decisions in the realm of urban mobility.

Data Exploration and Data Insights
•	Python was used to explore the data and discover the data summary.

•	Splitting the "timestamp" variable into two distinct columns with the name’s "date" and "time".

•	found the missing values in the dataset and the type of data for every variable. Since the dataset 
•	contained no missing values, and the data had previously been cleansed.

•	detected the relationship between the variables using a correlation matrix.

![image](https://github.com/Samarpanb8/-London-bike-sharing-dataset./assets/158126923/11ec6abc-240a-44f7-979f-892254f1ea45)
