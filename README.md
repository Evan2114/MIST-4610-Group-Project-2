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
Question: What is the total number of HIV, AIDS, and Concurrent diagnoses in the state of NY over the period provided by the data? For any given spikes, what was the distribution amongst boroughs?

<img width="930" alt="Screen Shot 2023-12-04 at 10 40 44 AM" src="https://github.com/Evan2114/MIST-4610-Group-Project-2/assets/145038467/800dc6b5-3fe0-4236-b0ac-0df7ff9675ad">

<img width="875" alt="Screen Shot 2023-12-03 at 12 58 27 PM" src="https://github.com/Evan2114/MIST-4610-Group-Project-2/assets/145038467/b7fa5930-839d-47d8-a1a1-19aaf8d9c2f0">


## Question 2:
Question: What is the distribution of the number of concurrent diagnoses amongst the various neighborhoods of NYC? What is the distribution amongst race and sex for the neighborhood with the most cases?

<img width="929" alt="Screen Shot 2023-12-04 at 10 25 44 AM" src="https://github.com/Evan2114/MIST-4610-Group-Project-2/assets/145038467/d0495847-4da9-4a33-80b3-265f270e193c">

<img width="985" alt="Screen Shot 2023-12-04 at 10 26 46 AM" src="https://github.com/Evan2114/MIST-4610-Group-Project-2/assets/145038467/087f8fbb-0bd2-41ab-87bb-a7e63ce010f6">

<img width="984" alt="Screen Shot 2023-12-04 at 10 27 14 AM" src="https://github.com/Evan2114/MIST-4610-Group-Project-2/assets/145038467/67217fc7-03cc-4dff-b1c9-3198f49555c9">

<img width="898" alt="Screen Shot 2023-12-04 at 10 28 30 AM" src="https://github.com/Evan2114/MIST-4610-Group-Project-2/assets/145038467/a8476de1-6d2f-4fcc-acd8-5d1337372e5c">


## Manipulations Applied to Dataset
The primary manipulation applied to our data is that we removed aggregate records to avoid double counting. We found that the columns 'Race', 'Sex', 'Borough', and 'Neighborhood' all had aggregate records with totals that we filtered out before the Tableau visualizations. For example, in the 'Sex' column, the data collectors sometimes grouped together male and female results, which they reflected as 'All' in the dataset. Additionally, we filtered out years 2010 through 2015 to only the years 2016-2021 because there were significant gaps in data between those earlier years. Additionally, we filtered out data with null entries in Borough, which also occurred in the data collected between 2010 through 2015, due to the fact that this data point was not recorded before 2016.

## Analysis and Results
Question 1: From our visualization of the change over time of the total number of HIV, AIDS, and Concurrent diagnoses in the state of NY, there is a clear relationship between the total number of HIV, AIDS, and Concurrent diagnoses. While it is not guaranteed that HIV will progress into AIDS, there seems to be a positive relationship between the total number of HIV and AIDS cases, meaning that when one increases, so does the other. Therefore, we decided to use the concurrent number of cases to do a deeper dive into the distribution of cases amongst NYC boroughs. 

We focused on the 2020 time frame as there was a clear spike resembling the data from the first chart. The distribution amongst concurrent cases shows that Brooklyn had the largest spike among the boroughs during this time frame. This data can be used by NYC health departments to centralize aid to communities with the greatest need. It also provides insight into how the COVID-19 pandemic affected diagnoses and can be a baseline to turn the curve in the future.

Question 2: New York City has many neighborhoods, and as such, modeling the number of cases by location is a useful metric. By comparing these totals, we can identify areas that contain higher amounts of diagnoses. From our output, it seems that Bedford, East Flatbush, High Bridge, Fordham, and Crown Heights could be worthy of further study. We opted to drill down on a neighborhood with a high amount of diagnoses to find out more information. 

We looked at one Crown Heights, and created a heat map contrasting Race and Sex. What the heatmap showed was interesting. Males of every group recorded had higher amounts of diagnoses than Females of all groups, such that for the White, Asian/Pacific Islander, and Other identifying groups, the Female demographic did not show up on the visualization. In terms of Race, two groups have higher diagnosis numbers than the rest: Black and Hispanic/Latino. 

These statistics are corroborated by a study conducted from 2014-2018 by the New York City Department of Health and Mental Hygiene. This study found that Black and Latino/Hispanic people accounted for 80% and 90% of new HIV diagnoses in men and women, respectively, in NYC in 2018 (Pg. 15). This study also identified Crown Heights as one of the 3 highest diagnoses count neighborhoods in 2018, which corroborates our choice of neighborhood to dril down (Pg. 34).

HIV in New York City 2014 - 2018:
https://www.nyc.gov/assets/doh/downloads/pdf/dires/hiv-aids-overall.pdf


## Tableau Packaged Workbook
The packaged workbook containing the visualizations displayed above is also attached to this repository.
