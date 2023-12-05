# Crime-Data
## **Background:**

## **Objectives:**

## **Instructions to replicate:**
1. Run the jupyter notebook "/ETL/LA_Crime_Data.ipynb" (or "/ETL/LA_Crime_Data_Colab.ipynb" if using google collab. if using google collab then the path to where the CSV file "ETL_Crime_Data.csv" will be exported in the "Export the newly transformed dataframe into a csv" section will need to be changed to an empty existing directory in your google drive account.) This will clean up the data in "/RESOURCES/Crime_Data_from_2020_to_Present.csv" by removing any unneeded or erroneous data and exports it into a new CSV file called "ETL_Crime_Data.csv".

## **Presentation**

## **Files:**
- **README.md File and Original Dataset File:**
  - **README.md** - This readme file.  
  - **/RESOURCES/Crime_Data_from_2020_to_Present.csv** - The original dataset that is used in this project before any ETL work was performed.
- **ETL Files:**
  - **/ETL/LA_Crime_Data.ipynb** - This jupyter notebook takes the data from "/Resources/credit_data.csv" and performs some cleanup (ETL) work of the data and then exports it to a new CSV file located at "/output_data/ETL/csv/ETL_credit_data.csv".
  - **/ETL/LA_Crime_Data_Colab.ipynb** - This jupyter notebook does the same as "/ETL/LA_Crime_Data.ipynb" except this version can be ran in the cloud using Google Colab  
 **Output Data Files:**
  - **/OUTPUT_DATA/ETL/CSV/ETL_Crime_Data.csv** - This CSV file is what is created after ETL work is performed on the original data using "/ETL/LA_Crime_Data.ipynb"

## **Sources:**
- The dataset located in "/RESOURCES/Crime_Data_from_2020_to_Present.csv" originated from https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8.