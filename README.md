# NYC-Taxi-Trip-Duration-Analysis
An analysis of traffic patterns in NYC, followed by a predictor of the duration for any given trip. 

We integrate historic taxi data with traffic volume and weather data to build a model that predicts the duration of any given taxi trip in NYC, given starting coordinates, ending coordinates, and the current datetime. A significant portion of the project focused on exploratory analysis, employing Plotly for interactive plots and geojson/geopandas coupled  for choropleth maps based on NYC census tract boundaries. Distance metrics between coordinates were determined using the Open Source Routing Machine (http://project-osrm.org/).

Final models included k-means for unsupervised clustering of geographical trip coordinates, and xgboost along with various forms of regression for duration prediction.

The entire report, along with all code and visualizations, can be found in this Colab Notebook https://colab.research.google.com/drive/1_LARBalR4jxzamewfMkC7wIexmdcBs0Q?usp=sharing. It is view only, so to run it, simply save a copy in your own drive. The data we used, including data which we preprocessed, can all be found at https://drive.google.com/drive/folders/1uBY-piDRiakcdCC8cguPD-IadxkrpLsX?usp=sharing.
