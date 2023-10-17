# Project-1-Data-Analysis-of-Singapore-Rainfall

# Problem Statement

CEO of Otteri Wash & Dry, a self-service laundry , in Singapore branch wanted to optimize company's business in term of revenue gathering and cost-saving to rely on local climate conditions. So he started to explore monthly climate statistics from Jan 1984 to Aug 2022 in order to initiate annual strategic planning.

# Data dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|month|string|rainfall-monthly-number-of-rain-days|Datetime (Month) "YYYY-MM"| 
|no_of_rainy_days|int|rainfall-monthly-number-of-rain-days|Number of Rain Days in the Month| 
|total_rainfall|float|rainfall-monthly-total|Monthly Total Rainfall(Millimetre)|
|maximum_rainfall_in_a_day|float|RainfallMonthlyHighestDailyTotal|Highest Daily Rainfall in the Month(Millimetre)| 
|mean_rh|float|RelativeHumidityMonthlyMean|Monthly mean relative humidity(%)| 
|mean_sunshine_hrs|float|SunshineDurationMonthlyMeanDailyDuration|Monthly Mean Daily Sunshine Duration(Hours)| 
|mean_temp|float|SurfaceAirTemperatureMonthlyMean|Surface Air Temperature - Monthly Mean(Degree Celsius)| 
|temp_mean_daily_min|float|SurfaceAirTemperatureMonthlyMeanDailyMinimum|Monthly Mean Daily Minimum Temperature(Degree Celsius)| 
|temp_mean_daily_max|float|SurfaceAirTemperatureMonthlyMeanDailyMaximum|Monthly Mean Daily Maxumum Temperature(Degree Celsius)|
|month_name|string|Added column|Name of the month e.g. Jan, Feb|
|year|int|Added column|Year ( B.C.) | 
|moonsoon_type|string|Added column|To distinguish the type of moonsoon season by month ( NE,SW,None) | 


# Summary and Recomendation

By the analysis, for Northeast Monsoon and inter_monsoonal 2 are the wettest period ,The CEO should go for ‘forward-strategy’ in order to gather revenues and new customers as the high rainfall and humidity, people might need an instant solution when drying clothes themselves is difficulty, while for Southwest Monsoon and inter_monsoonal 1, The CEO should aim to ‘backward-strategy’ in order to maintain or decrease the cost and retain customers with CRM strategies as lower rainfall and high temperature with longer sunshine duration which can give convenience when drying clothes outdoor.
