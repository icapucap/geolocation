# geolocation

This is part of the coursera project where I had to use various clustering methods to cluster the most frequent drop and pick up points of taxis. Clustering methods like KMeans,DBSCAN,HDBSCAN were used.The outliers were also detected and grouped into the nearest cluster.<br>
The dataset consists of Latitude, Longitude and the name of the most frequent drop and pick up points for taxis. 
<br>
KMeans considers all the points individually but doesn't take into account the density of the points on the map.However DBSCAN(Density Based Spatial Clustering with Noise) does take the density and noise into account.<br>
The problem with DBSCAN is that it assumes same density accross all locations on the map, which isn't practical hence HDBSCAN(Hierarchial DBSCAN) rectifies this by transforming the space based on density.

# To use install
```
   pip install hdbscan
```
```
   pip install folium
```
Folium is to produce the map of the given region.
