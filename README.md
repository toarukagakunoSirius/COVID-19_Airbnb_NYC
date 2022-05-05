# COVID-19_Airbnb_NYC

New York City's otherwise thriving sharing economy, including the short-term housing rental industry, has been severely decimated by the impact of the 2020 COVID-19 pandemic. This research study uses Airbnb rentals in New York City for September 2018 and September 2021 obtained from insideAirbnb as an example, and through machine learning, we will conduct statistics and analysis on the impact of different factors on the listings’ availability.
By analyzing how the importance of these different factors changed before and after the coronavirus outbreak, we hope to derive which factors visitors placed more importance on when choosing an Airbnb listing after the outbreak. In this way, we can provide hosts with recommendations to optimize their listings, improve room occupancy, and facilitate the recovery of the short-term housing rental industry in New York City after COVID-19.

Original data source for NYC Airbnb listingings September 2018 available at:
https://drive.google.com/drive/folders/1xk5RyR-UgF6M-ddhn11SXHEWJeB0fQo5?usp=sharing

Original data source for NYC Airbnb listingings September 2018 available at:
http://data.insideairbnb.com/united-states/ny/new-york-city/2021-12-04/data/listings.csv.gz

For data cleaning process and cleaned dataset, please find in clean_V2.ipynb, listing_ny_2018_09_filtered_V2.csv and listing_ny_2021_09_filtered_V2.csv

For using textblob to slice the description and calculate high frequency and high growth rate words, please find code in ML_2018.ipynb and ml2021.ipynb.

And result dataset inml2018.csv and ml2021.csv are words frequency in 2018 and 2021.

For decision tree analysis process, please find our code in DT.ipynb. 
