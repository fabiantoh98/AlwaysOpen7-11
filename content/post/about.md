---
author: Christian Decker
date: "2019-08-07"
description: Initial project description
sec: 1
title: 7-11 in Taiwan 
---

# Project Motivation

Convenience stores are a huge deal in Taiwan. Especially the Japanese-American chain, 7-Eleven is ubiquitous in Taiwan with 5,000 over stores distributed around the country. It provides various services that help people with their daily activities such as bill payment, cash withdrawal, top-up, delivery and pickup parcels. With that, the 7-11 in Taiwan plays an important part in peoples’ daily lives. It has also been integrated in peoples’ modern part of life by delivering brilliance service with every visit unlike the 7-11 in Singapore where people visit only when there is no other alternative. Therefore, this project aims to leverage on geospatial methods to discover the characteristic of 7-Eleven locations in Taiwan.  
 

# Project Objectives 
This project aims to: 

* Discover 7-11 cluster patterns in Taiwan 

* Discover the average distance between 7-11 stores and their location distribution patterns 

* Identify the correlation between 7-11 and amenities such as MRT, bus interchange, school etc. 

* Identify the correlation between 7-11 and regional population density. 


# Literature Review 

In literature review, we have done our topic on the following area to enhance our preliminary knowledge: 

## Plotting a colored Taiwan Map based on population: 

This is a simple project where the author analyzes Taiwan population distribution on a choropleth map. There are many insights we gain from this project such as how we should process the data. For example, not all files have an English version, this project show how we can join the data even if they are in different languages. 

https://rpubs.com/OzuShi/348822 

 

## Spatial Distribution analysis of convenience store in Kaifeng (China): 

This project focuses on the spatial distribution of convenience store in Kaifeng city and how it will affect the retail industry. Their research analyzes the spatial layout characteristics of convenience store such as traffic and compare the spatial distribution of convenience store with population clusters. They discovered that there is sufficient service coverage, unbalanced spatial distribution based on population cluster and most convenience store are distributed in cheaper land price area. Hence, they have come out with several recommendation for government to provide a uniform service range of comprehensive coverage. 

https://www.researchgate.net/publication/340659202_Spatial_Distribution_Analysis_of_Convenience_Stores_in_Kaifeng_City_Based_on_POI_Data 

# Methodology 


* Create a R Shiny application that allow us to view the location of 7-11 and its relations with other amenities.  

* To perform spatial point pattern analysis on 7-11 in Taiwan 

* Choropleth Map to visualize the population in Taiwan 

* Kernel Density Estimation of 7-11 and other amenities in Taiwan 

* Auto-correlation with 7-11 stores and various amenities 

* Second Order Analysis such G-function and L-function 

# Challenges and Mitigation 

As 7-11 store location is not readily available in geospatial data format in their website. It is required to scrape data from 7-11 website and perform geocoding to get the latitude and longitude for the 7-Eleven location. 

Taiwan uses a different coordinate system as Singapore, and they have multiple projection system throughout the country. However, we will be only be using epsg:3828 where the bounding box cover the mainland of Taiwan without the islands surrounding it. Refers to (https://epsg.io/3828) to see the bounding box. 






