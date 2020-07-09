
## Kovid19
COVID-19 statistics in Kurdistan as reported by KRG's department of Media and Information. This repository gets updated automatically. The data is fetched from https://gov.krd/coronavirus-en/dashboard/. KRG updates the data every 24 hours. This repo will be updated after 5 - 10 minutes.

## Website
[https://developerstree.github.io/Kovid19/](https://developerstree.github.io/Kovid19/)

## Schema

### [Summary](/data)
This file contains the summary of all of the governorates for each day:
 - `Date`: [ISO8601](https://en.wikipedia.org/wiki/ISO_8601) date format.
 - `Erbil`: New cases in Erbil (Hawler).
 - `Sulaymani`: New cases in Sulaymani.
 - `Duhok`: New cases in Duhok.
 - `Halabja`: New cases in Halabja.
 - `Total`: Total of new cases in Kurdistan on that day.
 - `Deaths`: Total of deaths in Kurdistan on that day.
 - `Recovered`: Number of recovered people in Kurdistan on that day.
 - `RunningSum`: Total confirmed cases in Kurdistan.
 - `Active`: Total number of Active cases in Kurdistan.

### [Governorates](/data/governorates)
These files contain more detailed data about each governorate:
 - `Date`: [ISO8601](https://en.wikipedia.org/wiki/ISO_8601) date format.     
 - `Male`: New male cases. 
 - `Female`:  New female cases. 
 - `Age0To19`:  New cases for 0 - 19 age group. 
 - `Age20To29`:  New cases for 20 - 29 age group. 
 - `Age30To39`:  New cases for 30 - 39 age group.  
 - `Age40To49`:  New cases for 40 - 49 age group. 
 - `Age50To59`: New cases for 50 - 59 age group. 
 - `Age60To69`: New cases for 60 - 69 age group.   
 - `Age70OrMore`: New cases for +70 age group. 
 - `TotalNewCases`: Total new cases of the day.
 - `Recovered`:  Number of recovered people of the day. 
 - `Deaths`:  Number of deaths on that day.
 - `TotalConfirmedCases`: Total confirmed cases in the governorate (Running Sum).
 - `TotalRecovered`:  Total number of recovered people in the governorate.
 - `TotalDeaths`:  Total number of deaths in the governorate.
 - `ActiveCases`: Total number of active cases in the governorate.
