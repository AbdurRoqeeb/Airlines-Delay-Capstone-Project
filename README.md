# Airlines-Delay-Capstone-Project
Analysis and Visualization of Airlines Delay data.

----
## Introduction
This project is the first capstone project of the [Data Analysis in Power BI track](https://aka.ms/30DLDATLandingPage) of NG 30 Days of Learning convened by Olanrewaju Oyinbooke ([@TheOyinbooke](https://twitter.com/TheOyinbooke)) for Nigerian students in  a bid to effectively utilise the ongoing ASUU strike.
This documentation includes:
- Project requirements
- Data Sourcing
- Data Cleaning
- Findings
- Reccommendations
- Limitations

----
## Project Requirements
The goal of analysing this data is to get insights about airlines delays:
1. The total number of times that there has been flight delays
2. The proportion of delayed and undelayed flights
3. Day of the week with the highest flight delays.
4. Airline with the highest number of delays.
5. Airport from which flights were delayed the most

----
## Data Sourcing
Data used for analysis was scrapped from [Kaggle](https://www.kaggle.com/datasets/jimschacko/airlines-dataset-to-predict-a-delay) and cam=n also be found in [this](https://github.com/theoyinbooke/30Days-of-Learning-Data-Analysis-Using-Power-BI-for-Students) Github repository.

----
## Data Cleaning
The data was relatively cleaned from source but some modifications were made to some of the columns:
- The DayOfWeek column contained numbers of the days of the week. I used the replace value feature to replace the number with their respective names.
- The Delay column contained numerical values (0 and 1). I changed it to text data by replacing 0 with "Not delayed" and 1 with "Delayed"
----
## Findings
Analysis and visualization was done with Microsoft Power BI and the following insights were derived:
- The total number of delayed flights is above 260,000. This represents about 44.56% of the total number of flights.
- Most flight delays occurred on Tuesday, Wednesday and Thursday, in that order.
- The airline with the highest number of delays is WN (SouthWest Airlines).
- The airline with the highest average delay time is FL (Florida Air Cargo).
- ATL (Hartsfield-Jackson Atlanta International Airport - Georgia) is the airport from whch flights get delayed most.

----
## Reccommendations
1. WN (SouthWest Airlines) should put in measures to reduce flight delaysby their airlines
2. A deeper investigation should be done to know what causes the increased number of flight delays on Tuesday, Wednesday and Thursday.

----
## Limitations
The period of time for the collection of the dataset was not available. This made it difficult to connect this dataset to other datasets such as weather information over a specific period of time which could help in further investigating the reasons for flight delays.
