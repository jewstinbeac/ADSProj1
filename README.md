# Repository Structure

All code notebooks are at the root level of this repository. The order the files should be run in is:
1. TaxiCSVtoParquetWithSchema.ipynb
2. CleanData.ipynb
3. Link External Data and Visualise.ipynb
4. interactionTest.Rmd

requirements.txt contains all the packages and libraries required to run the .ipynb files. interactionTest.Rmd has commented out code at the top to install any packages needed to run it.

Any data retrieved from any source should go in raw_data

Any data that has been processed (schema attached, feature engineered, outliers removed etc.) go into preprocessed_data.

Any graphics generated using the data go into the plots folder

# Data Sets
Data sets used in this project can be obtained from:
1. Yellow Taxi data from https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page. Select and download the yellow taxi data from June, July, and August of 2018.

2. Weather data from https://www.ncdc.noaa.gov/cdo-web/search. Select "Daily Summaries" as the observation type and select Date Range to be between 01/06/2018 - 31/08/2018.  Select Cities in the "Search For" section and use term "New York". 

	The first result that shows as New York should be downloaded, requesting for data units in metric and data types PRCP, SNWD, SNOW, TAVG, TMAX, TMIN, and AWND.



