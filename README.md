# Bangalore Web GIS Dashboard

A full-stack Web GIS application built with Python, PostGIS, GeoPandas, and Leaflet.js — demonstrating end-to-end spatial data engineering from data ingestion to interactive web map deployment.

## Features
- Road network analysis of Bangalore (393,000+ road segments)
- Hospital coverage analysis with 500m buffer zones
- Neighbourhood spatial joins using PostGIS
- Interactive Leaflet.js dashboard with dynamic road styling
- PostGIS spatial queries (ST_Distance, ST_Buffer, ST_Contains, ST_Intersects)
- Choropleth, Heatmap, MarkerCluster, MiniMap visualisations

## Tech Stack
| Layer | Technology |
|-------|-----------|
| Data Collection | osmnx, OpenStreetMap |
| Spatial Analysis | GeoPandas, Shapely |
| Spatial Database | PostgreSQL, PostGIS |
| Visualisation | Folium, Leaflet.js |

## Setup
```bash
pip install geopandas osmnx folium sqlalchemy geoalchemy2 psycopg2-binary
```

## Author
Komma Manjunath Reddy
