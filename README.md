As the amount of data, data sources, and data types at organizations grow, the importance of making use of that data in analytics, data science and machine learning initiatives to derive business insights grows as well. An ETL pipeline (or data pipeline) is the mechanism by which ETL processes occur. Data pipelines are a set of tools and activities for moving data from one system with its method of data storage and processing to another system in which it can be stored and managed differently. 

In this mini project, I show an example of an ETL-pipeline using PySpark. The end user suppose to find in the data warehouse the data for the analysis that he needs to implement. The data sources are different csv files, which include data from Airbnb listings for 6 different capitals in Europe. The files have been taken by kaggle, https://www.kaggle.com/datasets/thedevastator/airbnb-price-determinants-in-europe . Additionally, I use the geojson files with the names of each city's neighbourhoods, in order to know the neighbourhood of each Airbnb listing.

The loaded data will include the Price, the Housing type (Home or Private room), Capacity, Cleanless, Satisfaction, Bedrooms, Attractiveness, Longitude, Latitude, City and Neighbourhood.

The libraries that I used:

- PySpark
- Geopandas
- Shapely
