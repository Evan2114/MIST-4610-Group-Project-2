# MIST-4610-Group-Project-2

## Team Name:
39217 Group 8

## Team Members:
1. Ryan Alford [@Axeophone](https://github.com/Axeophone)
2. Khushi Patel [@khushipatel45](https://github.com/khushipatel45/MIST-4610-Group-Project-2)
3. Evan Andersen [@Evan2114](https://github.com/Evan2114)
4. Elizabeth Carlin [@elizabethcarlin](https://github.com/elizabethcarlin)
5. Ethan Bowen [@EthanB57](https://github.com/EthanB57)
6. Purvi Nandakumar [@pdn9874](https://github.com/pdn9874)

## Description of Dataset:
The dataset selected represents HIV/AIDS diagnoses by 'Neighborhood', 'Sex', and 'Race/Ethnicity' for New York City, which we found through the website https://catalog.data.gov/dataset. The time frame of the data spans from years 2010 until 2021 with 'Year' representing another primary column in the dataset. However, the years 2010 through 2015 did contain frequent gaps in data and empty/null values. In addition to the columns aforementioned above, the other columns in the dataset include 'Borough', 'Total Number of HIV Diagnoses', 'HIV Diagnoses per 100,000 Population', 'Total number of Concurrent HIV/AIDS Diagnoses', 'Proportion of Concurrent HIV/AIDS Diagnoses Among All HIV Diagnoses', 'Total Number of AIDS Diagnoses', and 'AIDS Diagnoses per 100,000 Population'. The total numbers were reflected in integers, the diagnoses per 100,000 population were reflected as decimals, and the proportion statistics were reflected as percentages relative to all the diagnoses. We chose this dataset because we liked how the data contained a lot of variation among different key groups, statistics specific to HIV and AIDS only, and a combination of the two. After careful consideration, we knew we could provide useful insights into the specific data domains that are highly impacted by these diseases.

## Question 1:
Question: 

What is the total number of HIV, AIDS, and Concurrent diagnoses in the state of NY over the period provided by the data? For any given spikes, what was the distribution amongst boroughs for concurrent diagnoses?

Importance:

The first part of this question is interesting because it enables one to determine if there is any strong, positive correlation between individual HIV and AIDS diagnoses and concurrent diagnoses. From this visualization, the interpreter could form conclusions that HIV and AIDS is a collective epidemic, and both diseases must be approached with a similar aid approach and an equal focus on prevention of future cases. The second part of the question is important because it provides useful insights into which boroughs of New York City are experiencing the highest concurrent rates of HIV and AIDS. As a result of this information, New York City officials could gain a deeper understanding into where the specific HIV and AIDS pain points are located in the city, and be able to devote additional aid and resources to the borough(s) with the greatest need.


First Visual:

<img width="930" alt="Screen Shot 2023-12-04 at 10 40 44 AM" src="https://github.com/Evan2114/MIST-4610-Group-Project-2/assets/145038467/800dc6b5-3fe0-4236-b0ac-0df7ff9675ad">

Analysis and Results:

From our visualization of the change over time of the total number of HIV, AIDS, and Concurrent diagnoses in the state of NY, there is a clear relationship between the total number of HIV, AIDS, and Concurrent diagnoses. While it is not guaranteed that HIV will progress into AIDS, there seems to be a positive relationship between the total number of HIV and AIDS cases, meaning that when one increases, so does the other. Therefore, we decided to use the concurrent number of cases to do a deeper dive into the distribution of cases amongst NYC boroughs. 


Second Visual:

<img width="875" alt="Screen Shot 2023-12-03 at 12 58 27 PM" src="https://github.com/Evan2114/MIST-4610-Group-Project-2/assets/145038467/b7fa5930-839d-47d8-a1a1-19aaf8d9c2f0">

Analysis and Results:

We focused on the 2018 to 2021 time frame as there was a clear spike resembling the data from the first chart in year 2020 for all three figures. For the instance of this visualization, we looked into the distribution amongst concurrent cases. The graph shows that Brooklyn had the largest spike in 2020 among the boroughs during this time frame. This data also provides insight into how the COVID-19 pandemic led to a sudden surge in HIV and AIDS diagnoses, and the year appears to be a relative outlier for the curve in the future. Additionally, we found it unique how the concurrent results immediately dropped the following year (2021) after COVID-19's peak in 2020 and returned to levels that closely resembled pre-pandemic results. 

## Question 2:
Question: 

What is the distribution of the number of concurrent HIV/AIDS diagnoses amongst the various neighborhoods of NYC? What is the distribution amongst race and sex for the neighborhood with the most cases?

Importance:

The first part of the question is important because it builds upon our analysis in the second part of question 1 by figuring out the specific neighborhoods that have the highest number of concurrent diagnoses. As a result, New York City officials could utilize this visual to identify the neighborhoods with the highest numbers and devote additional aid and attention on prevention and reduction of diagnoses in these areas. On the alternative perspective, New York City officials could also use this visual to identify the neighborhoods with the lowest number of diagnoses and do a deeper analysis into the factors, such as sexual reproductive education or increased contraception availability, that contribute to a lower prevalance of cases. Then, city officials could use this data to implement new strategies and funding into the higher risk neighborhoods to prevent these higher diagnostic rates in the future. The second part of this question is also significant because it analyzes two key demographic factors, race and sex, of the NYC neighborhood with the highest number of concurrent cases. From this visual, the interpreter could gain insight into which groups are being impacted the most by this epidemic in this specific region, which may also lead into other underlying factors, such as economic disparity or a poor education system, that are causing these groups to be highly affected.

First Visual:

<img width="929" alt="Screen Shot 2023-12-04 at 10 25 44 AM" src="https://github.com/Evan2114/MIST-4610-Group-Project-2/assets/145038467/d0495847-4da9-4a33-80b3-265f270e193c">
<img width="985" alt="Screen Shot 2023-12-04 at 10 26 46 AM" src="https://github.com/Evan2114/MIST-4610-Group-Project-2/assets/145038467/087f8fbb-0bd2-41ab-87bb-a7e63ce010f6">
<img width="984" alt="Screen Shot 2023-12-04 at 10 27 14 AM" src="https://github.com/Evan2114/MIST-4610-Group-Project-2/assets/145038467/67217fc7-03cc-4dff-b1c9-3198f49555c9">

Analysis and Results:

New York City has many neighborhoods, and as such, modeling the number of cases by location is a useful metric. By comparing these totals, we can identify areas that contain higher amounts of diagnoses. From our output, it seems that Bedford, East Flatbush, High Bridge, Fordham, and Crown Heights could be worthy of further study. We opted to drill down on a neighborhood with a high amount of diagnoses to find out more information about the specific demographic factors, race and sex, that may play a role in the higher rate. 


Second Visual:
<img width="898" alt="Screen Shot 2023-12-04 at 10 28 30 AM" src="https://github.com/Evan2114/MIST-4610-Group-Project-2/assets/145038467/a8476de1-6d2f-4fcc-acd8-5d1337372e5c">

Analysis and Results:

For this visual, we looked into the neighborhood, Bedford Stuyvesant - Crown Heights, and created a heat map contrasting Race and Sex. The results of the heatmap were insightful and interesting. Males of every group recorded had higher amounts of diagnoses than Females of all groups, such that for the White, Asian/Pacific Islander, and Other identifying groups, the Female demographic did not show up on the visualization. In terms of Race, two groups have significantly higher diagnosis numbers than the rest: Black and Hispanic/Latino. These statistics are corroborated by a study conducted from 2014-2018 by the New York City Department of Health and Mental Hygiene. This study found that Black and Latino/Hispanic people accounted for 80% and 90% of new HIV diagnoses in men and women, respectively, in NYC in 2018 (Pg. 15). This study also identified Crown Heights as one of the 3 highest diagnoses count neighborhoods in 2018, which corroborates our choice of neighborhood to dril down (Pg. 34).

HIV in New York City 2014 - 2018:
https://www.nyc.gov/assets/doh/downloads/pdf/dires/hiv-aids-overall.pdf

## Manipulations Applied to Dataset
The primary manipulation applied to our data is that we removed aggregate records to avoid double counting. We found that the columns 'Race', 'Sex', 'Borough', and 'Neighborhood' all had aggregate records with totals that we filtered out before the Tableau visualizations. For example, in the 'Sex' column, the data collectors sometimes grouped together male and female results, which they reflected as 'All' in the dataset. Additionally, we filtered out years 2010 through 2015 to only the years 2016-2021 because there were significant gaps in data between those earlier years. Additionally, we filtered out data with null entries in Borough, which also occurred in the data collected between 2010 through 2015, due to the fact that this data point was not recorded before 2016.

## Tableau Packaged Workbook
The packaged workbook containing the visualizations displayed above is also attached to this repository.
