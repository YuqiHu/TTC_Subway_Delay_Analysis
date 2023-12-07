# TTC_Subway_Delay_Analysis
The Toronto Transit Commission (TTC) reports as many as 130 different types of delay causes every year. The resilience of the subway system to various contingencies is vital for passenger satisfaction and operational efficiency. This project aims to delve into the transit resilience of the TTC subway system, particularly examining the causes of delays. Our analysis encompasses a comprehensive approach, considering behavioral, political, and technological factors. The findings of this project offer the TTC and policymakers a detailed understanding of the prevailing challenges. 

**Overview of Files**
1. ```Hourly Weather Data.ipynb```: Clean the hourly Toronto Weather CSV Data
2. ```Daily Weather Data.ipynb```: Clean the daily Toronto Weather CSV Data
3. ```Criminal Data and Disorderly Patrons Data.ipynb```: Plot the Criminal Data and Disorderly Patron Data on Toronto Map
4. ```Weather Snow Delay Regression.ipynb```: Attempted regression model based on merged hourly and mean hourly data with weather-related delays
5. ```TTC_delay_data.ipynb```: Clean the TTC_Real_Delay_2014_2023 CSV Data; Exploration Data Analysis for TTC delay data
6. ```TTC_Subway_Delay_Data_API.ipynb```: The API file to access Toronto Open Data
7. ```TTC_schedule.ipynb```: Web scrap the TTC Line 1 and Line 2 schedule for St,George station and Bloor-Yonge station
8. ```TTC_subway_ridership.ipynb```: clean the '' CSV Data
9. ```Twitter.ipynb```: Collect TTC subway delay posts information through Twitter and analysis the posting time

**Overview of Data**:
1. ```Toronto hourly weather data```: CSV file records the Toronto hourly weater data from January 2014 to September 2023
2. ```City of Toronto Weather data```: CSV file records the Toronto Daily weater data from January 2014 to September 2023
3. ```Assault_Open_Data```: CSV file records the Toronto Assault data from January 2014 to September 2023
4. ```TTC_Real_Delay_2014_2023```: Cleaned CSV file records the TTC delay reasons which has delay over i min
5. ```TTC_Real_Delay_2014_to_2023_Cleaned```: Cleaned CSV file records the TTC delay reason
7. ```TTC_subway_ridership_by_lines```: CSV file records TTC subway ridership by each subway line
8. ```Subway_Map```: CSV file records TTC subway stations and corresponding coordination system
9. ```ttc-subway-delay-codes```: xlsx file records TTC subwaydelay code and corresponding code description
10. ```TTC_stations```: CSV file records TTC subway station and corresponding subway line

**Overview of Folder**:
1. ```Criminal Data and Disorderly Patrons Data ``` folder: Contains the geometry SHP, assult open data CSV and Criminal Data and Disorderly Patrons Data.ipynb
2. ```Daily Weather Data ``` folder: Contains CSV file records the Toronto Daily weater data from January 2014 to September 2023 and Daily Weather Data.ipynb
3. ```Hourly Weather Data``` folder: Contains CSV file records the Toronto Hourly weater data from January 2014 to September 2023 and Hourly Weather Data.ipynb
4. ```Output``` folder: Contains CSV files record cleaned TTC subway delay reasons and record TTC subway ridership by each subway line 
5. ```TTC_delay``` folder: Contains CSV files record the TTC subway delay data from January 2014 to September 2023, and the delay code and code description
6. ```TTC_ridership``` folder: Contains CSV files record the TTC subway ridership data from 2014 to 2022, and subway stations information

**Links to Medium Articles:**
* Web Scraping Dynamic Content with Selenium: TTC Subway Schedule - https://medium.com/@hyq200117/web-scraping-dynamic-content-with-selenium-ttc-subway-schedule-6b34632ed4e7](https://medium.com/@hyq200117/web-scraping-dynamic-content-with-selenium-ttc-subway-schedule-6b34632ed4e7




**Workflow:**
![Overall Illustration](https://github.com/YuqiHu/TTC_Subway_Delay_Analysis/raw/20231109-nicole-regressionmodel/Overall_Illustration.png)





