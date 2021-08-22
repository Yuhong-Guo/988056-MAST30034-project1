# MAST30034 Project 1 - Quantitative Analysis
- Student Name: Yuhong Guo
- Student ID: 988056
- Due Date: Friday 13th of August 11:59:00 am (AEST).
- Report Link: https://www.overleaf.com/read/txsqjykfwzhc

# Dependencies
- Language: Python 3.8.3 and R 4.05
- Python Libraries: numpy, matplotlib, pandas, statsmodels
- R Libraries: dplyr, sf, tmap, tmaptools

# Datasets
- NYC TLC: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page
- GHCND: https://www.ncei.noaa.gov/metadata/geoportal/rest/metadata/item/gov.noaa.ncdc:C00861/html
- GHCND metadata: https://www1.ncdc.noaa.gov/pub/data/ghcn/daily/

# Directory
- `raw_data`: Contains all the raw data files.
- `preprocessed_data`: Contains all the preprocessed data files.
- `plots`: Output and save all your figures here.
- `code`: Keep all notebooks and scripts in this folder. Ensure that you have notebooks for each _stage_ of code. Here's an example:
    - df_preprocess notebook for "Extracting Data" and "Data preprocess" of NYC TLC data.
    - GHCND_preprocess notebook for "Extracting Data" and "Data preprocess" of GHCND data.
    - analysis notebook for "Analysis and Visualisation".
    - map_Rcode.Rmd for Visualisation.
    - Modelling notebook for "Statistical Modelling".
- `deprecated`: A folder to store "old code" that **you do not use anymore** or code that you experimented with, but decided to not go ahead. This is useful in case you ever need to come back to an older iteration of code or to express your other approaches to the problem.
