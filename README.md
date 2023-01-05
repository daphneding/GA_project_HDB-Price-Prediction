# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project: Data Analysis of Singapore Weather in relation to Dengue Cases

### Background

According to the Meteorological Services Singapore, Singapore has typical tropical climate with adundant rainfall, high and uniform temperatures and high humidity all year round, since its situated near the equator. There are other metrics of climate such as sun shine duration, wind speed, cloud cover etc. In this project, we will look into the data sets based on the three core metrics - rainfall, temperature and humidity which are believed to responsible in relation to the increase of dengue cases in the country.

![Screenshot_20230104_091158.png](../img/Screenshot_20230104_091158.png)

([Picture Source](https://bewareofthebugs.com/diseases/dengue-fever/))

---

### Problem Statement

*To provide insights using weather and dengue case data for National Environment Agency's dengue awareness campaigns.* 

---

### Datasets

All the datasets used in the project come from [data.gov.sg](data.gov.sg).

Here's a data dictionary of cleaned up dataframe for a quick overview of features/variables/columns, alongside data types and descriptions. 


|Feature|Type|Dataset|Description|
|---|---|---|---|
|yr (2014-2018)|int|final|Year column indicating the timeframe| 
|mth (1-12)|int|final|Month column indicating the timeframe| 
|total_rainfall|float|final|Total rainfall in mm in a month| 
|no_of_rainy_days|float|final|The number of rain days (day with rainfall amount of 0.2mm or more) in a month recorded|
|mean_rh|float|final|Monthly mean of relative humidity, percentages are expressed as a value over 100.|
|temp_mean_daily_min|float|final|Monthly mean daily minimum temperature|
|number|float|final|Number of reported dengue cases over a month|

---

#### Summary


