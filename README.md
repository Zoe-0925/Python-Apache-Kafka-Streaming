# Stop the Bushfire! Python-Apache-Kafka-Streaming
A python program that reads data from CSV files, streams the data with 3 Kafka producers, processes the result, and save it into MongoDB.

# Project Goal
To simulate processing big data streams from multiple sensors and saving the data analytics results to the MongoDB database.
The scenario is preventing bushfire through streamline data analysis by receiving data streams of the weather and multiple bushfire hotspots.

# Tech Stack
Python 3, Apache Kafka (Producers and Consumers), Apache Spark Streaming and MongoDB.

# Data Sets
○ hotspot_historic.csv

○ climate_historic.csv

○ hotspot_AQUA_streaming.csv 

○ hotspot_TERRA_streaming.csv 

○ climate_streaming.csv

# Task A - Analysis on MongoDB Data Modeling

# Task B - MongoDB Queries for Data Aggregation

# Task C - Kafka Producers
a. Event Producer 1: It loads all the data from climate_streaming.csv and randomly feed the data to the stream every 5 seconds. 

b. Event Producer 2: It loads all the data from hotspot_AQUA_streaming.csv and randomly feed the data to the stream every 10 - 30 seconds. AQUA is the satellite from NASA that reports latitude, longitude, confidence and surface temperature of a location.

c. Event Producer 3: It loads all the data from hotspot_TERRA_streaming.csv and randomly feed the data to the stream every 10 - 30 seconds. TERRA is another satellite from NASA that reports latitude, longitude, confidence and surface temperature of a location.
