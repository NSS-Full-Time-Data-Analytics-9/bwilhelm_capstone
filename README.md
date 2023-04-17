# Beach Vacation

## Table of Contents
- Tableau Dashboard
- Motivation
- Questions
- Problems and Hurdles
- Technologies Used
- Sources
- Conclusion

## Motivation
Growing up my family loved to travel and take trips together.  As my family has continued to grow, I have had the please and joy of experiencing the joys of family vacations as a parent.  As my wife and I plan these trips, much like when I was a child growing up, we are always drawn to the beach and all that a beach vacation has a to offer.  Whether it be the feeling of sand between the toes, the cuisine, or the beuatiful weather that traveling south has to offer, there is no feeling quite like that of traveling to the beach.  I  wanted to take this opportunity to research beaches that are within a driveable distance (~7-9 hours) from Nashville, TN.  When looking at at options of beaches to eplore and examine, I narrowed this study to the following beaches:

- Dauphin Island (Alabama)
- Orange Beach (Alabama)
- Miramar Beach (Florida)
- Panama City (Florida)
- Tybee Island (Georgia)
- Gulfport (Mississippi)
- Isle of Palms (South Carolina)

When exploring these beaches, I want to find out which areas offer the safest travel and the ideal time of year to travel to each location based on recent weather trends and data.  When looking at safety ratings for each area/county, I will be looking at crime rates from 2007-2020 and traffic accident rates from each area/county from 2017-2021.  I will also use weather data from the last 10 years (2013-2022) when exploring and analyzing trends in weather from each location.  The timeframe within each year that will be looked at will be March 11-18, May-August, and October 7-14.  The March and October months coincide with the typical Spring and Fall break weeks for schools in Nashville, and May-August will highlight prime summer travel timeframes.

## Questions:

1. What is the crime rate for each county in the locations with one of the specified beaches?
2. What is the traffic accident rate for each county in the locations with one of the specified beaches?
3. What are the trends in the crime and traffic data that could suggest the safest areas of when planning vacation to one of the seven beaches?
4. Does weather data over the last 10 years offer enough data to highlight ideal time to travel for each location?

5. Stretch Goals:
- What is a tpyical average price that visitors can expect to spend per night in housing at each location?
- Does certain locations offer more ideal type of rental property than other?  Factors to look at will be: number of beds, number of bathrooms, petfriendly, type of property (house, condo, resort, ect.).

## Problems and Hurdles
When analyzing these beaches, the beaches analyzed consisted of 7 different beaches/locations across 5 different states.  Making sure that the data collection process consisted of thorough collection and cleansing processes.  This would ensure that the data was normalized in a way that the format and structure of the data was consistent throughout each location.  This would ensure that the analaysis was done properly, with data that was structured and aggregated the same throughout all locations.  To aid in this process, sources that could provide data for all the different locations were used throughout the data collection process.  

Web-scraping the vrbo website for rental listings was another hurdle that took some time to gather data for each location.  This data consists of only data that was listed available on May 6, 2023 (pulled on April 15, 2023).  Any listing that was already taken is not shown so the data only represents data/listings that are available.  Hundreds of listings were still available to pull (numbers are smaller for locations with less listings available in general) that is able to still offer reasonable snapshot of what listings are offered at each location.

## Technologies Used
1. Python / Pandas - for exploration, collection, cleansing, and aggregation of the datasets
2. Tableau - creating final presentation and interactive dashboard
3. Git - for version control

## Data Sources
To answer the questions above, I used the following sources to collect the datasets used in my analysis:

1. Crime Data - web-scraped using the following website:
- https://www.city-data.com/crime/
2. Traffic Data - pulled from National Highway Traffic Safety Association website:
- https://cdan.nhtsa.gov/
3. Weather data offered through Visual Crossing (executed through Weather Query Builder)
- https://www.visualcrossing.com/weather/weather-data-services
4. Rental Property Listings were web-scraped through Vrbo website:
- https://www.vrbo.com/
