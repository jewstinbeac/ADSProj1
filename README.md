# Welcome to StackEdit!

Hi! I'm your first Markdown file in **StackEdit**. If you want to learn about StackEdit, you can read me. If you want to play with Markdown, you can edit me. Once you have finished with me, you can create new files by opening the **file explorer** on the left corner of the navigation bar.


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

