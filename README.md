# MIST-4610-Group-Project-2

## Team Name:
39217 Group 8

## Team Members:
1. Ryan Alford [@Axeophone](https://github.com/Axeophone)
2. Khushi Patel [@khushipatel45](https://github.com/khushipatel45)
3. Evan Andersen [@Evan2114](https://github.com/Evan2114)
4. Elizabeth Carlin [@elizabethcarlin](https://github.com/elizabethcarlin)
5. Ethan Bowen [@EthanB57](https://github.com/EthanB57)
6. Purvi Nandakumar [@pdn9874](https://github.com/pdn9874)

## Description of Dataset:
The dataset selected represents HIV/AIDS diagnoses by 'Neighborhood', 'Sex', and 'Race/Ethnicity' for New York City, which we found through the website https://catalog.data.gov/dataset. The time frame of the data spans from years 2010 until 2021 with 'Year' representing another primary column in the dataset. However, the years 2010 through 2015 did contain frequent gaps in data and empty/null values. In addition to the columns aforementioned above, the other columns in the dataset include 'Borough', 'Total Number of HIV Diagnoses', 'HIV Diagnoses per 100,000 Population', 'Total number of Concurrent HIV/AIDS Diagnoses', 'Proportion of Concurrent HIV/AIDS Diagnoses Among All HIV Diagnoses', 'Total Number of AIDS Diagnoses', and 'AIDS Diagnoses per 100,000 Population'. The total numbers were reflected in integers, the diagnoses per 100,000 population were reflected as decimals, and the proportion statistics were reflected as percentages relative to all the diagnoses. We chose this dataset because we liked how the data contained a lot of variation among different key groups, statistics specific to HIV and AIDS only, and a combination of the two. After careful consideration, we knew we could provide useful insights into the specific data domains that are highly impacted by these diseases.

## Question 1:
Question: What is the total number of HIV, AIDS, and Concurrent diagnoses in the state of NY sorted by year? For any given spikes, what was the distribution amongst boroughs?
![Alt Text](https://github.com/Evan2114/MIST-4610-Group-Project-2/blob/main/1a%20Group%20Project%202.png)

Still need the second Tableau visualization for Question 1

Importance:

## Question 2:
Question: What is the distribution of the number of concurrent diagnoses amongst the various neighborhoods of NYC? What is the distribution amongst race and sex for the neighborhood with the most cases?

Importance:
![Alt Text]

![Alt Text]

![Alt Text]

![Alt Text]

## Manipulations Applied to Dataset
The primary manipulation applied to our data is that we removed aggregate records to avoid double counting. We found that the columns 'Race', 'Sex', 'Borough', and 'Neighborhood' all had a aggregate records with totals that we filtered out before the Tableau visualizations. For example, in the 'Sex' column, the data collectors sometimes grouped together male and female results, which they reflected as 'All' in the dataset. Additionally, we filtered out years 2010 through 2015 to only the years of 2016-2021 because there were significant gaps in data between those earlier years. Additionally, we filtered out data with null entries in Borough, which also occurred in the data collected between 2010 through 2015, due to the fact that this data point was not recorded before 2016.

## Analysis and Results
Yo


## Tableau Packaged Workbook
The packaged workbook containing the visualizations displayed above is also attached to this repository.
