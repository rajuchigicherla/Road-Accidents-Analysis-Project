# Road-Accidents-Analysis-Project

## About the Project

In a world where road accidents claim millions of lives and leave countless others injured, this project stands as a testament to my analytical and visualization skills. According to the World Health Organization (WHO), road accidents cause 1.3 million deaths globally each year, with 20 to 50 million people sustaining injuries. The sheer magnitude of these numbers compelled me to embark on this project, where I explore accident hotspot locations, casualty analysis, and the underlying causes of these accidents. Ultimately, I aim to deliver valuable insights to relevant stakeholders, empowering them to implement safety measures and minimize road accidents.

To learn more about road traffic injuries, refer to the WHO fact sheet: [Road Traffic Injuries](https://www.who.int/news-room/fact-sheets/detail/road-traffic-injuries#:~:text=Approximately%201.3%20million%20people%20die,pedestrians%2C%20cyclists%2C%20and%20motorcyclists)

Since the Dataset is too large to upload in the github. So please have a look [Here](https://docs.google.com/spreadsheets/d/1cBf5lJ1ZV6rgICWeml3QNkS93LwFKwKr/edit?usp=sharing&ouid=104163897018162368239&rtpof=true&sd=true)

Please Visit here to see the live Dashboard:[Here](https://www.novypro.com/project/road-accident-analysis-power-bi)

## Steps in the Project 



- Requirement Gathering/ Business Problem
- Stakeholders in the Project
- Understanding of the Data
- Data Cleaning
- Data processing
- Data Modelling
- Data Visualization and Dashboard Building
- Insights




## Requirement Gathering/ Business Problem



The clients want to create a Road Accident Dashboard for the years 2021 and 2022 so that they can have insight into the below requirements -



Primary KPI - Total Casualties and Total Accident values for the current year and YOY growth.


Primary KPIs - Total Casualties by Severity for the current year and YOY growth.
 

Secondary KPIs - Total casualties concerning the vehicle type for the current year.


Monthly trend showing the comparison of casualties for the current year and the previous year.


Casualties by road type for the current year.
﻿

Current year Casualties by Area/Location & by Day/ Night.


Total Casualties and Total Accidents by Location


Stakeholders in the Project



The following are some key stakeholders in the project. Stakeholders are nothing but the users of the dashboard.



**Ministry of Transport**



**Road Transport Department**



**Police Force**



**Emergency Services Department**



****Road Safety Corps**



**Transport operators**



**Traffic Management Agencies**



**Public**



**Media**



## Understanding of the Data



Used Excel to understand the data. The dataset contains 308 thousand records in 21 columns. Finally, loaded the data into Power BI.



## Data Cleaning 



After understanding the data, I identified some outliers in the severity column and replaced them with correct values using Power Query Editor.



## Data Processing



If any date column is present in the data it is better to create a date column to play with the dates. Hence we created a date table "Calender" using time intelligence functions.



## Data Modelling



Created a one-to-many relationship between the Calender table and our Accident data table



## Data Visualization and Dashboard Building

First of all created background for our report using PowerPoint according to our KPI requirements.



After that created visualizations for the stakeholder requirements using different visualizations like Bar charts, Area Charts, Donut charts, and Geolocation Maps.



Finally, applied slicers and filters to prepare the report.



## Key Insights



- Total current year casualties are 195.7K which is ~12% less than the previous year
- Total current year Accidents are 144.4K which is ~12% less than the previous year
- Total casualties for Fatal, Serious, and Slight severity types for the current year are 2.9K, 27K, and 165.7K respectively.
- When compared to the previous year all three severity-type casualties decreased by 33.3%,16.2%, and 10.6% respectively.
- When compared to the various vehicle type casualties only car type contributed more than 50%.
- Nearly 3/4th of casualties were caused in daylight only.
- Single Carriageway road caused 145K casualties i.e. nearly 50% of the total casualties.
- Out of the total 62% of the casualties happened in urban areas
 

## Recommendations

- Based on the insights derived from the road accident dashboard, the following recommendations can be made to the stakeholders:

- Ministry of Transport, Road Transport Department, and Traffic Management Agencies should work together to implement stricter speed limit regulations during the daytime. As 3/4th of casualties occurred during daylight, it is necessary to enforce speed limits to reduce accidents during this time.


- Road Safety Corps and Emergency Services Department should focus on providing timely assistance to victims during accidents. They should implement faster emergency response measures, including quicker ambulance services and efficient communication systems.


- Police Force should enforce traffic laws and implement stronger penalties for traffic violations, especially those related to speeding and reckless driving.


- Transport operators should conduct regular maintenance and safety checks on their vehicles to ensure that they are in good condition and meet safety standards. They should also provide regular training to their drivers on safe driving practices and road safety rules.


- Public awareness campaigns should be conducted to educate people about road safety, including the importance of wearing seat belts, not using mobile phones while driving and obeying traffic signals.


- Media should play an active role in promoting road safety by covering stories related to road accidents and highlighting the importance of safe driving practices.

By implementing these recommendations, the stakeholders can work towards reducing the number of road accidents and casualties, thus making our roads safer for everyone.


## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request
