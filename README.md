# AI-BOOTCAMP PROJECT
## PROJECT TOPIC: SALES ANALYSIS OF D-LITE ELECTRONICS LIMITED

## PROJECT OVERVIEW: D-Lite Electronics Limited operates across the four major regions in Nigeria; the North, South, East and West of the country. Due to the inconsistent nature of the data, management were not able to draw proper insight, thus, this project seek to establish how various factors influence sales performance within the four regions of the country through data cleaning, data analysis, data visualization and providing recommendaions.

## DATA SOURCE: Data for this work was provided as part of the resource material during AI Bootcamp training. 

## TOOLS USED: Several tools were deploy for this analysis, at the ingestion, data transformation and analysis stage. The raw data was cleaned using tools like TRIM, CLEAN, PROPER, LEN, SORT, Pivot Tables, Visualization etc. 

## DATA CLEANING: Replaced wrong spellings etc. Column entries were also converted to correct data format for data consistency. Cleaned up duplicate and empty entries.
### Date column; changed data type of date column to date.  changed the format to numbers form, then changed from numbers form back to date using the preferred style, stay in cell A1, format date to short date, right click and format cell, choose preferred style and copy down.
### - region:  =CLEAN(TRIM(PROPER(B2)))
### -  product: =PROPER(CLEAN(TRIM(C2)))          (Noted the row with unknown product)
### - category: =PROPER(TRIM(CLEAN(CLEAN(D2))))  
### - unit sold: changed data type to whole number
### - unit price: changed data type to currency
### - sales rep: =PROPER(TRIM(CLEAN(G2)))         (Change data type to text)
### - customer: =PROPER(TRIM(CLEAN(H2)))        (Change data type to text)
### - sales amount: =PRODUCT(E2,F2)                (change data type to currency)


## EXPLORATORY DATA ANALYSIS: 


## DATA ANALYSIS:



## SUMMARY: The outcome of this analysis is a clean dataset, KPIs metrics tracking, a visual dashboard highlighting performance by each region, products performance, sales reps performance. the dashboard also present opportunities for improvement and assist D-lite electronic makes data driven decision that will improve sales; and bring effectiveness and efficiency into the overall business operations of the company
