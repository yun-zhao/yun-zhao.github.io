---
layout: post
title: "Scaling Spatial Pattern Metrics: Impacts of Composition and Configuration on Downscaling Accuracy"
date: 2021-08-03
thumb: "https://yun-zhao.github.io/Proj_File/Scaling.jpg"
---

## Summary
This study evaluate how changes in composition/configuration produced by coarse graining affect scaling function fit and the accuracy of that function for predicting patterns at finer resolutions than observed. Neutral model landscapes with controlled composition/configuration were generated in QRule. Each raster was aggregated to seven coarser resolutions, and landscape metrics computed. Five scaling functions were fit to the seven-value set for each landscape and metric. The best-performing function for each landscape/metric was downscaled to predict the metric at a fine resolution not used in the scale-fitting process. Downscaling accuracy was measured through relative error. Results show aggregation impacts the fit and use of scaling functions for downscaling/prediction. Research to differentiate aggregation effects from physical processes in complex, real-world landscapes is needed.

## Illustration

The below figure shows examples of neutral model landscapes aggregated from 60 to 480 m with constant proportion **P** (0.5) but varying **H** values a 0.0, b 0.5, and c 0.95. **H** is a built-in heterogeneity parameter in QRule.

<div style="text-align:center">
  <img src="https://yun-zhao.github.io/Proj_File/HSR-1.jpg" alt="Description of the image" width="500">
</div>


Here is a map showing the proposed high-speed rail line between Dallas and Houston, along with existing trasnsportation infrastructures the support inter-city travels, such as airports and interstate highway.

<div style="text-align:center">
  <img src="https://yun-zhao.github.io/Proj_File/HSR-2.jpg" alt="Description of the image" width="400">
</div>

This below figure is an visualization of produced by the proposed method, showing advantages of different travel modes in Houston.  Red area indicates where HSR will have shorter total travel time, green area indicate areas where Airport Hobby will have advantage, and Purple indicate areas where Airport Geirge Bush will have advantage.   

<div style="text-align:center">
  <img src="https://yun-zhao.github.io/Proj_File/HRS-3.jpg" alt="Description of the image" width="500">
</div>


## Links

For full peer-reviewed published paper, click <a href="https://www.dropbox.com/scl/fi/zlhi1owh4o3pg8tjc6nkk/HSR.pdf?rlkey=0rxopmyxipvf4k9nfej6mjvjg&dl=0" target="_blank">here.</a>
