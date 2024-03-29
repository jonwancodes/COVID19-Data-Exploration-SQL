# COVID19-Data-Exploration

## Objective: 
To perform an exploratory analysis of the COVID-19 pandemic using BigQuery / SQL, and gain insights into the pandemic's death counts and vaccination statuses.

With BigQuery, I utilized Joins, CTE's, Temp Tables, Windows Functions, Aggregate Functions, Creating Views, and Converting Data Types.

## Data:
Link to dataset: https://ourworldindata.org/covid-deaths

Dataset contains data from January 8th 2020 to March 6th 2023.


## Data Cleaning:
Split the large dataset from the website into two separate .csv files in order to practice joins with SQL and make the large dataset more managable.

## Link to view my data exploration on COVID-19 dataset:
https://console.cloud.google.com/bigquery?sq=529249657765:c051e94efe9941d5b02e324a8d0c1e3f

SQL Code is also available to view in BigQueryCode.md file



## Data Anaylsis:

As a healthcare worker in the US that worked directly in COVID-19 units and throughout the pandemic, I was able to personally relate to the data I explored. While exploring this data, I found some interesting, yet grim, insights. 

* For example, as of March 6th, 2023, the United States is the number one country with the highest total death count from COVID-19 with 1,122,264 total deaths. Followed by Brazil (699,276 total deaths) and India (530,775 total deaths). According to the data, 30.64% of the population of the United States has had a confirmed case of COVID-19. 

* We can find the percent of each country's population that has received at least one vaccine and the percent of the population that is 'fully vaccinated'. For example, in the United States, about 80% of the population has received at least one vaccine dose and 68% of the population is fully vaccinated.

* On a slightly more positive news, the likelihood of death after contracting COVID-19 in the United States today is 1.08%. However, this is only a general percentage and does not take into account for age, gender, vacccination status, etc. I believe this would be an interesting topic to dive deeper into for future exploration!


## Data Visualization using Tableau:
![Dashboard 1](https://github.com/jonwancodes/COVID19-Data-Exploration-SQL/assets/102621853/4c7e95a8-af31-4342-ab4a-df50aae6b910)

Dashboard can be downloaded and accessed in files or linked below to gain a more detailed analysis
https://public.tableau.com/views/COVID19Dashboard_372023/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link

