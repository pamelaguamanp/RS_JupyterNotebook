### Description

This repository was created to upload files that complement tasks described in **"Geospatial task 2023 internship.pdf"**. 

**File content**

[TOCM]

[TOC]

#Dependences
The file **"dependences.txt"** contains all library dependences necesary to run the notebook **"TASK Intership.ipynb"**. The libraries and modules are:
- numpy
- xarray
- scipy
- h5netcdf
- netCDF4
- matplotlib
- rasterio
- geopandas
- odc-geo
#Data
The files **geospatial_test_datacube.nc** and **geospatial_sub_aoi.geojson** contains the dataset and the sub AOI provided for this project. 
#TASK Internship.ipynb
This file is the Jupyter notebook that contains all the code that execute the task described in **"Geospatial task 2023 internship.pdf"**.
#Question 2

Date | NDVI average | Average NDVI (Month)
------------- | -------------
4/9/2021 | 0.560181 | 0.57217167
4/14/2021| 0.579453|
4/27/2021|0.576881|
5/7/2021| 0.579228|0.71529
5/19/2021|0.650879|
5/24/2021|0.812332|
5/29/2021|0.818721|
6/18/2021|0.852717|0.852717
7/28/2021|0.861783|0.861783
8/10/2021|0.823053|0.79328
8/12/2021|0.763636|
8/25/2021|0.793151|
9/4/2021|0.851028|0.83605425
9/16/2021|0.844687|
9/19/2021|0.823391|
9/21/2021|0.825111|
10/6/2021|0.731453|0.678658
10/9/2021|0.630867|
10/29/2021|0.673654|
11/5/2021|0.652978|0.657885
11/20/2021|0.659958|
11/23/2021|0.678537|
11/25/2021|0.640067|
The Normalized Difference Vegetation Index, (NDVI), is an index that allows for determining the quality of the vegetation. It is currently the index of the most used vegetation. NDVI is an index to measure vegetation's amount and health in an area. It is calculated by dividing the difference between the near-infrared (NIR) and red bands of a satellite image by their sum. Its range is from -1 to 1; the higher values indicate a higher green/healthy vegetation density, and low values refer to low/unhealthy density vegetation. Other surfaces like water or clouds can have negative values that cannot be ruled out.
The table shows the values of ndvi for 2021 from April until November. For April, we can see an average value of 0.57 around. According to some authors, this value means “average vegetation” (0.5-0.7), which can be described as dense and normal healthy vegetation. It happens the same in October (0.67) and November (0.65) 
For may, the value average is 0.71, for June is 0.85; for July 0.86; for august 0.79; for September 0.84; until here, the ndvi values can be considered as “health vegetation” (Range 0.7-1). 
Particularly, during may, we can see a change of ndvi values, which start with 0.5, but at the month's end, the value increases until 0.8. we can assume that during this month, had a growth of vegetation.
Generally, the months with higher health vegation are june,july and september, which belong to summer. The month with lower ndvi values in April, probably because in this month, the winter period is finished, and spring is starting. It depends on the characteristics of the study area. November also has an average-low value (0.65), which refers to an autumn session where vegetation is lost because winter is coming. On the other hand, no extreme values less than -0.5 are observed, which may indicate that the vegetation may not be diseased (0.2-0.5) and that its average cover is normally dense during this time series.
The Changes in the density of vegetation as a new growth or the loss of vegetation are due to several factors such as deforestation or drought, weather, decline of crops, among others. Although these results denote an improvement in vegetation quality, these must be analyzed in greater detail since the indices used do not distinguish the vegetation cover that presents a certain degree of quality. I mean, an area with a high NDVI value can correspond to both a healthy native forest and a crop. As well as a low value of this same index can occur in an area of bushy and sparse vegetation but not necessarily diseased. This will depend on the type of vegetation in the study area.
