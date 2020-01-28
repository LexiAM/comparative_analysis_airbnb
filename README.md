# Statistical Comparitive Analysis of Airbrn Listings and Price Trends: LA vs NYC
## Summary
In this project we compare Airbnb listings and yearly trends between Los Angeles and New York for the past year starting with October 2018 and ending with October of 2019. We follow CRISP-DM process to perform comparative statistical analysis examining the types and sizes of listings, offered amenities, and listed prices throughout the year. We perform significance and effect size testing to evaluate strength of our findings.

## Findings
We found that generally Los Angeles Airbnb rental properties are larger in terms of the number of rooms, beds and accomodations than those in NY.

![](/resources/sizes.png?raw=true)

We found similar price trends throught the year between Los Angeles and New York, with some differences in the amplitude of seasonal price changes. We also found a significantly larger price spike around Christmas and New Years in New York as compared with LA.

![](/resources/price_trends.png?raw=true)

## Project Structure
```
|-- `airbnb_analysis.ipynb`: analysis Jupyter Notebook
|-- `airbnb_analysis.html`: analysis html
```
## Data
Data for this analysis can be found on the Inside Airbnb projects website [Inside Airbnb Data](http://insideairbnb.com/get-the-data.html)  

[Los Angeles calendar](http://data.insideairbnb.com/united-states/ca/los-angeles/2018-10-05/data/calendar.csv.gz)  
[New York calendar](http://data.insideairbnb.com/united-states/ny/new-york-city/2018-10-03/data/calendar.csv.gz)  
[Los Angeles listings](http://data.insideairbnb.com/united-states/ca/los-angeles/2018-10-05/data/listings.csv.gz)  
[New York listings](http://data.insideairbnb.com/united-states/ny/new-york-city/2018-10-03/data/listings.csv.gz)   
## Requirements
Python 3.6 + with the following packages:
 ```
 datetime
 IPython
 matplotlib
 numpy
 pandas
 seaborn
 scipy
```
## Authors
- Alexander Manasson
