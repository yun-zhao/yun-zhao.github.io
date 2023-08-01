---
layout: post
title: "Urban Poulation Estimation Using Lidar"
date: 2016-05-20
thumb: "https://yun-zhao.github.io/Proj_File/Pop.jpg" 
---

## Summary
 The purpose of this work is to estimate work and home population use lidar-derived building volumes.  Previous studies have noted inconsistencies between population and building volume estimates in certain areas. This study investigate this disparity by incorporating both static and ambient population data into the models using the US Census Bureau’s Longitudinal Employer-Household Dynamics (LEHD) database. To do this, we first develop a normalized home–work index to classify census blocks as primarily work-oriented, home-oriented, or mixed-use based on the LEHD data. We then employ ordinary least squares and geographically weighted regression (GWR) to explore the relationships between the different population groups (work, home, and mixed) and lidar-derived building volumes. We test these relationships across four diverse cities in Texas: Austin, Dallas, Houston, and San Antonio. Results suggest non-stationarity in the relationship between building volume and population with stronger, positive relationships in home-oriented and mixed-use blocks where the amount of building volume per person may be more consistent compared to work-oriented blocks. GWR models yielded high R2 values (0.9), particularly in mixed-use areas, indicating the potential for predictive relationships. 

## Illustration

A confounding factor in the over- and underestimation of population from building volume is the intermixing of the diurnal working and residential populations within blocks and individual buildings. To overcome this constraint, we developed a NHWI (similar to Normalized Difference Vegetation Index, aka. NDVI) to control for the amalgamation of working and residential populations at the block level. Counts are normalized to provide a standardized range of values from −1 to 1 with negative values indicating the block contains a greater relative ‘home’ population, and positive values indicating the block contains a greater ‘work’ population.  

<div style="text-align:center">
  <img src="https://yun-zhao.github.io/Proj_File/pop-1.JPG" alt="Description of the image" width="200">
</div>


The proposed index and methods are applied to four major cities in Texas: Austin, Dallas, San Antonio, and Houston.

<div style="text-align:center">
  <img src="https://yun-zhao.github.io/Proj_File/pop-2.jpeg" alt="Description of the image" width="550">
</div>

GWR  is a local statistical technique for exploring spatial variations in relationships across space and can account for the spatial non-stationarity in the effect of independent variables often present in OLS regression. GWR allows the weights of observations to vary such that observations closer to the block being assessed are given a greater weight than observations further away. The below table shows the improvements of GWR compared to traditional OLS linear regression.   

<div style="text-align:center">
  <img src="https://yun-zhao.github.io/Proj_File/pop-3.JPG" alt="Description of the image" width="650">
</div>


## Links

For full peer-reviewed published paper, click <a href="https://www.dropbox.com/scl/fi/l8rlm9zpwrw5wr0expg6d/Estimating-work-and-home-population-using-lidar-derived-building-volumes.pdf?rlkey=68gc18dbxfb4o5nctf5gqeplg&dl=0" target="_blank">here.</a>
