# majacloud 

A DSCI 525 project by Group 3 to predict rainfall in NSW, Australia based on big datasets 

## Overview 
Our goal is to develop and deploy cloud-based ensemble machine learning model for future rainfall prediction in NSW, Australia. The datasets we used contain rain (mm/day) over time observed or computed by different models, retrieved on [figshare](https://figshare.com/articles/dataset/Daily_rainfall_over_NSW_Australia/14096681). The datasets were loaded and combined together using `pandas` and `dask`, and underwent exploratory data analysis using both `python` and `R`. The data will then be used for big data machine learning model building and deployment to predict future rainfall in Australia. 


| Milestones       |  Timeline        | 
|:------------------:|:------------------:|
| [Milestone 1 (Week 1) - Get the Data from Web & familiarize with advanced file formats](https://github.com/UBC-MDS/majacloud/blob/main/notebooks/milestone1.ipynb) |  2021-04-03 | 
| [Milestone 2 (Week 3)-  Setup S3 bucket, EC2 instance & TLJH](https://github.com/UBC-MDS/majacloud/blob/main/notebooks/Milestone2.ipynb) |   2021-04-17|
| [Milestone 3 (Week 4)- Setup EMR-spark instance & rewrite ML model you have from previous milestone in spark](https://github.com/UBC-MDS/majacloud/tree/main/notebooks/milestone3) | 2021-04-24  | 
| [Milestone 4 (Week 5)- Deploy ML model using flask]() | 2021-04-29     |

## Dependencies
**Python 3.8.3**
```
re == 2.2.1
requests == 2.25.1
json == 2.0.9
pandas == 1.2.3
dask == 2021.3.1
rpy2 == 3.4.3
pyspark == 3.1.1
s3fs == 0.6.0
joblib == 1.0.1
matplotlib == 3.4.1
sklearn == 0.0
json5 == 0.9.5
urllib3 == 1.26.4
```
**R 4.0.2**
```
arrow == 3.0.0
dplyr == 1.0.3
```

## Contributors
UBC MDS DSCI 525 Group 3:
* Aishwarya Gopal @AishwaryaGopal12
* Aditya Bhatraju @adibns
* Jianru Deng @jianructose
* Mitchie Yiqi Zhao @shoebillm

## Attributions 
CMIP6 Experimental Design and Organization [https://www.wcrp-climate.org/wgcm-cmip/wgcm-cmip6](https://www.wcrp-climate.org/wgcm-cmip/wgcm-cmip6)

Pangeo Coupled Model Intercomparison Project Phase 6 [https://pangeo-data.github.io/pangeo-cmip6-cloud/](https://pangeo-data.github.io/pangeo-cmip6-cloud/)

SILO - Australian Climate Data [https://www.longpaddock.qld.gov.au/silo/](https://www.longpaddock.qld.gov.au/silo/)

