# NYC-Taxi-Trip-Duration-Analysis
An analysis of traffic patterns in NYC, followed by a predictor of the duration for any given trip. 

We integrate historic taxi data with traffic volume and weather data to build a model that predicts the duration of any given taxi trip in NYC, given starting coordinates, ending coordinates, and the current datetime. A significant portion of the project focused on exploratory analysis, employing Plotly for interactive plots and geojson (and geopandas) coupled with a dataset of NYC census tract boundaries to create choropleth maps. Distance metrics between coordinates were determined using the Open Source Routing Machine (http://project-osrm.org/).

Final models included k-means for unsupervised clustering of geographical trip coordinates, and xgboost along with various forms of regression for duration prediction.

The entire report, along with all code and visualizations, is outlined within the .ipynb.
