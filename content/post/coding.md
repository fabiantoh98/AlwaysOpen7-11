---
author: Christian Decker
date: "2019-08-07"
description: Some section with content
sec: 3
title:
---

# Challenges and Mitigation 

As 7-11 store location is not readily available in geospatial data format in their website. It is required to scrape data from 7-11 website and perform geocoding to get the latitude and longitude for the 7-Eleven location. 

Taiwan uses a different coordinate system as Singapore, and they have multiple projection system throughout the country. However, we will be only be using epsg:3828 where the bounding box cover the mainland of Taiwan without the islands surrounding it. Refers to (https://epsg.io/3828) to see the bounding box. 

# Data Sources

 Name                         | Sources
 -----------------------------|---------------------------------------------------------
7-11 convenience stores       | https://www.319papago.idv.tw/lifeinfo/7-11/7-11-00.html 
Population Density            | https://gis.ris.gov.tw/dashboard.html?key=B07 
Other Taiwan open source data | https://data.gov.tw/ 



