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
The lowest average temperature by month is -3 degrees celcius while the highest is 22 degrees celcius.There is a consistent rise in temperature from January to July then a consistent drop from July to December.
### Dew Point Temp:
* Overall Trend: The values start in the negative during the winter months, increase through spring and summer, and then decrease again as winter approaches.
* Lowest Dew Point: The lowest dew point occurs in January (-12.29°C), suggesting very dry air during the winter, which is typical for colder months.
* Highest Dew Point: The highest dew point is in August (15.64°C), indicating more moisture in the air during late summer.
**Seasonal Variation:**
* Winter (Jan - Mar): The dew point temperatures are negative, indicating cold and dry conditions.
* Spring (Apr - Jun): The dew point begins to rise, indicating an increase in moisture as the weather warms.
* Summer (Jul - Sep): The dew point peaks in August, suggesting a warm and humid period.
* Fall (Oct - Dec): The dew point gradually decreases, with temperatures dipping back into negative territory as winter approaches.
### Humidity:
* Overall Trend: The line chart shows how average humidity varies over the year. Based on the values, there's a noticeable fluctuation in humidity throughout the year.
* Lowest Humidity: The lowest average humidity appears to be in April (56.15%), indicating a potentially drier period during the spring.
* Highest Humidity: The highest average humidity is in December (81.30%), which might suggest a more humid winter season.
* Seasonal Variation: There’s a general rise in humidity from spring (April) to early summer (July), a slight dip in late summer (August), and then another rise through the fall and early winter.
