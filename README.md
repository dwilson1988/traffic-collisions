# Notebooks

* get_weather.ipynb - this notebook pulls weather data for all stations in Utah with coverage over 2010-2018 and writes to a CSV file. utah_stations.csv is intended to create Voronoi Poygons to intersect with the road layer to assign a station to a road segment. Weather will be joined by stationid
* prepare_tset.ipynb - this notebook prepares and trains the xgboost model. It's a work in progress. WHen it's done it'll prep a training set file (maybe in libsvm format) that can be used with any classifier.


