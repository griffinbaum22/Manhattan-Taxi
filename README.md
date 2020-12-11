# Manhattan-Taxi

### Overview
Implemented various regression models to predict travel time of taxi rides in New York. 

## Processing
Accessed Yellow Taxi data from NYC Taxi and Limosine Commission, storing data into nyc_taxi.db, a SQLite database. Data represents all New York Yellow Taxi trips taken in January 2016.

## Exploratory Data Analysis
Wrote SQL queries to process and clean data, filtering unusual conditions (Historic 2016 Blizard) and points outside Manhattan. Went onto cluster data into distinct Manhattan geo-locations with K-Means, and implement PCA on pickup longitude and latitude locations. Data augmentation used to create final feature frame.

## Modeling
Predicted taxi ride-duration with a variety of regression models, utilizing Tree Regression and XGBoost. 
