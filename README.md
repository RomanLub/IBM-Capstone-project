# Which venues will succeed in which neighborhood based on neighbourhood's market potential and level of competition (User case exmple: Helsinki, Cafe)

### Introduction/Business Problem 
The goal is to create model which will give recommendation based on Finland’s national statistics collected on neighbourhood level (such as neighbourhood area size, population, jobs and income) is there market potential for selected venue type (venue classification comes from Foursquare).

Based on national statistical data and data from Foursquare four models will be created (KKN, Decision tree, Support vector machine and logistic regression – model with best fit will be selected) to estimate are neighbourhoods in selected municipality/city underserved (for instance number of venues less than estimated by model) and additional venues can be potentially established or other way around - which neighbourhoods are overserved and establishing new venues is not recommended (basically meaning high level of competition).

Model can be used by consultants or potentially enterpreneur who wants to know in which neighbourhood to etablish his/her enterprise.

For user case capital of Finland Helsinki will be selected and one venue type i.e. Café.

### Data

Finland’s national statistics: www.stat.fi, Free Power Query (M) generator for Statistical OpenDATA from PXWeb will be used to collect required data https://stat.qumio.com/

Finland’s neighbourhood location data: https://www.avoindata.fi/data/fi/dataset/postcodes

Foursquare venue data

