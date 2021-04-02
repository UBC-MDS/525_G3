# jamacloud 

A DSCI 525 project by Group 3 to predict rainfall in NSW, Australia based on big datasets 

## Overview 
Our goal is to develop and deploy cloud-based ensemble machine learning model for future rainfall prediction in NSW, Australia. The datasets we used contain rain (mm/day) over time observed or computed by different models, retrieved on [figshare] (https://figshare.com/articles/dataset/Daily_rainfall_over_NSW_Australia/14096681). The datasets were loaded and combined together using `pandas` and `dask`, and underwent exploratory data analysis using both `python` and `R`. The data will then be used for big data machine learning model building and deployment to predict future rainfall in Australia. 

## Dependencies
**Python 3.8.3**
```
* re == 2.2.1
* requests == 2.25.1
* json == 2.0.9
* pandas == 1.2.3
* dask == 2021.3.1
* rpy2 == 3.4.3
```
**R 4.0.2**
```
* arrow == 3.0.0
* dplyr == 1.0.3
```

## Contributors
UBC MDS DSCI 525 Group 3:
* Aishwarya Gopal @AishwaryaGopal12
* Aditya Bhatraju @adibns
* Jianru Deng @jianructose
* Mitchie Yiqi Zhao @shoebillm

## Attributions 
CMIP6 Experimental Design and Organization [](https://www.wcrp-climate.org/wgcm-cmip/wgcm-cmip6)

Pangeo Coupled Model Intercomparison Project Phase 6 [](https://pangeo-data.github.io/pangeo-cmip6-cloud/)

SILO - Australian Climate Data [](https://www.longpaddock.qld.gov.au/silo/)

