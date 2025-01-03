# Power-BI-Capstone-Project

## Capstone Project – Weather Analysis

### Objective: 
The objective outlines the purpose of the analysis, defining the specific questions or problems that need to be addressed. It serves as the foundation for the entire project, guiding the direction of the analysis and ensuring that all efforts are aligned with the intended outcomes.

### Analysis Scope:
The analysis covers six key aspects: humidity, pressure, temperature, wind direction, wind speed, and weather descriptions. Each factor will be examined to identify trends and anomalies.

### Goal:
The overarching goal is to derive actionable insights from the historical weather data set. These insights will empower stakeholders in sectors like agriculture, energy management, urban planning, and transportation.

### Insights and Recommendations:
The project will generate key insights and actionable recommendations based on the analyzed data. This information will be essential for adapting strategies to cope with changing weather patterns and enhancing decision-making.

### Reports and Presentations:
Findings will be compiled into a comprehensive report, supplemented by data visualizations to illustrate key trends. Presentations will be designed to make the insights accessible and understandable to a wide audience.

## _Interactive dashboards will be employed to visualize complex weather data relationships. This tool will help users grasp insights more effectively, facilitating better planning and decision-making._

![image](https://github.com/user-attachments/assets/e1e00322-cbeb-4b1f-973f-adb652efc151)

### ⌛Valuable Insights:
The project provides critical insights into various weather patterns, which are essential for informed decision-making across multiple sectors. By analyzing factors such as temperature, humidity, and atmospheric pressure, stakeholders can enhance resource management, optimize operational strategies, and improve risk mitigation efforts.

### 🎯Improvement Focus:
A continuous improvement focus is essential for adapting strategies based on evolving weather data and insights. By regularly reassessing methods and practices, organizations can enhance their resilience and effectiveness in responding to weather-related challenges.

### 📍Evaluation of Effectiveness:
Evaluating the effectiveness of strategies involves systematically analyzing outcomes against predetermined benchmarks and objectives. This rigorous assessment process not only identifies successes and failures but also provides insights for continuous improvement and adaptation in response to changing conditions.

### 📈Trend Identification:
Identifying trends in weather data is essential for proactive decision-making, allowing organizations to anticipate changes and adjust their strategies accordingly. This involves analyzing historical data to recognize patterns and anomalies that can inform future actions in sectors like agriculture, urban planning, and disaster management.

### 📑Comprehensive Understanding:
A comprehensive understanding of weather data involves integrating various meteorological factors, historical patterns, and real-time information to inform holistic decision-making. This multifaceted approach allows organizations to develop effective strategies that address the complexities of weather variability and its impacts on different sectors.

### Dataset Description:
This dataset includes data on city attributes, humidity, pressure, temperature, weather descriptions, wind direction, and wind speed for various cities.

## ER Diagram:
![image](https://github.com/user-attachments/assets/3867ae6b-3940-48f0-a2e1-a23a2427db56)

## Key Questions Answered:
- Latitude Analysis: Variation in the distribution of cities across countries in terms of Latitude.
- Humidity Analysis: Variation of Humidity across cities.
- Temperature Analysis: Temperature trend over a period of time.
- Weather condition Analysis: Identification of busiest hours for specific weather condition.
- Wind speed Analysis: Change of wind speed over a course of day.
- Wind Direction Analysis: Visualizes prevailing wind direction for specific city.
- Wind speed and Pressure Correlation: Identification of the relationship between wind spedd and pressure for a specific city.

## Steps
### 1. Data Import and Cleaning:
Imported data using the Get Data option in Excel.
Used Power Query Editor to clean the data, ensuring that each table is properly structured and formatted for analysis.

### 2. Data Preparation:
Loaded six tables: city_attributes, country, city_lookup, final_fact, date_lookup and time_lookup
Joined the tables based on relevant keys like City_id,Country_id, date_id and time_id

### 3. Dynamic Dashboard:
Created multiple dynamic charts to visualize weather factors.
Added slicers for easy filtering by cities,weather conditons etc.

### 4. Visuals:
Used different types of charts (Bar, Line, Radial and Rose) to visualize:
Temperature trends.
Correlation between wind speed and pressure.
Variation of Humidity and Wind speed across cities and time.
Busiest hours of Weather condition.

## Conclusion:
Based on the analysis, the climatic factors remain largely unaffected by latitude variations, and no significant correlations explain the clustering of cities with similar geographic coordinates. Cities exhibit stable temperatures over time without unusual deviations linked to specific events. However, wind speed and direction are identified as key influencers of severe weather conditions, although no extreme weather events were observed in the provided data. In conclusion, the data suggests overall climatic stability with wind dynamics being a crucial factor in weather severity.


![image](https://github.com/user-attachments/assets/d5408bce-e8fb-4d37-a0d8-67cdf0f66ba2)


