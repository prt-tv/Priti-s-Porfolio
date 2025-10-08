# Layoffs Data Cleaning (SQL)

## Project Overview

This project focuses on cleaning a layoffs dataset using SQL. The goal is to prepare the raw, messy data for accurate analysis by:

- Removing duplicate records  
- Handling missing or null values  
- Standardizing date formats  
- Correcting inconsistent text entries  

## Dataset

The dataset contains information about layoffs from various companies, including details such as company name, industry, total layoffs, date, country, and stage of layoffs.

## Tools Used

- SQL (MySQL)

## Data Cleaning Steps

Some of the key cleaning techniques applied in the SQL script (`Data Cleaning.sql`) include:

- Eliminating duplicates using `DISTINCT` or `ROW_NUMBER()`  
- Replacing NULLs with default or calculated values using `COALESCE()`  
- Formatting dates consistently with functions like `TO_DATE()` or `CAST()`  
- Standardizing text data (e.g., trimming spaces, converting to uppercase/lowercase)  

## How to Use

To reproduce the cleaning process, run the `Data Cleaning.sql` script in your preferred SQL environment on the raw layoffs dataset.

## Results

The cleaned dataset is now ready for further analysis or visualization, ensuring consistent and reliable insights.


## Learnings

This project enhanced my SQL skills in handling real-world messy data and demonstrated the importance of thorough data cleaning in the data analysis pipeline.

## Next Steps
- Perform exploratory data analysis (EDA) to identify trends  
- Build predictive models to forecast layoffs  


