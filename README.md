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

