# Chicago Crime

## Installation
Libraries needed to run the juypter notebook:
- geopandas
- geoplot
- matplotlib
- numpy
- pandas
- scikit-learn
- shapely

The initial dataset can be downloaded [here](https://drive.google.com/file/d/1ssrshVftiX1bEpm4D7wuPVK2v5jteKw1/view). Size ~1.8 GB

## Project Motivation
The City of Chicago provides a lot of publicly available data about the city on their [data portal](https://data.cityofchicago.org/).  
For this project I have been interested in crime related data and had a look at the following questions:
1. When do crimes happen and how did they develop over the recent years?
2. What are the most common crimes in each community area?
3. Where are the most common crimes happening?
4. Can we reliably predict arrests?

## File Descriptions
- chicago_community_areas.geojson: This file contains geospatial data about the 77 community areas of Chicago
- chicago_crimes.ipynb: The jupyter notebook containing the full analysis used to answer above questions

The initial dataset used for this analysis is too big to be uploaded on GitHub (~1.8 GB) but it can be downloaded [here](https://drive.google.com/file/d/1ssrshVftiX1bEpm4D7wuPVK2v5jteKw1/view) or directly at the data portal [here](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2)

## Results
Summary of the data analysis:
1. The total number of crimes has been mostly decreasing since 2003.
2. There are more crimes happening in the summer compared to the winter and more during day time compared to night time. The day of the week has no significant effect.
3. Theft, battery and criminal damage are the three most common crime types in Chicago. Offenses with regards to narcotics are less wide spread across the city but have some focus areas in the west and central part of the city.
4. The community areas with high levels of battery and criminal damage have a large overlap, with their highest values in the north west of the city. Theft is most common in a few community areas in the north east.
5. Predicting arrests is difficult as many different factors play a role. A prediction model simply based on the crime type, community area and date showed to be not reliable enough. However, more sophisticated projects might be able to build a reliable prediction model in combination with more data available from the City of Chicago.

A more detailed description of the results can be found in this <-- link! medium article.

## Acknowledgement
All data used for this project has been provided by the [data portal](https://data.cityofchicago.org/) of the City of Chicago, in particular the [crime dataset](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2) and the [geojson dataset for community areas](https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Boundaries-Community-Areas-current-/cauq-8yn6)

## Licensing
The license for the used data is available in the [terms of use](https://www.chicago.gov/city/en/narr/foia/data_disclaimer.html) of the City of Chicago.
