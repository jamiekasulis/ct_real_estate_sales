This repository is for an analysis of CT real estate sales data from 2001 to 2016. You can view it here:
  https://data.ct.gov/Housing-and-Development/Real-Estate-Sales-2001-2016/5mzw-sjtu?category=Housing-and-Development

This repository includes my own copy of the raw file from the above link as well as my own cleaned versions of that file (one for every
  year).

FILES
- data/Real_Estate_Sales_2001-2016.csv    The raw data downloaded from the above link on 7/6/18
- data/clean_data_xxxx_listings.csv       Year-by-year clean data. There are 16 of these
- Data Cleaning Final.ipynb               The notebook I use to produce the clean year-by-year data.
- Data Exploration.ipynb                  My initial analysis notebook.

Note: Data Cleaning Final.ipynb takes quite some time to reproduce even a year of clean data (even just 2001 has around 60,000 rows of
  data). If you wish to rerun this notebook on your own device, you should plan to run it overnight or while you go off to do something
  else.
