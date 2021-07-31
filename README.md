# Project1: Criminal Data Analytics with Python
This is Project 1 in UCI Data Analytics Bootcamp
****
Our final versions of data, notebooks and outputs can be found in the 'main' folder. 

Our final versions of graphs and plots can be found in the 'Graphs and Plots' folder. 

Our observations can be found as a txt file in the master branch. 
****
In this project, our group utilizes public data from the city of LA open database to analyze crime data between 2019 and 2020 to better understand if there is an impact of COVID-19 on the amount of criminal cases reported. Our hypothesis is that in 2020, there were less reported criminal cases than in 2019 due to COVID-19. To test our hypothesis and to make sense of our data, we conducted analyses on different trends in criminal activities between the two years relating to victim demographics, areas most affected by crimes, and the change in criminal offenses.
There were many steps taken to ensure that we have the cleanest working data: First we noticed that in the "Victim's Age" column, there were a few invalid results such as the ages being listed as 0 and negative numbers. We would understand if age being 0 could mean the victim is a baby but we believe any negative number is invalid data so we made sure to disregard any reports that contains such results in our age group analysis. Then we eliminated potential outlier data that belong to any timeframe outside of between 1-1-2019 and and 12-31-2020.   
The tools we utilized are pandas to manipulate and clean data, matplotlib to create visualizations and graphs, API calls using Google API for our heatmap, and csv reading to extract data from the source. 
From this project, we should be able to observe data trends to draw conclusions of COVID-19's impact on criminal activities within the city of LA and also view the changes in crime itself between 2019 and 2020.  
