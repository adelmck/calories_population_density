# calories_population_density
Total caloric consumption of countries and the population density of countries

Questions?/Hypothesis
1. Does the amount of rainfall/freshwater of a country effect its food production?
2. How many calories per hectare of arable land and population?
3. Is population density correlated with agricultural land productivity?  
4. Which countries are the most productive at producing which crops? 
5. Crop production by segmentations (failed state index, dictatorships, tropical, OECD)
6. Are the agricultural productivity of countries with increasing populations increasing?
7. What is the standard deviation from neighbors/region. Is the location of a country more correlated to calories consumed and agricultural productivity than countries' population, population density, rainfall/freshwater, arable land, climate zone?


Process

Gather the data
Data sources:
1. FAO data set
2. Crops by calories per hectare
3. Population of countries
4. Failed state index
5. OECD
6. List of tropical countries

Explore the data

Find common columns (country code, country name, crop names)
FAO data has too many columns and columns of yearly productions should be unpivoted.


Clean the data
1. Rename columns to match across the various data sets.
2. Unpivot the FAO data set to merge year columns into the country rows.
3. Ensure country code column match acrosss data sets for merger.
4. Merge data sets on country code.
5. Remove the 'Y' from before the year in FAO data set?
