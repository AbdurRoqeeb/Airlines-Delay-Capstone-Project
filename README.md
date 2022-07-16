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
- Weather is the major cause of plane crash, which accounts for more than 1,600 of the total crashes.
- 1972 is the year with the highest amount of crashes (104). This is also the year with the highest fatalities.
- The top three countries where crashes occur are USA, Brazil and Russia respectively.
- Most crashes occur in December, closely followed by January and August.
- Aeroflot is the operator that has experienced crashes the most, closely followed by the US Air Force.

----
## Reccommendations
1. Weather forecast should be properly done before flights take off.
2. Special attention should be given to countries where most crashes has occured in order to reduce further occurrences.
3. Airline operators should make necessary checks to ensure the plane is in good shape so as to prevent crashes due to engine failure.

----
## Limitations
Although the Summary column provided some information about the reason for some crashes, it is not sufficient for some others.
