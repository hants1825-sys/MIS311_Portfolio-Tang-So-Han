# MIS-311
## Introduction to Business Analytics
### *Data Analysis and Insight*
## Data Overview
Source of data: Electric Vehicle Population Data
Washington State Department of Licensing (DOL); Statistical Organizations.
Number of rows: 203 rows
Number of columns: 6 columns
The context: The Electric Vehicle Registration data for Washington State provides insight into how the Electric Vehicle adoption is spreading throughout the state. In addition to providing information on how many Electric Vehicles there are in each year and the various makes and models of Electric Vehicles, it also gives a general view of which brands are gaining dominance (such as Tesla), what years are growing the most rapidly and where (urban vs. rural) the most growth is happening. This type of information is vital for local governments that are trying to determine where to put charging infrastructure, companies that are determining what types of EV market strategies to pursue, energy providers that are trying to plan for future demand and consumers that are considering switching to an Electric Vehicle. The trends of sustainable transportation, the impact on the environment and the level of penetration of new Electric Vehicle technology into daily living are all important factors to be considered.
## Data Cleaning
Handling Missing Values: Detected 14 missing entries in location-based columns. These records were excluded from the analysis as they represent a negligible portion of the dataset and would not impact the overall trend.
  Vehicle Identification Number: Missing 4 values (A70, A74, A79, A93)
  City: Missing 2 values (B24, B31)
  Make: Missing 2 values (E16, E97)
  Model: Missing 1 value (F59)
Handling Duplicates: Identified and removed 3 duplicate records to ensure data integrity and avoid overcounting specific vehicles.
=> After deletion, there are 189 rows and 6 columns left.
