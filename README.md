## WEATHER DATA EXPLORATORY DATA ANALYSIS
The aim of the project is to perform exploratory data analysis to uncover interesting patterns, insights, and potential anomalies within the weather dataset.
It is a continuation of the [week 1](https://github.com/MorganTheAnalyst/Lux-Academy-Week-1-Project-Python-Sql-for-Data-Science-and-Analysis) project.
### Data Overview and Cleaning:
The dataset has  8784 entries and 8 columns which are;
* Date/Time </br>
* Temp_C </br>
* Dew Point Temp_c </br>
* Rel Hum_% </br>
* Wind Speed_Km/h </br>
* Visibility_Km </br>
* Press_Kpa </br>
* Weather </br>
The dataset do not have any missing, null values or duplicate records.
### Weather Patterns and Trends
### Temp:
* **Overall Trend:** The line chart shows a clear seasonal pattern, with temperatures starting low in the winter months, rising through the spring and summer, and then decreasing again as winter approaches.
* **Lowest Temperature:** The lowest average temperature occurs in January (-7.37°C), which is typical for winter.
* **Highest Temperature:** The highest average temperature is in July (22.79°C), indicating the peak of summer warmth.
* **Seasonal Variation:**</br>
  * Winter (Jan - Mar): The temperatures are below freezing, with January being the coldest month.
  * Spring (Apr - Jun): The temperatures rise steadily, indicating a warming trend as the season progresses.
  * Summer (Jul - Sep): Temperatures peak in July, with slight cooling beginning in September.
  * Fall (Oct - Dec): The temperatures gradually drop, with November and December showing a return to near or below freezing     conditions.
### Dew Point Temp:
* Overall Trend: The values start in the negative during the winter months, increase through spring and summer, and then decrease again as winter approaches.
* Lowest Dew Point: The lowest dew point occurs in January (-12.29°C), suggesting very dry air during the winter, which is typical for colder months.
* Highest Dew Point: The highest dew point is in August (15.64°C), indicating more moisture in the air during late summer.</br>
* **Seasonal Variation:**
  * Winter (Jan - Mar): The dew point temperatures are negative, indicating cold and dry conditions.
  * Spring (Apr - Jun): The dew point begins to rise, indicating an increase in moisture as the weather warms.
  * Summer (Jul - Sep): The dew point peaks in August, suggesting a warm and humid period.
  * Fall (Oct - Dec): The dew point gradually decreases, with temperatures dipping back into negative territory as winter        approaches.
### Humidity:
* Overall Trend: The line chart shows how average humidity varies over the year. Based on the values, there's a noticeable fluctuation in humidity throughout the year.
* Lowest Humidity: The lowest average humidity appears to be in April (56.15%), indicating a potentially drier period during the spring.
* Highest Humidity: The highest average humidity is in December (81.30%), which might suggest a more humid winter season.
* Seasonal Variation: There’s a general rise in humidity from spring (April) to early summer (July), a slight dip in late summer (August), and then another rise through the fall and early winter.
### Wind Speed:
* **Overall Trend:** The line chart shows the fluctuation of wind speeds throughout the year, with some months experiencing higher winds than others.
* **Highest Wind Speed:** The highest average wind speed is in January (18.11 km/h) and December (17.61 km/h), indicating 
that the winter months might be windier.
* **Lowest Wind Speed:** The lowest average wind speed is in July (11.89 km/h), suggesting calmer conditions during mid-summer.
* **Seasonal Variation:** </br>
  * Winter (Jan - Mar): Wind speeds start high in January and then decrease in February and March.
  * Spring (Apr - Jun): Wind speeds fluctuate, with a peak in April (17.37 km/h) and then a decrease in May and June.
  * Summer (Jul - Sep): The wind speed is lowest in July, gradually increasing through August and September.
  * Fall (Oct - Dec): Wind speeds rise in October and November, with another peak in December.
### Visibility:
* **Overall Trend:** The line chart will show the variation in visibility throughout the year, with periods of higher and lower visibility.
* **Highest Visibility:** The highest average visibility occurs in July (33.66 km), indicating that mid-summer tends to have the clearest conditions.
* **Lowest Visibility:** The lowest average visibility is in December (19.73 km), suggesting that winter months, particularly December, might have more foggy or hazy conditions, reducing visibility.
* **Seasonal Variation:**</br>
  * Winter (Jan - Mar): Visibility starts relatively low in January (22.10 km) and increases through February and March.
  * Spring (Apr - Jun): Visibility continues to improve, peaking slightly in June (32.10 km).
  * Summer (Jul - Sep): The visibility is highest in July and then slightly decreases in August and September.
  * Fall (Oct - Dec): Visibility begins to drop in October and November, reaching the lowest point in December.
### Pressure:
* **Overall Trend:** The line chart will show the variation in atmospheric pressure throughout the year, with fluctuations in different months.
* **Highest Pressure:** The highest average pressure occurs in November (101.66 hPa), indicating a potential increase in high-pressure systems during this time, often associated with more stable weather conditions.
* **Lowest Pressure:** The lowest average pressure is in April (100.72 hPa), suggesting the presence of low-pressure systems, which can be associated with unsettled weather, such as storms or rain.
* **Seasonal Variation:** </br>
  * Winter (Jan - Mar): Pressure starts moderate in January, slightly increases in February, and reaches a higher value in 
    March (101.34 hPa).
  * Spring (Apr - Jun): Pressure dips in April and May, with a slight increase in June.
  * Summer (Jul - Sep): Pressure remains relatively stable, with minor fluctuations through July, August, and September.
  * Fall (Oct - Dec): Pressure increases in October, peaks in November, and remains high in December.
### Anomalies and Unusual Patterns:
#### 1. Temperature:
Anomaly: There doesn’t appear to be a significant anomaly in the temperature data, as the values follow a typical seasonal pattern with colder winter months and warmer summer months.
Conclusion: No major anomalies observed in temperature data.
#### 2. Dew Point Temperature:
Anomaly: The dew point temperature in April (-1.93°C) is significantly lower than in May (8.08°C) and March (-3.49°C).
Possible Reason: This could be due to an unseasonably cold spell in April, where the air was dry and temperatures were low, causing a sharp decrease in the dew point.
#### 3. Humidity:
Anomaly: The humidity is relatively low in April (56.15%) compared to the surrounding months.
Possible Reason: April might have experienced unusually dry conditions, possibly due to a lack of precipitation or an increase in temperature, which can lower humidity levels.
#### 4. Wind Speed:
Anomaly: The wind speed in January (18.11 km/h) and December (17.61 km/h) is notably higher than in the other months, especially July (11.89 km/h).
Possible Reason: The higher wind speeds in winter could be due to stronger storm systems, as winter often brings more dynamic weather patterns with strong winds. July’s lower wind speed might be due to more stable, calmer summer weather.
#### 5. Visibility:
Anomaly: The visibility in December (19.73 km) is much lower compared to the summer months like July (33.66 km).
Possible Reason: December’s low visibility could be due to winter fog, mist, or snow, which are common in colder months and can significantly reduce visibility. The summer months, especially July, typically have clearer conditions with less atmospheric moisture or particulates, leading to higher visibility.
#### 6. Pressure:
Anomaly: The pressure in April (100.72 hPa) is slightly lower compared to March (101.34 hPa) and May (101.06 hPa).
Possible Reason: April might have experienced a significant low-pressure system, which is often associated with stormy or unsettled weather. This could explain the dip in pressure during that month.



Conclusion:
April Anomalies: Both humidity and pressure show anomalies in April, suggesting that this month might have experienced atypical weather conditions, such as a storm system or an unusual cold snap, leading to lower pressure and humidity levels.
December Anomalies: December shows anomalies in visibility and wind speed, potentially due to winter weather patterns like fog, mist, or snow reducing visibility, and stronger winds associated with winter storms.
Winter vs. Summer Patterns: There is a clear contrast between winter and summer months in terms of wind speed and visibility, reflecting the typical seasonal differences where winter brings more dynamic and sometimes harsher weather conditions.
