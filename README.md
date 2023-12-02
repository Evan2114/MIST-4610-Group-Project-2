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
The dataset selected represents HIV/AIDS diagnoses by neighborhood, sex, and race/ethnicity for New York City, which we found through the website https://catalog.data.gov/dataset. The time frame of the data spans from years 2013 until 2021 and is represented as another primary column in the dataset. However, there were frequent data points from 2013 to 2015 that contained empty/null values, so we decided to exclude all the data points before 2016 from our analysis. In addition to the columns aforementioned above, the other columns in the dataset include borough, the total number of solely HIV diagnoses, HIV diagnoses per 100,000 population, the total number of concurrent HIV/AIDS diagnoses, the proportion of concurrent HIV/AIDS diagnoses among all HIV diagnoses, the total number of AIDS diagnoses, and AIDS diagnoses per 100,000 population. The total numbers were reflected in integers, the diagnoses per 100,000 population were reflected as decimals, and the proportion statistics were reflected as percentages relative to all the diagnoses. We chose this dataset because we liked how the data contained a lot of variation among different key groups, statistics specific to HIV and AIDS only, and a combination of the two. After careful consideration, we knew we could provide useful insights into the specific data domains that are highly impacted by these diseases.

## Question 1:
What is the total number of HIV, AIDS, and Concurrent diagnoses in the state of NY sorted by year? For any given spikes, what was the distribution amongst boroughs?



## Question 2:
What is the distribution of the number of concurrent diagnoses amongst the various neighborhoods of NYC? What is the distribution amongst race and sex for the neighborhood with the most cases?


## Manipulations Applied to Dataset
We removed aggregate records to avoid double counting. Race, Sex, Borough, and Neighborhood all had a aggregate records with totals that we filtered out. Additionally, we filtered to only the years of 2016-2021 because there was a gap in data beteen 2013 and 2016. Additionally, we filtered out data with null entries in Borough, because that data was not recorded before 2016.. 


## Analysis and Results
h


## Tableau Packaged Workbook
The packaged workbook containing the visualizations displayed above is also attached to this repository.
