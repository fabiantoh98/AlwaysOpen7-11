---
author: AlwaysOpen7-11
date: "2020-10-10"
description:
sec: 6
title:
---

# Challenges and Mitigation 

As 7-11 store location is not readily available in geospatial data format in their website. It is required to scrape data from 7-11 website and perform geocoding to get the latitude and longitude for the 7-Eleven location. 

Taiwan uses a different coordinate system as Singapore, and they have multiple projection system throughout the country. However, we will be only be using epsg:3828 where the bounding box cover the mainland of Taiwan without the islands surrounding it. Refers to (https://epsg.io/3828) to see the bounding box. 

