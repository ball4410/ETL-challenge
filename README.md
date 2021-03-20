# ETL-challenge
Extract:
My data sources are three CSV files and a JSON file which are in the resources folder. The CSV files have salary information and the data included special characters such as dollar signs and commas. The JSON file had a lot data, not of all which I needed, so the main goal with this file was to only include necessary information. 

Transform:
The main cleaning performed for the CSV file was to remove the dollar signs and columns. Since they are declared as numbers in Postgres, the data could not be loaded otherwise. 

For the JSON file, I needed to decide which information I wanted to keep and is pertinent. I also wanted to organize the columns so the data was layed out in a more organized matter.

Load:
I chose to load the data into Postgres since my main data sources are CSV files. I feel like their structure is more similiar to that of a relational database compared to non-relational. 

I created four table, one for each data source.
