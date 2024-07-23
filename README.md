#  In and Out of the Philippines: A Look in the Current Status of Filipino and Foreign Tourism (Jan - May 2024)

### Overview
<p align="justify">As travel restrictions been waived off and seeing many people in news and social media sharing their travel adventures, I decided to investigate the top countries that most Filipinos visited. In contrast, I also included top nationalities that love to visit the Philippines in order to have a quick picture of the number of tourists (Filipinos and Foreigners) going in and out of the Philippines. To complete this project, I applied the standard procedures done by a DA role starting from Data Acquisition, Data Cleaning and Analysis using MySQL. And to summerize the findings, I then presented the data on a dashboard via Tableau.</p>

 ### Steps
 A. Data Acquisition
- 1. Identify sources and retrieve the data
- 2. Identify questions that I intend to answer after processing the data

     &nbsp;&nbsp;&nbsp;&nbsp;Q1. What were the top countries that most Filipinos have visited starting this year up until the recent data?
     
     &nbsp;&nbsp;&nbsp;&nbsp;Q2. Which foreigners visited the Philippines the most?
     
     &nbsp;&nbsp;&nbsp;&nbsp;Q3. What is the difference in numbers between the Inbound and Outbound tourism.
     
     &nbsp;&nbsp;&nbsp;&nbsp;Q4. How will I present the data in the dashboard that showcase the exchange in tourism between the many countries and the
     
     &nbsp;&nbsp;&nbsp;&nbsp;Philippines without being too much overwhelming?

B. Data Cleaning using MySQL	
- 1. Prepare data for cleaning: Outbound Tourism Data
- 2. Check/Remove Duplicates: Outbound Tourism Data
- 3. Standardize the data: Outbound Tourism Data
- 4. A,B & C Procedure on Inbound Tourism Data
- 5. Merging both the processed Outbound and Inbound data and further cleaning

C. Data Exploration using MySQL
- 1. Identify trends
- 2. Identified data representation limitations
- 3. Solutions to the limitations
- 4. Initial Queries

D. Data Presentation using Tableau (Initial)
- 1. Dashboard Contents
- 2. Dashboard

E. Improvements on Data	
- 1. Adding Longitude and Latitude data for each country and further data cleaning

F. Tableau (Final)
- 1. Updating and creating new charts for the dashboard
- 2. Dashboard
- 3. Resolving previous concerns
- 4. Answering the guide questions

Click here for the [Project Documentation](https://docs.google.com/spreadsheets/d/1lSygxO0qv4ZjTrAea-bsbdSpEFVRgiygHF9ioZUMcaA/edit?usp=sharing) to see the complete details.

### Dashboard

A. Initial: [[Tableau Link]](https://public.tableau.com/views/ALookatFilipinosGoingAbroadVS_ForeignersGoingtothePhilippines/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

![Initial_Dashboard](https://github.com/user-attachments/assets/4d65837e-7282-44d1-a9a7-bbbee598865e)

B. Final: [[Tableau Link]](https://public.tableau.com/views/InandOutofthePhilippinesALookintheCurrentStatusofFilipinoandForeignTourismJan-May2024/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

![Final_Dashboard](https://github.com/user-attachments/assets/204bbad9-0bad-4087-b9e6-89db1e4e1706)


### Findings
Answering the initial questions:

Q1. What were the top countries that most Filipinos have visited starting this year up until the recent data?
 - Based from the data, Hong Kong - SAR was the top destination for the Filipinos so far for this year. With both Japan and Sierra Leone closely behind Hong Kong.

Q2. Which foreigners visited the Philippines the most?
- Based from the data, South Koreans are the top foreigners to visit the country, almost double of that the Americans in the 2nd place. With this amount, it can be observed also that there are double the amount of koreans visiting the Philippines compared to filipinos going to another country.

Q3. What is the difference in numbers between the Inbound and Outbound tourism.
- From the quick summary, we can can see the there were more Filipinos leaving the country vs. foreigners visiting the Philippines. It seems that many Filipinos really took the chance of travelling once the travel ban was lifted. 

Q4. How will I present the data in the dashboard that showcase the exchange in tourism between the many countries and the Philippines without being too much overwhelming?
- With the addition of the flight path feature and additional filters, it made the the whole data presentation more understandable as compared to the initial implementation. The updated dashboard also presented the data in such a way that it can be understood right a way with a customizable feature to let the audience choose which data it wants to display.

### Conclusion
<p align="justify">As the travel ban have been lifted,more and more Filipinos travel abroad, even beating the total number of visiting foreigners in the Philippines. This shows that their is a high demand in abroad travelling, with Hong Kong leading the way and followed by Japan and Sierra Leone. On the other hand, foreign tourism in the Philippines is also high with Sout Korean nationals comprising the majority of the tourist with a staggering 700,000 visitors, almost double the number of vistors from the USA coming in second. These information just proves how tourism is currently booming in the country and by understanding the demand, it can be beneficial to the respective countries as they can adjust their approach in handling their tourism according to such demands.</p>

### Data Source
Data for both [inbound](http://www.tourism.gov.ph/files/2024/tourism_demand/06/06-07/Visitor%20Arrivals%20by%20Country%20of%20Residence%20Jan-May%202024%20(2%20files%20merged).pdf) and [outbound](http://tourism.gov.ph/files/2024/tourism_demand/06/06-14/Outbound/JAN-MAY2024.pdf) tourism data were acquired from the [Department of Tourism of the Philippines](http://tourism.gov.ph/tourism_dem_sup_pub.aspx).

### Tools
For this project, I used MySQL for data cleaning/analysis and Tableau for dashboard making.

### Files

Project Documentation: Contains all the steps and details done in completing the project.

SQL Query: Contains the SQL query used for cleaning and data exploratory.

SQL Query Output Data: Contains the output data.

Dataset: Contains the tourism data document acquired from the [Department of Tourism of the Philippines](http://tourism.gov.ph/tourism_dem_sup_pub.aspx).

[[Files Link]](https://drive.google.com/drive/folders/1s8uzQq3bR_D9iZpW6AC80DAyTVRlilS1?usp=sharing)



