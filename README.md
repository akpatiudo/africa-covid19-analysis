## AFRICA CONTINENT COVID-19 DATA ANALYSIS AS OF JANUARY 2020 TO MAY 2023: AN SQL SERVER (SSMS) AND TEABLU PROJECT

![image](https://github.com/akpatiudo/africa-covid19-analysis/assets/118566096/21444d94-61ac-4851-9b7c-a8a6102d9a5e)

### *INTRODUCTION*
As of May 2023, according to the data analysed the number of confirmed COVID-19 cases in Africa amounted to around 8,630,485,021, 188,807,977 deaths and 2.19% death rate. The African continent first came in contact with the coronavirus pandemic on February 14th 2020, in the northernmost part, particularly Egypt. Since then, the different governments took severe restrictive measures to try to curb the spread of the disease. However, South Africa, Morocco and Tunisia have the highest population infected respectively in terms of numbers, but in terms of average sum of percentage by population (rate) for the period analysed, Seychelles, Reunion and Mauritius top the chat with 20.82%, 18.26% and 7.90% respectively, South Africa came 10th with 3.89%.
all SQL code used are in this file: SQLcovidFinal.sql

### *STEPS I TOOK TO ARRIVE AT MY DASHBOAD*

The first thing I did was to create a database call ‘portfolio’ and a file call ‘projects’ by following these steps:

1) Right click on database on SQL server

2) Click on new database in the dialogue box fill the name of the database of your choice and click on add, mine was ‘Portfolio’

3) Fill the name of the file, it is the space at the beginning of the last row under database file and click ok, mime was ‘project’

4) Refresh your data base and you will see your portfolio

### *DATA IMPORTATION*

I split the dataset into two different data files which I named “covidDeath$” and “covidVaccinations$” respectively. The two data files were imported into my newly created database. This is to reduce the size of the dataset being analyse at a given time, thus, increasing the speed of executing a task by my SQL Server.

**covidDeath$ table**

![image](https://github.com/akpatiudo/africa-covid19-analysis/assets/118566096/c2f10a36-0a08-497d-80f5-49c1bf49e638)

**covidVaccinations**
![image](https://github.com/akpatiudo/africa-covid19-analysis/assets/118566096/4605f261-5e69-449f-bcb9-6359fe9eb7fa)

### *DATA EXPLORATORY*

All my calculations and 95% of data cleaning were done in SQL server, Tableau was strictly use for visualizationI started by creating a Common Table Expression (CTE), I used this process to select the columns that I needed for this analysis.  KPIs

### *KPIs Considered*

1  looking at highest cases vs Country

2  looking at highest cases vs location

3  Showing total covid cases in africa by Country

4  showing pecentage of total death by number of cases

5  SHOWS POPULATION GOT COVID by Countries

6  looking at Countries that managed their caseds in the hospital

7  Lookig at new cases vs new death

8  Looking at poeple vaccinated: showing percentage of total vaccinated by populationand poeple full vaccinated by population

9  showing pecentage  of people not fully vaccinated

10  showing pecentage  of people fully vaccinated

### DATA VISUALIZATION 
**Covid_29 Dashboard**

![image](https://github.com/akpatiudo/africa-covid19-analysis/assets/118566096/64db9792-9311-46ac-a7f3-050f0536af7b)

### *INSIGHTS*

From the visualization, North African countries Top the chat in death by population rate: Sudan, Egypt and Liberia were on top with 6.39% death in 2020, 7.08% in 2021, 7.65% in 2022 and 7.86% 2023 for Sudan; Egypt has 4.81% for 2023, 4.88% for 2022, 5.75% for 2021 and 5.41% 2020; Liberia has 3.64% in 2023, 3.85% in 2022, 4.75% in 2021 and 6.91% in 2020.

South African had the highest cases recoded, this could be as a result of temperature falls between June and August, temperature can get as low to -20C In some part of South Africa. At the heel of South Africa, were Morocco Tunisia and Egypt respectively, Ethiopia, Central Africa came 5th.

January, July, August and December where the months that have the highest out break of new cases and January, February July, August, December has the highest records of new deaths. It should be noted that only South Africa and Algeria had record of cases managed in hospital, South Africa have 2694 patients in ICU and 18034 hospital Patient, Algeria has 67 patients in ICU none as hospital patient. This could be as a result of social Stigmatization, Myth and Conspiracy Theories that surrounds the covid-19 outbreak in Africa

Seychelle, Morocco, Tunisia and South Africa top the chart of percentage of people fully vaccinated by population with 53.04%, 33.16%, 30.04% and 23.82% respectively

## *SUMMARY*

The continent, has had about 188,807,977 death cases from 2020 to 2023 according to dataset from www.ourworldindata.org. There was less death in Central and West Africa compare to other part of the continent in that Central Africa did not make the list of top 15 countries with high percentage death rate, West has only one among the top 15 countries.

Some countries with high population had low infection and death rate, this might be as a result of under-reporting of some of the cases in certain countries and the efficient handling of the outbreak in some others. There was low hospital record in the continent, this again could be as a result of pool health facilities, fear and ignorance about the virus that led to conspiracy theories. The vaccination rate did not translate to the population of each country, it was only Seychelle, that has 50% of her population vaccinated.

thanks


