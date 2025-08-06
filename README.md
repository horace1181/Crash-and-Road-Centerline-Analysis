# Crash-and-Road-Centerline-Analysis
Analyzing crash clusters in Downtown Salt Lake City

##### This notebook performs the following tasks:
###### 1. Reads in crash data (assumed to be in CSV format with "longitude" and "latitude" columns) and road centerline data (e.g., a shapefile).
###### 2. Converts the crash data into a GeoDataFrame.
###### 3. Finds the intersection of crash points with road centerlines using a spatial join.
###### 4. Uses scikit‑learn’s DBSCAN and OPTICS to cluster the crash data based on location.
###### 5. Visualizes the resulting clusters using Seaborn.
