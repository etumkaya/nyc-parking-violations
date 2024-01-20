# About the Project

This project begins with ingesting the NYC Parking Violations data from 01-July-2022 to 30-June-2023. It is a freshly launched dataset which can be found on [NYC Open Data Portal](https://data.cityofnewyork.us/City-Government/Parking-Violations-Issued-Fiscal-Year-2023/869v-vr48). It has more than 20 million rows and 40 columns. Cleaning, analyzing and visualising this large dataset from different angles was the inital part of the work, grouping it by date and hour features followed. 

Soon after, I ingested another dataset containing hourly weather data for respective dates. Cleaning this dataset was once again crucial before merging it with Parking Violations. This merge let me answer an important question I had planned to ask to my dataframe prior to starting my analysis: "Are weather conditions, spesifically rain, assosicated with the number of parking violations?". I approached this question from various perspectives to find the answers I needed. Although the results surprised me, I believe I can say that I was content with my findings. 

Last part of the project consisted of training a machine learning model to predict hourly parking violation counts. It was mostly about preparing the features to be trained and trying different algorithms. 

Almost every code I wrote is followed by my comments on what I did, how I did it and the difficulties I had. I tried to be as open as I could during this whole project. 

My problems which I set out to solve, how I dealt with them, the difficult parts, things I couldn't perform and the reasons of all can be found at the bottom of this notebook, below the project. I also included a section where I gave brief information about the resources I used and the time it took for me to finish this project. 
