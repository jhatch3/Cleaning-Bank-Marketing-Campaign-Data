Bank Marketing Data Cleaning Project
- This project involves cleaning and preparing a dataset collected from a bank’s recent marketing campaign that aimed to promote personal loans. The cleaned data is structured to be used for future campaigns.

Project Goals
- Load, inspect and clean a CSV file named bank_marketing.csv
- Clean and reformat columns according to specific business rules
- Split the dataset into three clean CSV files:
  - client.csv
  - campaign.csv
  - conomics.csv

Key Tasks
- Replace invalid or unclear values (e.g., "unknown" → NaN, "." → "_")
- Convert string columns to Boolean (e.g., "yes" → 1, "no" → 0)
- Combine day, month, and a constant year into a proper date format (YYYY-MM-DD)
- remove unnecessary columns and create well-structured DataFrames
- Export the cleaned DataFrames to CSV for future database import

What I Learned
- How to use Pandas and NumPy for data cleaning
- Data type conversion and string manipulation
- Handling missing or incorrect values
- Creating and formatting dates from multiple columns
- Structuring data to match a relational database format

WORK CITED
- Project done from DataCamp's Website
- https://www.datacamp.com/datalab/w/951154df-5fc0-4b26-a389-f80434295e72/edit
