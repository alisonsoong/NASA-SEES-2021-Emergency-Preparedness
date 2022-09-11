# Analyzing, Visualizing, and Predicting the Impacts of Various Natural Disasters Through Geospatial Applications
NASA SEES 2021 Emergency Preparedness Team
Alison Soong, Adelene Chan, Grady Pennington, Neha Vardhaman, Eashan Hatti, Sabrina Chang, Joel Villarino, Sheryl Hsu, Natasha Cordova-Diba, Sophia Lin
Mentor: Teresa Howard

# Abstract
Using population grid datasets, satellite imagery, and geospatial data accessed through Google Earth Engine, we identified patterns between natural disasters, their causes, and their impact on communities in order to predict and identify ways to reduce their effects. Techniques used include resampling, grid manipulation, mapping of datasets, and trend examination by creating time-series graphs and visualizations.

For wildfires, population data was overlapped by burn scar data to calculate the yearly California population directly affected by wildfires (residing in burn areas) from 2000 to 2020. A line of best fit based on the calculated values showed an increase in population affected over time, and notable outliers revealed years with conditions that contributed to wildfire vulnerability, including high vegetation, high wind speeds, high temperatures, low relative humidity, and sloped topography. Scoring and combining data based on these five factors resulted in a fire risk map that visualizes the susceptibility of California to wildfires.

For floods and tropical storms, the hurricane-heavy Florida-Caribbean region was analyzed by processing surface soil moisture (SSM) and precipitation (GPM) datasets to create time series line charts that revealed an upward trend in both SSM and precipitation in the fall of 2017. To examine how susceptible SSM, precipitation, and dense populations were to flooding, we overlapped maps of the various datasets by masking higher values with areas of the map that had flooded. A significant overlap existed with these flood factors, allowing us to generate a map that visualizes areas susceptible to flooding.

For extreme heat, San Francisco was chosen as the area of study. We created land surface temperature (LST) and normalized difference vegetation index (NDVI) images of the city to determine the effect of vegetation on extreme heat events in urban areas. Our observations showed that while greenbelts — large vegetated areas dispersed throughout the city — do have a significant cooling effect, this effect does not spread far beyond the limits of the area. A possible solution is to distribute a greater number of smaller green areas evenly throughout the city instead.

![alt text](https://github.com/alisonsoong/NASA-SEES-2021-Emergency-Preparedness/blob/main/AbstractFigure.jpeg?raw=true)

# Supplemental Material
### Abstract
[Abstract](https://www.essoar.org/doi/10.1002/essoar.10508436.1) published through AGU 2021 Fall Meeting and ESSOAr (Earth and Space Science Open Archive)

### Presentation
[2021 SEES Emergency Preparedness Final Presentation](https://www.youtube.com/watch?v=yiGSz_DawFA)

### Poster
![alt text](https://github.com/alisonsoong/NASA-SEES-2021-Emergency-Preparedness/blob/main/SEES2021_EmergencyPreparedness_Poster.pdf?raw=true)

# Overview

## Extreme Heat group
Eashan Hatti, Grady Pennington, Joel Villarino, Sheryl Hsu

Code:
- https://code.earthengine.google.com/4de2f34bcef19c6f12e3e89f14a954eb

## Wildfire group
Alison Soong, Natasha Cordova-Diba

Code:
- https://colab.research.google.com/drive/1WMK3_JEtFNNqepDUPnMYazgNK0rwWvzT?usp=sharing

## Floods/Tropical Storms group
Adelene Chan, Neha Vardhaman, Sabrina Chang, Sophia Lin

Code:
- https://colab.research.google.com/drive/1kRiPG4zAmmUh49PXkMm0lm4GwXS4nEZH?usp=sharing
